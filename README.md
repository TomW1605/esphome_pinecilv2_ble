# ESPHome PinecilV2 BLE
This is a config for a Bluetooth capable ESP32 to receive data from a PinecilV2 soldering iron and present the data to Home Assistant.

## Setup
To use this config you will need to update your PinecilV2 to the latest firmware build. you shoudl be able to download the latyest firmware from here https://github.com/Ralim/IronOS/actions/workflows/push.yml

Once you have your ESP32 setup with ESPHome copy the sensor and BLE config to the bottom of your config file and put in the BLE MAC address of your PinecilV2.

Here are some instructions on finding your PinecilV2's BLE MAC address using your ESP32, https://esphome.io/components/binary_sensor/ble_presence.html#esp32-ble-tracker-setting-up-devices

## Thanks
A big thanks to [@ithinkido](https://www.github.com/ithinkido) for his help getting started and working out some of the decoding and to [@Ralim](https://github.com/Ralim) for his help with IronOS and being increadably open to pull requests
