# Hacking a Bluetooth Device - Null Kolkata

This is a simple demonstration of how one can hack a Bluetooth device by enumerating the characteristics and its controls to write arbitrary data that will indeed control the device.

![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/falcnix/Hacking-a-Bluetooth-Device-NULL-Kolkata) [![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)  [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) [![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

---

## Requirements

- ESP32 DEV Board
- Raspberry pi 4(optional)
- Any smartphone preferably Android OS 

---
## Installation / Getting Started
- [Follow to install necessary ESP32 components and to upload the code](https://github.com/falcnix/Hacking-a-Bluetooth-Device-NULL-Kolkata/tree/main/ESP32%20Arduino%20Code)
- Install the [Android application](https://github.com/falcnix/Hacking-a-Bluetooth-Device-NULL-Kolkata/blob/main/APK/README.md)

---

## Commands
Note: I am making use of bluetoothctl here 

| Command | Description |
| ------- | ----------- |
| `hciconfig` | To check the host controller interface that is present in our attacking system  |
| `hciconfig hcix up/down` | To enable and disable the ble adapter |
| `hcitool scan` | To scan the ble devices in our vicinity  |
| `bluetoothctl` | Interactive bluetooth control tool that is one-stop shop for all the requirements for bluetooth pentesting  |
| `show` | Shows that we are making use of raspberry pi HCI  |
| `scan on` | Turn the scanning on  |
| `scan off` | Turn the scanning off  |
| `devices` | Listing the paired/connected device  |
| `pair MAC_address` | Pairing  |
| `menu gatt` | Listing different set of commands to read and write to the characteristics  |
| `list-attributes` | Listing various characteristics we have  |
| `attribute-info` | Lists various flags that have been enabled on the characteristics  |
| `select-attribute characteristic` | Selecting the characteristics    |
| `read` | Read the data from the selected characteristic |
| `write 0x57` | Writing the data in hexadecimal value |

---

## Session Recording 

- [Youtube]() 

