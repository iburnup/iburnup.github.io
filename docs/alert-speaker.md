---
title: Audio alert speaker
description: play wav files (sounds or speech) based on mqtt messages
tags:
  - iot
  - wip
---

A speaker for audio notifications from IOT system. 
Use an ESP32 to subscribe to MQTT messages and play sound files that have been saved to sd card


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

https://www.pschatzmann.ch/home/2021/04/29/bluetooth-a2dp-streaming-from-files-on-a-sd-card/

https://forum.arduino.cc/t/using-esp32-under-arduino-ide-as-bluetooth-source/1416125/8

https://makerworld.com/en/models/1232745-voice-assistant-wyoming-satellite#profileId-1251755

