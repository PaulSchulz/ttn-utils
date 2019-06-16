# The Things Network Utilities
This repository contains utilites that have been created to
assist working with The Things Network and IoT devices.

## Getting Started
To get started, checkout this repository.

Edit the 'application' file to contain the configuration details for
your TTN application and device. 

Patches and pull requests are most welcome.
(Git Hint: Use a local branch so you don't accidentally commit your
application keys.)

## Utilities
```
monitor     - Display the MQTT messages for configured device.
monitor-all - Display the MQTT messages for all application devices.
downlink    - Schedule downlink data to configured device.
'''

### Configuration File (application)
```
HANDLER=au.<Region>.thethings.network
APPLICATION=<YourApplicationName>
KEY=<ttn-account-v2.-key>
DEVICE=<YourDeviceID>
# DEBUG=y
'''