# SpaceX Next Launch and Starman Sensors

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

Once installed, go to Configuration -> Integrations and click the + to add a new integration.

Search for SpaceX and you will see the integration available.

Click add, confirm you want to install, and voila... you have the SpaceX Sensors in your Home Assistant.

## Recommended Configuration Changes in Home Assistant

This integration includes a countdown timer sensor which will add a large amount of log entries on changes. It is highly recommended that you make the following change in your configuration.yaml to eliminate those log entries:

```
recorder:
  exclude:
    entities:
      - sensor.next_launch_countdown

Enjoy!