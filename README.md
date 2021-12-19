# CC2652P USB stick
CC2652P based Zigbee coordinator/router

## Flashing
- download [cc2538-bsl](https://github.com/JelmerT/cc2538-bsl) (you may need to install Python and/or other dependecies listed there)
- download [firmware](https://github.com/Koenkk/Z-Stack-firmware)
- run (change COM port to suit yours and specify location of downloaded FW)
```
python cc2538-bsl.py -p COM8 -w ./CC1352P2_CC2652P_other_router_20210128.hex
```
