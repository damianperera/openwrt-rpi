# OpenWRT for RPi 4
[![build](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml/badge.svg)](https://github.com/damianperera/openwrt-rpi/actions/workflows/build.yml)

Based off the works of [wulfy23/rpi4](https://github.com/wulfy23/rpi4) and includes the following enhancements:
- Obtains a DHCP client so that OpenWRT can obtain an IP from the WAN network
- Configures Google DNS servers so that domain names can be resolved
- Configures a 5GHz WiFi access-point on an isolated LAN network bridged to the WAN network
- Allows access to the LuCi web interface from both the LAN and WAN networks
- Allows SSH access from both the LAN and WAN networks

This enables you to flash a RPi 4 and connect to the OpenWRT interface directly from your existing home network, and starts up a WiFi network from the first boot.

## Release Schedule
Scheduled versions will be built and released once a week.
