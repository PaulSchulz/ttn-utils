# The Things Network Utilities
This repository contains utilites that have been created to
assist working with The Things Network and IoT devices. They work from the
bash command line (CLI) in Ubuntu.

## Getting Started
To get started, checkout this repository.

Edit the 'application' file to contain the configuration details for
your TTN handler/server, application and device. 

Patches and pull requests are most welcome.
(Git Hint: Use a local branch so you don't accidentally commit your
application keys.)

## Utilities
```
monitor     - Display the MQTT messages for configured device.
monitor-all - Display the MQTT messages for all application devices.
downlink    - Schedule downlink data to configured device.
```

## Requirements
These bash scripts use the following additional tools (in Ubuntu).
```
mosquitto_sub,mosquitto_pub - Available in mosquitto-clients package
xxd                         - Tool to make (or reverse) a hex dump
jq                          - Lightweight and flexible command-line
                              JSON processor
```

## Configuration File (application)
```
HANDLER=au.<Region>.thethings.network
APPLICATION=<YourApplicationName>
KEY=<ttn-account-v2.-key>
DEVICE=<YourDeviceID>
# DEBUG=y
```