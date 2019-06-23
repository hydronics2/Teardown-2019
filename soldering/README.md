# Soldering

Parts list
- [Nordic Semiconductor nrf52840 bluetooth module](https://www.adafruit.com/product/4078)
- [LIS3DH Accelerometer](https://www.aliexpress.com/item/CJMCU-LIS3DSH-High-resolution-Three-axis-Accelerometer-Triaxial-Accelerometer-Module-LIS3DH/32879796761.html?)
- [SPI QUAD FLASH 2MB Memory](https://www.digikey.com/product-detail/en/gigadevice-semiconductor-hk-limited/GD25Q16CTIGR/1970-1010-1-ND/9484760)


Full parts list on [mouser](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=5d5a690db9).


[Here's the schematic](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/schematic.pdf)


![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/1_headers.JPG)
11 pin header for accelerometer.

![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/2_10k_pullup.JPG)
10K pullup resistor for the CS pin to initiate i2c on the accelerometer.

![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/3_3.3Voltage_reg.JPG)
3.3volt regulator and 100n(0.1uF) capacitor

![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/4_330ohmResistor.JPG)
Current limiting resistors for the LEDs. ~330ohms but anywhere from 220 to 510 is fine.

![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/4_330ohmResistor.JPG)
Current limiting resistors for the LEDs. ~330ohms but anywhere from 220 to 510 is fine.

![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/ws2812.JPG)
![](https://github.com/hydronics2/Teardown-2019/blob/master/soldering/pics/22.jpg)

Solder 3 wires onto the potentiometer.

That's it. We're all finished! We're leaving a few footprints unpopulated for this class.
