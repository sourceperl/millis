millis.c
--------

this sample is for an Atmel ATTiny85 (AVR uC)

to compile you need AVR-GCC toolchain for Linux.

install command for "debian like" GNU/Linux :
  sudo apt-get install gcc-avr binutils-avr gdb-avr avr-libc avrdude

to compile it        : make
to read program size : make size
to upload            : make upload
  |-> i use AVRDUDE with an Arduino UNO (with ArduinoISP sketch)
to clean directory   : make clean
