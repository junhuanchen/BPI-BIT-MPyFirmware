# Esp32-MicroPyhton
Fit For BpiBit And BpiUno32.

# Config Guide

# shell exec `gedit ~/.profile`

#export PATH=$PATH:/root/esp32/xtensa-esp32-elf/bin

#export IDF_PATH=/root/esp32/esp-idf

#  and source `gedit ~/.profile`

# into `/micropython/ports/esp32`

use `make` build micropython firmware.bin

use `make deploy` flash and download firmware.bin

use `make erase` erase and flash default factory bin

more read Makefile not is makefile.
