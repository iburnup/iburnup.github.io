---
title: ESPNow Sensors
---
Multiple repositories for developing battery and solar sensors

##### 1. [espnow to mqtt gateway](https://github.com/iburnup/esp-now-gateway)

Data from multiple sensors is received using esp-now and formatted using the [BTHome format](https://bthome.io/format/)
This is decoded and re-transmitted as mqtt message over Ethernet.


| Channel | Location | Description                                   | Link | Frequency |
| ------- | -------- | --------------------------------------------- | ---- | --------- |
| 1       |          |                                               |      |           |
| 2       | Garden   | temperature, solar powered                    |      | 5 Mins    |
| 3       | Garden   | New solar panel testing                       |      | 5 mins    |
| 4       | Garage   | temperature,atmospheric pressure, light level |      |           |

