# CC2652P USB stick
CC2652P based Zigbee coordinator/router

## Flashing
- download [cc2538-bsl](https://github.com/JelmerT/cc2538-bsl) (you may need to install Python and/or other dependecies listed there)
- download [firmware](https://github.com/Koenkk/Z-Stack-firmware)
- run (change COM port to suit yours and specify location of downloaded FW)
```
python cc2538-bsl.py -p COM8 -w ./CC1352P2_CC2652P_other_router_20210128.hex
```

### BOM
| Qty | Value | Package | Component |
|:---:| --------- | ----- | ------- |
| 2 | 1uF/10V | 0805 | Ceramic capacitor |
| 1 | 100n | 0805 | Ceramic capacitor |
| 1 | 10n | 0805 | Ceramic capacitor |
| 1 | CH340C | SO16 | USB to Serial |
| 1 | USB A | | USB Connector |
| 1 | Red LED | 0603 | |
| 1 | Green LED | 0603 | |
| 1 | 100R | 0805 | Resistor |
| 1 | 1K | 0805 | Resistor |
| 1 | 820R | 0805 | Resistor |
| 1 | 10K | 0805 | Resistor |
| 1 | SMD button |  |  |
| 1 | MCP1802T-3302I/OT | SOT23-5 | LDO regulator |
| 1 | EBYTE-E72|  | CC2652P based wireless module |
