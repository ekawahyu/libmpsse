libmpsse
========

Open source library for SPI/I2C control via FTDI chips

Building on OSX:
----------------

1. Install libftdi1 and libusb install using macport
2. Point CPPFLAGS="-I/opt/local/include"
3. Point LDFLAGS="-L/opt/local/lib"
4. ./configure && make && sudo make install
