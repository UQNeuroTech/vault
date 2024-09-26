
## Bill Of Materials (BOM)

[link](https://github.com/OpenBCI/V3_Hardware_Design_Files/blob/master/OpenBCI%20Cyton%20Designs/OBCI_Cyton_Plots/OBCI_V4_C_BOM.xlsx)


## Component Sourcing
### Is 4 layered Cyton PCB required?
Short answer - yes. Long answer [here](https://openbci.com/forum/index.php?p=/discussion/1997/building-cyton-questions-4-layer-required-bom-vs-schematic)
### RFD22301 is not available :(

But apparently you can just use the [WiFi shield](https://docs.openbci.com/GettingStarted/Boards/WiFiGS/) instead of the Bluetooth module! The only person I have found online to be successful with this is Haseeb. He outlines how he did it in [[Haseebs-thesis|his thesis]].

Useful links to follow about this problem:
- [RFD22301 is not available (reason: obsolete)](https://openbci.com/forum/index.php?p=/discussion/1701/rfd22301-is-not-available-reason-obsolete)
- [programming Cyton without RFduino dongle? / our completed SSVEP demo](https://openbci.com/forum/index.php?p=/discussion/1773/is-cyton-programming-possible-without-using-bluetooth-dongle)
