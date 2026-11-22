# Transit Tracker Lyon

A live board of Lyon's public transport for the [Transit Tracker](https://github.com/EastsideUrbanism/transit-tracker) LED display. You choose what each row shows:

- **a TCL line at a stop**: the line, its destination and the time to the next departure (real-time when available)
- **a Vélo'v station**: its name, free docks, mechanical bikes and electric bikes

This repository contains the firmware. To set everything up on your own computer with Docker, follow the guide: **[Running Transit Tracker Lyon (TCL + Vélo'v)](https://github.com/tiralmos/transit-tracker-lyon-api/blob/main/docs/deployment/deploy-tcl-velov.md)**.

The rest of the original Transit Tracker documentation (hardware, wiring, frame) is in [`docs/`](docs/) and applies unchanged.

## Updating from the bike-only firmware

A display that ran the earlier Bike Tracker firmware keeps its Vélo'v stations after updating: while no rows are set, the firmware shows the stations from the old settings. Once you save rows in the configurator, those are used instead.

## Related Projects

- [Transit Tracker Lyon API](https://github.com/tiralmos/transit-tracker-lyon-api) &mdash; serves TCL departures (GTFS) and Vélo'v station availability (GBFS) to the display
- [ESPHome Transit Tracker Lyon Component](https://github.com/tiralmos/esphome-transit-tracker-lyon) &mdash; the ESPHome component which draws the rows
- [Transit Tracker Lyon Configurator](https://github.com/tiralmos/transit-tracker-lyon-configurator) &mdash; the web-based tool to flash the display and choose its rows

Forked from [EastsideUrbanism/transit-tracker](https://github.com/EastsideUrbanism/transit-tracker).
