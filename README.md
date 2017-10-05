# FPGA-SDR-FILTER-FILES

This repository contains some of the Filter Files that I download into my FPGA SDR transceiver from an Arduino NANO used as the UI Control processor.

Note that, in the Arduino code, I store these filters in the Arduino's Program Memory, thus the "const PROGMEM int" in lieu of "static int" used by Dick, W1QG, in his original filter files (Dick used a PIC processor for UI control).

The file "AF_Filters_1.h" contains the filters I used in the audio RX Equalizer stage, while all other ".h" files are Base-Band Information Filters (centered at 0 Hz -- refer to blog post 3 in my FPGA SDR series).
