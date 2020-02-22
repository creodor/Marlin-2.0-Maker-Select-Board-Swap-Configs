# Marlin-2.0-Maker-Select-Board-Swap-Configs

These are configuration files for the Marlin 2.0 firmware, for use with a Monoprice Maker Select v2 after a board swap from the stock Melzi to a MKS Gen 1.4.

The settings in the files work for me, on my printer. I do NOT guarantee them to work for anyone else.

I provide them as a starting point that is more likely to work than the default Wanhao i3 which is the closest option I could find.

Of very important particular note, in Configuration_adv.h I had to modify #define THERMAL_PROTECTION_HYSTERESIS 4 to #define THERMAL_PROTECTION_HYSTERESIS 10. You may not need that much flucuation.

Please note that my printer was modified from stock even before I swapped the control board.

You will require the Arduino IDE ( https://www.arduino.cc/en/main/software ) as well as the Marlin 2.0.x firmware ( https://github.com/MarlinFirmware/Marlin ).
These two files should go into the Marlin-2.0.x\Marlin\ directory, replacing the default Configuration.h and Configuration_adv.h files.
There are a lot of guides on how to upload the firmware to the board.
