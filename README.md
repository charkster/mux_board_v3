# mux_board_v3
Custom PCB with SAMD21 QT PY controlling TWO ADG1606BRUZ 16 input muxes!

**--> UPDATED design available: [mux_board_v5](https://github.com/charkster/mux_board_v5) <--**

![picture](https://github.com/charkster/mux_board_v3/blob/main/mux_board_v3_pcb.png)

Check-out my **PDF** [schematic](https://github.com/charkster/mux_board_v3/blob/main/mux_board_v3_schematic.pdf) !!

The SAMD21 QT PY can be  programmed with the qt_py_samd21-usbtmc.uf2 file (drag-n-drop) and has the same USBTMC commands that my [Mux Board V1](https://github.com/charkster/mux_board_v1) had. Here is the list:

**MUX1:EN 1** # enable MUX1, a zero will disable the mux

**MUX1:SEL 1** # select S1 input, values 1 through 16 are valid

**MUX1:EN?** # this query returns the state of MUX1

**MUX1:SEL?** # this query returns the presently selected input

***RST** # disables all MUX enables

***IDN?** # returns valid commands and this URL

![picture](https://github.com/charkster/mux_board_v3/blob/main/2x10stacking_header.jpg)

2x10 2.54mm stacking headers can be found on [Aliexpress](https://www.aliexpress.us/item/2251832794527968.html?gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US)

![picture](https://github.com/charkster/mux_board_v3/blob/main/SAMD21_QT_PY_.jpg)

SAMD21 QT PY and ADG1606BRUZ ICs can be found on Digikey/Mouser.
