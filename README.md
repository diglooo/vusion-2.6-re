# Reverse Engineering of a SES imagotag Vusion 2.6

This repository documents the reverse engineering efforts of the **SES-imagotag Vusion 2.6** Electronic Shelf Label (ESL).

## Hardware Overview
- Silicon Labs EFR32FG22C121 32-bit ARM Cortex-M33 based MCU
- 2.4 GHz radio transceiver (proprietary protocol)
- **E-paper Display**: Black white red yellow (BWRY)
- NFC chip NXP NT3H2111, 1K, I2C interface

![Vusion 2.6 Display](media/screen.jpg)

![Vusion 2.6 Display](media/back.jpg)

## PCB reverse engineering 
- E-paper display pinout, functionally identical to a Pervasive Displays E2213KS0E1 or E2266KS0C1
- MCU pinout

![Vusion 2.6 Display](media/vusion-2.6.jpg)

## Legal Notice

This project is for educational and research purposes only. All reverse engineering activities are conducted in compliance with applicable laws. The information provided here should not be used for any unauthorized or illegal purposes.

## Contributing

Contributions, findings, and improvements are welcome. Please open an issue or submit a pull request.

## Disclaimer

This is an independent research project and is not affiliated with, endorsed by, or sponsored by SES-imagotag or Silicon Labs.
