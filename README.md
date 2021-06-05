# OpenWRT for RPi
[![build](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml/badge.svg)](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml)

Based off the works of [wulfy23/rpi4](https://github.com/wulfy23/rpi4) and includes the following enhancements:
- Obtains a dynamic IP from the WAN gateway
- Configures Google DNS servers
- Configures a 5GHz WiFi access-point on the LAN network
- Allows access to the LuCi web interface from both the LAN and WAN networks
- Allows SSH access from both the LAN and WAN networks

This enables you to flash a RPi and connect to the OpenWRT interface directly from your existing home network.

## Release Schedule
Scheduled versions will be released at 00:00 UTC on the 1, 8, 15, 22 and 29th of every month.
