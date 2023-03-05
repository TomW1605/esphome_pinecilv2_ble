# ESPHome PinecilV2 BLE
This is a config for a Bluetooth capable ESP32 to receive data from a PinecilV2 soldering iron and present the data to Home Assistant.

## Setup
To use this config you will need to update your PinecilV2 to the latest firmware build. you shoudl be able to download the latyest firmware from here https://github.com/Ralim/IronOS/actions/workflows/push.yml

Once you have your ESP32 setup with ESPHome copy the sensor and BLE config to the bottom of your config file and put in the BLE MAC address of your PinecilV2.

Here are some instructions on finding your PinecilV2's BLE MAC address using your ESP32, https://esphome.io/components/binary_sensor/ble_presence.html#esp32-ble-tracker-setting-up-devices

## Examples
![2023-02-04_23 44 58](https://user-images.githubusercontent.com/17092573/222944144-72a453ed-cf7b-4135-89e3-cf1f9836194f.png)
![2023-02-04_19 51 31](https://user-images.githubusercontent.com/17092573/222944143-6414dd7e-a75b-4fee-862a-588b2880e8b5.png)
<video src='https://user-images.githubusercontent.com/17092573/222945489-c2014c01-6e50-4301-adbd-195d81ad1fac.mp4'/>



## Thanks
A big thanks to [@ithinkido](https://www.github.com/ithinkido) for his help getting started and working out some of the decoding and to [@Ralim](https://github.com/Ralim) for his help with IronOS and being increadably open to pull requests
