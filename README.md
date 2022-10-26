# STM32F03 Dev board


To flash the board use:

`stm32flash -b 115200 -i -rts,dtr:-dtr,rts -w ./program.bin /dev/ttyUSB0`

Make sure to use the appropriate path to the .bin you want to flash and change `ttyUSBO` to whatever your system assigned to the dev board.