# IOTA Pollen CLI Wallet

A CLI wallet to interact with Pollen network on ESP32.

# System requirements

* [VSCode with PlaftormIO](https://platformio.org/install/ide?install=vscode)  
* [espressif32](https://docs.platformio.org/en/latest/platforms/espressif32.html)  

# Support Commands (WIP)

* node_info: shows status of the connected node.
* balance: display current wallet balance

# Disclaimer

This application is based on [pollen_qianbao](https://github.com/oopsmonk/pollen_qianbao), it is under developing and tested with [GoShimmer-0.3.0](https://github.com/iotaledger/goshimmer/releases/tag/v0.3.0) and [espressif32 v2.0.0](https://github.com/platformio/platform-espressif32/releases/tag/v2.0.0).  

It's not guarantee to work with other GoShimmer release or systems, please use with caution!  

# Building and Running

## Checkout the Pollen ESP32 project and opening it via VSCode

```
git clone https://github.com/oopsmonk/iota_c_platformIO.git
cd iota_c_platformIO
git checkout origin/dev_pollen_esp32 -b dev_pollen_esp32
code .
```

## Project Configuration  

Find the `Run Menuconfig` in PlatformIO extension  

**Setup endpoint and wallet information is needed**  

![Image](https://i.imgur.com/pliZjSR.png)

## Running 

The `Upload and Monitor` will write the image into esp32 and start a terminal for monitoring the application.

![Image](https://i.imgur.com/kShngVj.png)
