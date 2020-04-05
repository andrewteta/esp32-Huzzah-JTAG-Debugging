##CMD Command to start OpenOCD with Adafruit ft232h breakout
openocd -f interface/ftdi/ft232h-module-jtag.cfg -f board/esp-wroom-32.cfg