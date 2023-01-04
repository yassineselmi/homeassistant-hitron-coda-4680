[![hacs_badge](https://img.shields.io/badge/HACS-Default-green.svg)](https://github.com/custom-components/hacs)

# Hitron Coda 3680 Router: Presence Detection Integration for Home Assistant
An integration that offers presence detection by examining devices connected to a Hitron Coda 3680 Router.

The main reason behind this custom integration is to extend the out-of-the-box integration (Rogers Hitron Coda)[https://www.home-assistant.io/integrations/hitron_coda/] which does not support new routers like the Hitron Coda 3680


## Basic Configuration

```yaml
device_tracker:
  - platform: hitron_coda_3680
    host: !secret router_ip
    username: !secret router_username
    password: !secret router_password

```

## Configuration variables

This integration accepts the same configuration variables as the out-of-the-box [Device Tracker](https://www.home-assistant.io/integrations/device_tracker/).
