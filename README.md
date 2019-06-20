# Teardown-2019
nrf52840 reference board


Programming from scratch.
Download nrfjprog command line utility from nordic semiconductor
Grab yourself a $20 programmer from digikey (j-link segger)

nrfjprog -f nrf52 --eraseall
nrfjprog --program feather_nrf52840_express_bootloader-0.2.11_s140_6.1.1.hex --chiperase -f nrf52 --reset

next a folder will open and pull the latest file over. As of 6/19/19 it is the following:
adafruit-circuitpython-feather_nrf52840_express-en_US-4.0.1.uf2
