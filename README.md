### Kong

48 key orthogonal keyboard with offset bottom row

![top](img/chonkyKong_top.png)

## Features

- Hotswap sockets
- onboard rp2040
- production files for pcba
- case files are supplied (stl, dxf, as well as the freecad files)
- QMK with vial support
- completely open source, permissive license ([CERN-OHL-P](https://cern-ohl.web.cern.ch/home))

- bottom rows supported:
  - alpha thumbs
    - 1u 1u 1u
    - 2u 1u
    - 3u
  - numpad thumbs
    - 1u 1u 1u
    - 2u 1u
    - 1u 2u
  - makro cols
    - 1u 1u 1u 1u
    - 2u 1u 1u
    - 1u 1u 2u
    - 1u 2u 1u
    - 2u 2u

## Want one?

All production files you need to build your own board can be found here: [pcb](./prod/pcb) / [case](./prod/case).

Parts needed beside the assembled pcbs:

- up to 60 hotswap sockets ( mx or choc)

- up to 60 of your favourite switches (mx or choc)

- 8 m2 heat inserts

- 8 m2 screws

### firmware
firmware configs for qmk and vial can be found in the [firmware folder](./firmware).

The first time the pcb is plugged in, the bootloader will provide a drive to upload the firmware file. 
You may either build the firmware yourself or use the provided vial firmware files [here](./firmware/uf2). You can use VIAL ([download](https://get.vial.today/) to program your board after that, without need to build a new firmware.

### the rest

Everything in this repository is free to use however you might see fit. If you want to support me and my projects, please consider linking back to this repository if you build/change/use anything.

If you would like to send me a tip, you could do it [here](https://ko-fi.com/weteor) (Please don't feel like you have to).

