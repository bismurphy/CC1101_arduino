# CC1101_arduino
A simple library for setting up and interfacing with the CC1101 radio transceiver.

This is derived from https://github.com/simonmonk/CC1101_arduino/tree/ad0370904b93a7063ac3ce45f8af85399292d903.

Major changes:
- Removed ELECHOUSE from all the function calls, now it's just CC1101 which is more usable.
- Removed hardcoding on the GDO pin numbers
- Added convenient functions for setting the registers on the chip (Calculating register values on the fly for frequency, offsets, etc as well as toggles for CRC, data whitening, etc
