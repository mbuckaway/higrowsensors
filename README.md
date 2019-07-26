# HiGrow Sensors Project

## Purpose

This project aims to support uploading Temperature, Humidity, and Soil Moisture data for the Chinese HiGrow Sensor board to ThingsSpeak over WIFI on a schedule. The goal is to support the ESP32's low power mode (sleep) in between data cycles thereby making the battery last longer. This project is intended for experimentation only and not for long term usage.

## Future Directon

Future directions include using a LORA module instead of WIFI to send the data to a custom remote LORA concentrator, then create a custom designed board using something other than an ESP32 to lower power consumption as well as the ability to turn the sensors on/off via software to further lower power consumption.

## Required Software

Visual Studio Code and Platform.IO. It does not use the Ardrino IDE.

## URLs

Sample code: https://github.com/ihajar/Higrow-sensors
HiGrow Project: https://hackaday.io/project/25253-higrow-plants-monitoring-sensor (seems to be dead)
Another HiGrow Project: https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-web-server-arduino-ide/
Moisture Sensor Usage: https://wiki.dfrobot.com/Capacitive_Soil_Moisture_Sensor_SKU_SEN0193
Yet Another HiGrow Project: https://github.com/lucafabbri/HiGrow-Arduino-Esp

LilyGO HiGrow Project: https://github.com/LilyGO/higrowopen

