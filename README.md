# Vioneta Agro Node-RED Companion Integration

[![releasebadge]][release] [![Build Status][buildstatus-shield]][buildstatus-link] [![License][license-shield]](LICENSE.md)

_Companion Component to [node-red-contrib-vioneta-agro-websocket](https://github.com/Vioneta/node-red-contrib-vioneta-agro-websocket) to integrate Node-RED with Vioneta Agro._

## Features

- Create and update entities from Node-RED
  - binary sensor
  - button
  - number
  - select
  - sensor
  - switch
  - text
- Disable and enable Node-RED flows from Vioneta Agro UI
- Create Vioneta Agro webhooks and handle them in Node-RED
- Use Device triggers and action from Node-RED

## Minimum Requirements

- [node-red-contrib-vioneta-agro-websocket](https://github.com/Vioneta/node-red-contrib-vioneta-agro-websocket) v0.57+
- [Vioneta Agro](https://github.com/Vioneta/core) 2024.5+

## Installation

### Manual

1. Using your tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `nodered`.
1. Download _all_ the files from the `custom_components/nodered/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Vioneta Agro
1. Refresh your browser window (bug in HA where it doesn't update the integration list after a reboot)
1. From "Settings" in the Vioneta Agro sidebar, select "Devices and Services", click the blue [+ Add integration] button (in bottom right of the page) and search for "Node-RED", and install it.

## Configuration

Once installed and added via Vioneta Agro Integrations all configuration is done from within Node-RED.

---

[license-shield]: https://img.shields.io/github/license/Vioneta/vioneta-agro-node-red.svg?style=for-the-badge
[release]: https://github.com/Vioneta/vioneta-agro-node-red/releases
[releasebadge]: https://img.shields.io/github/v/release/Vioneta/vioneta-agro-node-red?style=for-the-badge
[buildstatus-shield]: https://img.shields.io/github/actions/workflow/status/Vioneta/vioneta-agro-node-red/push.yml?branch=main&style=for-the-badge
[buildstatus-link]: https://github.com/Vioneta/vioneta-agro-node-red/actions
