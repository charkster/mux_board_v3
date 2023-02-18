# mux_board_v3
Custom PCB with SAMD21 QT PY controlling TWO ADG1606BRUZ 16 input muxes!

![picture](https://github.com/charkster/mux_board_v3/blob/main/mux_board_v3_pcb.png)

Check-out my **PDF** [schematic](https://github.com/charkster/mux_board_v3/blob/main/mux_board_v3_schematic.pdf) !!

The SAMD21 QT PY can be  programmed with the qt_py_samd21-usbtmc.uf2 file (drag-n-drop) and has the same USBTMC commands that my [Mux Board V1](https://github.com/charkster/mux_board_v1) had. Here is the list:

**MUX1:EN 1** # enable MUX1, a zero will disable the mux

**MUX1:SEL 1** # select S1 input, values 1 through 16 are valid

**MUX1:EN?** # this query returns the state of MUX1

**MUX1:SEL?** # this query returns the presently selected input

***RST** # disables all MUX enables and sets DAC to 0V

***IDN?** # returns valid commands and this URL

