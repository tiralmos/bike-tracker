# Bike Tracker

A live Vélo'v (Lyon bike-share) board for the [Transit Tracker](https://github.com/EastsideUrbanism/transit-tracker) LED display. Each row shows a station's name, its free docks, mechanical bikes and electric bikes.

This repository contains the firmware. To set everything up on your own computer with Docker, follow the guide: **[Running Bike Tracker for Lyon Vélo'v](https://github.com/tiralmos/bike-tracker-api/blob/main/docs/deployment/deploy-velov.md)**.

The rest of the original Transit Tracker documentation (hardware, wiring, frame) is in [`docs/`](docs/) and applies unchanged.

## Related Projects

- [Bike Tracker API](https://github.com/tiralmos/bike-tracker-api) &mdash; reads the Vélo'v GBFS feed and streams station availability to the display
- [Bike Tracker ESPHome Component](https://github.com/tiralmos/esphome-bike-tracker) &mdash; the ESPHome component which draws the stations
- [Bike Tracker Configurator](https://github.com/tiralmos/bike-tracker-configurator) &mdash; the web-based tool to flash the display and pick stations

Forked from [EastsideUrbanism/transit-tracker](https://github.com/EastsideUrbanism/transit-tracker).
