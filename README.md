# pinquin87's Home Assistant Configuration

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

![GitHub Stars][stars-shield]
![GitHub Watchers][watchers-shield]
![GitHub Forks][forks-shield]

## About

This is my personal Home Assistant configuration, running my home automations. For more information about Home Assistant, see their website: https://www.home-assistant.io.

My Home Assistant runs on Hass.io. Hassio runs on Ubuntu server OS. This is hosted on a Dell Precision M4600 laptop running ESXi 6.7. I've upgraded to this from a Raspberry Pi for better performance and reliability.

A overview of the Home Assistant configuration, automations and devices will follow soon.

### Infrastructure
- Dell Precision M4600 laptop running VMWare ESXi.
- VM for Hass.io running Ubuntu server 18.04 LTS.
- VM for Plex.tv running Ubuntu server 18.04 LTS.

### Devices
- ?x Custom ESP8266 devices (mainly sensors) running ESPHome, Tasmota or custom firmware.
- 3x Sonoff Basic running ESPHome.
- 2x Sonoff Pow 2 running ESPHome. 
- 8x Action 433Mhz power plug.
- 2x LSC Smart Connect RGB ligts (running Tasmota)
- 5x LSC Smart Connect cwww lights (running ESPHome)
- ESP8266 as a MQTT to 433Mhz gateway running OpenMQTT Gateway.
- Nest thermostat.
- Apple TV HD (4th gen).
- Google Home Mini.
- Ubiquiti UniFi AP AC LR acces point.
- Multiple IOS and Android mobile devices.

### Hass.io add-ons
- InfluxDB
- Grafana
- DuckDNS
- ESPHome
- Pi-hole
- Unifi Controller
- Visual Studio Code
- SSH & Web Terminal

### Presence detection
Presence detection is done via the IOS app and Android app.

## Contributing

Please feel free to check out the code and feel free to contribute if you see any improvements!


## Authors & contributors

The original creator of this repository is [Fabian Tubbing][pinquin87].


## License

MIT License

Copyright (c) 2018-2020 Fabian Tubbing

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[commits-shield]: https://img.shields.io/github/commit-activity/y/pinquin87/Home-AssistantConfig.svg
[commits]: https://github.com/pinquin87/Home-AssistantConfig/commits/master
[contributors]: https://github.com/pinquin87/Home-AssistantConfig/graphs/contributors
[pinquin87]: https://github.com/pinquin87
[home-assistant]: https://home-assistant.io
[license-shield]: https://img.shields.io/github/license/pinquin87/Home-AssistantConfig.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/pinquin87/Home-AssistantConfig.svg
[stars-shield]: https://img.shields.io/github/stars/pinquin87/Home-AssistantConfig.svg?style=social&label=Stars
[forks-shield]: https://img.shields.io/github/forks/pinquin87/Home-AssistantConfig.svg?style=social&label=Forks
[watchers-shield]: https://img.shields.io/github/watchers/pinquin87/Home-AssistantConfig.svg?style=social&label=Watchers