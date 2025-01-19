# 1.0 - Useful links

- [Cyton Docs](https://docs.openbci.com/Cyton/CytonLanding/)

### 1.1 - Hardware

- [Cyton Board PCB Files](https://github.com/OpenBCI/V3_Hardware_Design_Files)
- [Cyton BOM (Bill Of Materials)](https://github.com/OpenBCI/V3_Hardware_Design_Files/blob/master/OpenBCI%20Cyton%20Designs/OBCI_Cyton_Plots/OBCI_V4_C_BOM.xlsx)

- [Cyton Board](https://docs.openbci.com/Cyton/CytonSpecs/)
- [Cyton Board Schematic](https://docs.openbci.com/Cyton/CytonSpecs/#openbci-cyton-board-circuit-schematic)
- [External Trigger on OpenBCI Cyton Board](https://docs.openbci.com/Cyton/CytonExternal/)

- [OpenBCI USB Dongle](https://docs.openbci.com/Cyton/CytonSpecs/#openbci-usb-dongle)
- [OpenBCI USB Dongle Schematic](https://docs.openbci.com/Cyton/CytonSpecs/#openbci-dongle-circuit-schematic)

- [WiFi Board](https://docs.openbci.com/ThirdParty/WiFiShield/WiFiLanding/)
- [WiFi Board Schematic](https://docs.openbci.com/ThirdParty/WiFiShield/WiFiLanding/#wifi-board-circuit-schematic)

### 1.2 - Firmware

- [Cyton Programming Tutorial](https://docs.openbci.com/Cyton/CytonProgram/)

- [Cyton Dongle Firmware](https://github.com/OpenBCI/OpenBCI_Radios)
- [Cyton Dongle Programming Tutorial](https://docs.openbci.com/Cyton/CytonRadios/) -- For experienced users only!

- [WiFi Shield Firmware GitHub](https://github.com/OpenBCI/OpenBCI_WIFI)
- [WiFi Shield Programming Tutorial](https://docs.openbci.com/ThirdParty/WiFiShield/WiFiProgam/)

### 1.3 - Forum

- [Hardware Discussions](https://openbci.com/forum/index.php?p=/categories/hardware)
- [Headwear Discussions](https://openbci.com/forum/index.php?p=/categories/headware)
- [Electrodes Discussions](https://openbci.com/forum/index.php?p=/categories/electrodes)

# 2.0 Component Sourcing

### 2.1 Discontinued Components

| Component Name    | Part Number          |
| ----------------- | -------------------- |
| BTLE Module       | RFD22301             |
| MicroSD Card Slot | ST-TF-003A           |
| 3V Zener Diode    | CZRQR52C3-HF         |
| 4 CAP ARRAY       | CKCL44X7R1H102M085AA |

### 2.2 - Is 4 layered Cyton PCB required?
Short answer - yes. Long answer [here](https://openbci.com/forum/index.php?p=/discussion/1997/building-cyton-questions-4-layer-required-bom-vs-schematic)

### 2.3 - RFD22301 Module Workarounds

The RFD22301 is no longer produced, but apparently you can just use the [WiFi shield](https://docs.openbci.com/GettingStarted/Boards/WiFiGS/) instead of the Bluetooth module! The only person I have found online to be successful with this is Haseeb. He outlines how he did it in [[Haseebs-thesis|his thesis]].

Useful links to follow about this problem:
- [RFD22301 is not available (reason: obsolete)](https://openbci.com/forum/index.php?p=/discussion/1701/rfd22301-is-not-available-reason-obsolete)
- [programming Cyton without RFduino dongle? / our completed SSVEP demo](https://openbci.com/forum/index.php?p=/discussion/1773/is-cyton-programming-possible-without-using-bluetooth-dongle)
