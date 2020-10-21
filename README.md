# SpaceX Next Launch and Starman Data Integration

<a target="_blank" href="https://www.buymeacoffee.com/djtimca"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy me a coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;"></a> [![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

This integration will provide sensors for SpaceX Next Launch and Starman information from the SpaceX APIs.

Sensors include:
- Next Confirmed Launch Day
- Next Confirmed Launch Time
- Next Launch Countdown
- Next Launch Day (regardless of confirmed)
- Next Launch Time (regardless of confirmed)
- Next Launch Mission
- Next Launch Payload
- Next Launch Rocket
- Next Launch Site
- Next Launch Alert (Binary Sensor) - Launch in the next 24 hours
- Next Launch Alert (Binary Sensor) - Launch in the next 20 minutes
- Latest Launch Day
- Latest Launch Time
- Latest Launch Mission
- Latest Launch Payload
- Latest Launch Rocket
- Latest Launch Site
- Starman Current Speed
- Starman Current Distance from Earth

## Install

Install from the default HACS repository or by copying the contents of the spacex folder into your custom_components/spacex folder and rebooting your Home Assistant, go to Configuration -> Integrations and click the + to add a new integration.

Search for SpaceX and you will see the integration available.

Click add, confirm you want to install, and voila... you have the SpaceX Sensors in your Home Assistant.

Enjoy!
