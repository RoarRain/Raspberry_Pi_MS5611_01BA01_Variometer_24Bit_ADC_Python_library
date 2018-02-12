[![ MS5611_01BA01](MS5611_01BA01_I2C.png)](https://store.ncd.io/product/ms5611-01ba01-variometer-with-24-bit-analog-to-digital-converter-i2c-mini-module/).

#  MS5611_01BA01

From MEAS Switzerland, the MS5611-01BA is a new generation of high resolution altimeter sensors with an I2C bus interface.The sensor module includes a high linearity pressure sensor and an ultra low power 24-bit ΔΣ ADC with internal factory calibrated coefficients. It provides a precise digital 24-bit pressure and temperature value. Different operation modes allow the user to optimize for conversion speed and current consumption.
This Device is available from www.ncd.io 

[SKU: MS5611_01BA01]

(https://store.ncd.io/product/ms5611-01ba01-variometer-with-24-bit-analog-to-digital-converter-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MS5611_01BA01 variometer and 24bit ADC With Raspberry Pi :
1. <a href="https://store.ncd.io/product/ms5611-01ba01-variometer-with-24-bit-analog-to-digital-converter-i2c-mini-module/">MS5611_01BA01 variometer and 24bit ADC</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MS5611_01BA01.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
