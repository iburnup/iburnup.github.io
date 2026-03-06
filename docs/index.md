### Overview 

Multiple repositories for developing battery and solar sensors

##### 1. [espnow to mqtt gateway](https://github.com/iburnup/esp-now-gateway)

Data from multiple sensors is received using esp-now and formatted using the [BTHome format](https://bthome.io/format/)
This is decoded and re-transmitted as mqtt message over Ethernet.


---
title: Audio alert speaker
description: play wav files (sounds or speech) based on mqtt messages
tags:
  - iot
  - wip
---
#### Overview

#### Plan

##### Phase One

1.  Read file from CD card
2. Play file using I2S
3. Include MQTT - Just play to start.
4. 3d print suitable case

##### Phase two

1. Additional MQTT messages - list files, add new files
2. Version that sends sound to Bluetooth speaker in place of I2S

#### Links


https://esp32io.com/tutorials/esp32-mp3-player
https://www.makerguides.com/playing-audio-with-esp32-and-max98357/
https://github.com/pschatzmann/ESP32-A2DP
https://github.com/pschatzmann/arduino-audio-tools
https://www.pullupresistor.com/bluetooth_audio_streamer.html
https://www.pschatzmann.ch/home/2020/09/15/sending-sound-from-an-esp32-to-a-bluetooth-sink-e-g-bluetooth-speaker/
https://www.pschatzmann.ch/home/2021/04/29/bluetooth-a2dp-streaming-from-files-on-a-sd-card/
https://forum.arduino.cc/t/using-esp32-under-arduino-ide-as-bluetooth-source/1416125/8
https://makerworld.com/en/models/1232745-voice-assistant-wyoming-satellite#profileId-1251755

