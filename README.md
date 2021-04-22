# bme280_json.py
I put together [using BME280 I2C Tempretature Pressure Sensor in Python](https://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/)
and [a minimal http server](https://gist.github.com/nitaku/10d0662536f37a087e1b) to have a simple json server on a Raspberry Pi in a remote place that has a BME280 connected to it via I2C.
The json data is then read by [advanced-http-temperature-humidity plugin](https://github.com/ingowalther/homebridge-advanced-http-temperature-humidity) for [homebridge](https://github.com/homebridge/homebridge)
