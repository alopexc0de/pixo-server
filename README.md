# pixo-server

A general purpose server that can be used with pixo-thiclient


## What's the purpose?

The goal for this server is to communicate with the API provided by [pixo-thinclient](https://github.com/alopexc0de/pixo-thinclient) and provide various example methods such as 
* Uploading images provided to it to the pixo
* Send commands to show images
* management of all settings via web UI
* Reading accelerometer data
* OTA Updates (user provides compiled binary)
* Polling various sites for notifications and showing them on the pixo


## What is pixo-pixel?

Pixo Pixel is a 16x16 REB LED display, using an ESP32 microcontroller and a 3-axis Accelerometer + Gyro.

Originally created by [Sean Hodgens](https://github.com/IdleHandsProject/pixopixel) as a Make 100, the hardware is interesting but no general purpose firmware has been created publically. I've contributed to the project a bit in the past [here](https://github.com/alopexc0de/pixopixel/tree/fw_cleanup), in the form of updating the readme and also some expansion/rewriting of example display functions.