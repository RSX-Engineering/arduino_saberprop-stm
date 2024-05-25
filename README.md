# Arduino Plugin for SaberProp

1. Open Arduino, go to 'Preferences' and add the following Board Manager URL: https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json
2. Go to 'Boards Manager' and install the 'STM32 MCU based boards' package version 2.7.1
3. Go to Arduino package location ...\Arduino15\packages\STMicroelectronics\hardware\stm32\, backup and remove the installed version (folder 2.7.1)
4. Clone this repository in the stm32 folder: git clone https://github.com/RSX-Engineering/arduino_saberprop-stm 2.7.1
5. Download the [ProffieOSxs source code](https://github.com/RSX-Engineering/ProffieOSxs) and open ProffieOS.ino
6. Select the 'SaberProp Lite' board in Arduino    
7. Verify and upload as usual.


More info on Arduino core support for STM32 based boards, [here](https://github.com/stm32duino/Arduino_Core_STM32/blob/main/README.md)
