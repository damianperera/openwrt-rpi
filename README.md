# OpenWRT for RPi 4
[![build](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml/badge.svg)](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml) [![GitHub issues](https://img.shields.io/github/issues/damianperera/openwrt-rpi)](https://github.com/damianperera/openwrt-rpi/issues) [![GitHub license](https://img.shields.io/github/license/damianperera/openwrt-rpi)](https://github.com/damianperera/openwrt-rpi/blob/main/LICENSE) [![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fdamianperera%2Fopenwrt-rpi)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fdamianperera%2Fopenwrt-rpi)

Based off the works of [wulfy23/rpi4](https://github.com/wulfy23/rpi4) and includes the following enhancements:
- Configures a DHCP client so that OpenWRT can obtain an IP address from the WAN network
- Configures Google DNS servers so that domain names can be resolved
- Configures a 5 GHz WiFi access-point on an isolated LAN network using the onboard WiFi
- Allows access to the LuCi web interface from both the LAN and WAN networks
- Allows SSH access from both the LAN and WAN networks

For more information on the default features included in this build and usage instructions, please refer the [wulfy23/rpi4](https://github.com/wulfy23/rpi4) repository.

_N.B._ In the above context WAN refers to your home/office network, and LAN refers to the network created by OpenWRT.

## Requirements
- RPi 4 Model B
- A fast SD card (ideally larger than 2 GB)

## Installation
- Download the RPi Imager ([macOS](https://downloads.raspberrypi.org/imager/imager_latest.dmg), [Windows](https://downloads.raspberrypi.org/imager/imager_latest.exe), [Ubuntu](https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb))
- Download the [latest release](https://github.com/damianperera/openwrt-rpi/releases/latest) from this repository
- Flash the `openwrt.img.gz` file using the RPi Imager onto your SD card

  ![Screen Recording 2021-06-06 at 12 13 04 PM (6)](https://user-images.githubusercontent.com/15967502/120920902-7478e580-c6c1-11eb-9b62-d4041fcac34d.gif)
- Boot up your RPi and wait for the initial setup to complete (5-7 mins)
- Obtain the IP address of the device using your main network router and use it to connect to the LuCi web interface

## Release Schedule
Automated builds have been scheduled for once a week. Urgent hotfixes will be manually triggered.
