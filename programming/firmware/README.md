Programming from scratch.
Download [nrfjprog command line utility](https://www.nordicsemi.com/?sc_itemid=%7B56868165-9553-444D-AA57-15BDE1BF6B49%7D) from nordic semiconductor

Grab yourself a $20 SWD programmer from [digikey/mouser](https://www.mouser.com/ProductDetail/943-8.08.91) (j-link segger)
You'll need to populate (solder) the SWD header onto the board and then just plug it in.

nrfjprog -f nrf52 --eraseall
nrfjprog --program feather_nrf52840_express_bootloader-0.2.11_s140_6.1.1.hex --chiperase -f nrf52 --reset

Once the hex firmware is flashed, a folder will open (FTHR840BOOT) and you can pull the latest circuitpython firmware, UF2 file, over into the folder. As of 6/19/19 it is the following:
adafruit-circuitpython-feather_nrf52840_express-en_US-4.0.1.uf2

That's it. If everything goes right, the RTHR840BOOT folder will close and a CIRCUITPY will open.

Adafruit maintains the hex bootloader [here](https://github.com/adafruit/Adafruit_nRF52_Bootloader/releases)

Adafruit maintains the uf2 circuitpython firmware [here](https://github.com/adafruit/circuitpython/releases)
