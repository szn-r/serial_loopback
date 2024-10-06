# serial_loopback

The documentation for PySerial is [here](https://pyserial.readthedocs.io/en/latest/shortintro.html).

## Quick Start

Install using the quick start [here](https://pyserial.readthedocs.io/en/latest/pyserial.html), either via Conda or PyPi.

Connect 2 USB-UART bridges that are connected to a 433MHz HC-12 transceiver each. The documentation on HC-12 is [here](https://statics3.seeedstudio.com/assets/file/bazaar/product/HC-12_english_datasheets.pdf).

Note: 
- You may have to preconfigure HC-12 according to datasheet by setting the Baud Rate.
- Tera Term can be used. It can be downloaded from [here](https://teratermproject.github.io/index-en.html).

Run the `test_read.py` and `test_write.py`.
