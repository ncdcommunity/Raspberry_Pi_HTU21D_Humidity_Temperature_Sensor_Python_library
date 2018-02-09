[![HTU21D](HTU21D_I2C.png)](https://store.ncd.io/product/htu21d-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/).

# HTU21D

The HTU21D is a digital humidity sensor with temperature output by MEAS.This sensor provides calibrated, linearized signals in digital, I2C format. HTU21D digital humidity sensors are dedicated humidity and temperature plug-and-play transducers for OEM applications (where reliable and accurate measurements are needed).These low power sensors are designed for high-volume and cost-sensitive applications with tight space constraints.The resolution of these digital humidity sensors can be changed by command (8/12bit up to 12/14bit for RH/T).
This Device is available from www.ncd.io

[SKU: HTU21D]

(https://store.ncd.io/product/htu21d-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface HTU21D humidity and temperature sensor With Raspberry Pi :

1. <a href="https://store.ncd.io/product/htu21d-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/">HTU21D humidity and temperature Sensor</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python

Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python HTU21D.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
