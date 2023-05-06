# rpi-dashboard-node-red
Raspberry Pi ([Zero](https://www.raspberrypi.com/products/raspberry-pi-zero/)) simple dashboard based on [Node-RED](https://nodered.org/)

Just need to add node [node-red-contrib-string](https://flows.nodered.org/node/node-red-contrib-string)

![pic_phone_screen](https://github.com/joingig/rpi-dashboard-node-red/blob/main/rpiz-dash00.jpg "screen0")

Flow Schematic:

![flow_sch](https://github.com/joingig/rpi-dashboard-node-red/blob/main/flow-sch-pic0.png "flow_sch")

Node **sar-c-tail-awk-bc** can easyly replace node chain: **sar-c** -> **cut Average idle** -> **100-Idle**

Main [flow.json](https://github.com/joingig/rpi-dashboard-node-red/blob/main/flows%20.json)

# TODO

- [ ] Сonsider MemAvailable
- [ ] Add GPIO Activity
- [ ] :tada:

