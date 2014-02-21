libmpsse
========

Open source library for SPI/I2C control via FTDI chips

Building on OSX:
----------------

1. sudo port install libftdi1 libusb
2. export CPPFLAGS="-I/opt/local/include"
3. export LDFLAGS="-L/opt/local/lib"
4. ./configure && make && sudo make install
