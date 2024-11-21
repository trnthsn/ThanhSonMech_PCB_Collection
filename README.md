# ThanhSon.Mech PCB Collection

# E8ghty
![E8ghty](https://imgur.com/M4Oudco.png)
## Keymap
[Json E8ghty](Via/trnthsn_e8ghty_via.json)
## Firmware

| STM32F072  | STM32F103 |
| ------------- | ------------- |
| [STM32F072](Firmware/E8ghty/F072/trnthsn_e8ghty_stm32f072_via.bin)  | [STM32F103](Firmware/E8ghty/F103/trnthsn_e8ghty_stm32f103_via.uf2) |

# E8ghtyQK
![E8ghty](https://imgur.com/Ok3rE5l.png)
## Keymap
[Json E8ghtyQK](Via/trnthsn_e8ghtyQK_via.json)
## Firmware

| STM32F072  | STM32F103 |
| ------------- | ------------- |
| [STM32F072](Firmware/E8ghtyQK/F072/trnthsn_e8ghtyqk_stm32f072_via.bin)  | [STM32F103](Firmware/E8ghtyQK/F072/trnthsn_e8ghtyqk_stm32f103_via.bin) |


# Mjolnir70

![Mjolnir70](https://imgur.com/zgguqjk.png)
## Keymap
[Json Mjolnir70](Via/trnthsn_mjolnir70_via.json)
## Firmware

| STM32F072  | 
| ------------- |
| [STM32F072](Firmware/Mjolnir70/trnthsn_mjolnir70_via.bin)  |

# S6xty
![S6xty](https://imgur.com/XJ0A3sF.png)
## Keymap
[Json S6xty](Via/trnthsn_s6xty_via.json)
## Firmware

| STM32F072  | STM32F103 |
| ------------- | ------------- |
| [STM32F072](Firmware/S6xty/F072/trnthsn_s6xty_via.bin)  | [STM32F103](Firmware/S6xty/F103/trnthsn_s6xty_via.uf2) |

# S6xty Rev.2

![S6xty Rev.2](https://imgur.com/18nYBRO.png)
## Keymap
[Json S6xty Rev.2](Via/trnthsn_s6xty_via.json)
## Firmware

| STM32F072  | STM32F103 |
| ------------- | ------------- |
| [STM32F072](Firmware/S6xtyR2/F072/trnthsn_s6xtyr2_stm32f072_via.bin)  | [STM32F103](Firmware/S6xtyR2/F103/trnthsn_s6xtyr2_stm32f103_via.uf2) |

# S6xtyMikeVuong
# S6xty5
# S6xty5 Rev.2
# S6xty5Neo
# S6xty5Neo Rev.2
# S7venty
# S7venty Rev.2

# S6xty5

![S6xty5](https://i.imgur.com/bFKBlnm.jpg)


A PCB for 65% keyboards. Uses a Left USB Type C connector or JST SH daughter board. 

![Layout](https://i.imgur.com/6gSoh0e.jpg)

* Keyboard Maintainer: [Trnthsn](https://github.com/trnthsn)
* Hardware Supported: STM32, S6xty5, Bakeneko65, Krush65
* Hardware Availability: [Trnthsn](https://www.facebook.com/ThanhSon.mech)

Make example for this keyboard (after setting up your build environment):

    make trnthsn/s6xty5:default

Flashing example for this keyboard:

    make trnthsn/s6xty5:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
