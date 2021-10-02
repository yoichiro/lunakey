# Lunakey Project

This project has some keyboards designed by Yoichiro Tanaka.


## Lunakey Mini

![PXL_20201126_230559644_trim](https://user-images.githubusercontent.com/261787/135699278-a7d3e8fc-2fd0-4624-bd7a-ec9648d5dd82.png)

Lunakey Mini is a 40% keyboard which has 44 keys and is splitted to left and right. Each side has 3 rows x 6 columns and 4 keys that are pressed by a thumb. Also, it has an ability to light up by Underglow LEDs on the bottom, an ability to display information by OLED modules and an ability to play a sound by a speaker module. Of course, the column-staggered key layout is the result of deep thinking to fit each finger and each key naturally. Lunakey Mini can assist your PC life everyday.

* [Lunakey Mini - Remap](https://remap-keys.app/catalog/BnvcH8rfVvhoT34bsP4r)
* [Build Guide (Japanese only)](https://www.eisbahn.jp/yoichiro/2020/12/lunakey_mini_build_guide_rev4.html)

### Features of Lunakey Mini

* 40% keyboard (3 rows and 6 columns for each side).
* Column-staggered key layout to fit each length of fingers.
* 4 keys for thumb fitted to ranges of movement of the finger naturally.
* Supported both Cherry MX compatible key switches and Kailh Choc low profile key switches.
* Can exchange key switches without soldering by adopting the key sockets.
* Underglow LEDs lighting effect.
* Provides a sound feedback by a piezoelectric speaker.
* OLEDs can put on each side (optional).
* Can customize with [Remap](https://remap-keys.app)

### Necessary Parts

* PCB x 2
* Top plate x 2
* Bottom plate x 2
* Cover plate x 2
* ProMicro x 2
* Head pins (12 pins) x 4
* TRRS socket x 2
* Tact switch (2 feet) x 2
* Diode (1N4148W) x 44
* LED (WS2812B) x 12
* Key socket (Cherry MX Compatible) x 44
* Key socket (Kailh Choc V1) x 44
* piezoelectric speaker (PKLCS1212E4001-R1) x 1
* Register 1kΩ x 1
* M2 spacer 7.5mm x 10
* M2 spacer 10mm x 4
* M2 bolt 5mm x 24
* M2 bolt 3mm x 2
* TRS Cable or TRRS cable x 1
* USB Micro B cable x 1
* Key switch（Cherry MX compatible or Kailh Choc V1） x 44
* Key cap（Cherry MX compatible or Kailh Choc V1, 1U） x 44
* OLED module （with pin socket） x 2 (optional)

## Lunakey Pico

![PXL_20210929_030923513](https://user-images.githubusercontent.com/261787/135699552-709d028c-7716-44f9-9142-e14e680ac727.jpg)

Lunakey Pico is a 40% keyboard which has 44 keys and is splitted to left and right. Each side has 3 rows x 6 columns and 4 keys that are pressed by a thumb. Also, it has an ability to light up by Underglow LEDs on the bottom and an ability to play a sound by a speaker module. Of course, the column-staggered key layout is the result of deep thinking to fit each finger and each key naturally.

The special feature of this Lunakey Pico is that Raspberry Pi Pico has been adopted. Users can use some firmwares: [KMK Firmware](https://github.com/KMKfw/kmk_firmware) and [PRK Firmware](https://github.com/picoruby/prk_firmware).

### Features of Lunakey Pico

* 40% keyboard (3 rows and 6 columns for each side).
* Column-staggered key layout to fit each length of fingers.
* 4 keys for thumb fitted to ranges of movement of the finger naturally.
* Supported both Cherry MX compatible key switches and Kailh Choc low profile key switches.
* Can exchange key switches without soldering by adopting the key sockets.
* Underglow LEDs lighting effect.
* Provides a sound feedback by a piezoelectric speaker.

### Necessary Parts

* PCB x 2
* Top plate x 2
* Bottom plate x 2
* Cover plate x 2
* Raspberry Pi Pico x 2
* Head pins (20 pins) x 4
* TRRS socket x 2
* Tact switch (2 feet) x 2
* Diode (1N4148W) x 44
* LED (WS2812B) x 12
* Key socket (Cherry MX Compatible) x 44
* Key socket (Kailh Choc V1) x 44
* piezoelectric speaker (PKLCS1212E4001-R1) x 1
* Register 1kΩ x 1
* M2 spacer 7.5mm x 10
* M2 spacer 10mm x 4
* M2 bolt 5mm x 24
* M2 bolt 3mm x 2
* TRRS cable x 1
* USB Micro B cable x 1
* Key switch（Cherry MX compatible or Kailh Choc V1） x 44
* Key cap（Cherry MX compatible or Kailh Choc V1, 1U） x 44

Note that TRS (three poles) cable does not work.


## Lunakey Macro

![PXL_20210801_081120101](https://user-images.githubusercontent.com/261787/135699876-0cde00c4-77dd-40b5-9984-46d17b465a78.jpg)

This is a keyboard which has 11 keys only. Users can customize all keys by assigning any key code freely and assigning macros with [Remap](https://remap-keys.app).

* [Lunakey Macro - Remap](https://remap-keys.app/catalog/IY0IjAQ6fM1G3DAKQjmm)

### Features of Lunakey Macro

* 11 keys.
* Supported both Cherry MX compatible key switches.
* Can exchange key switches without soldering by adopting the key sockets.
* Underglow LEDs lighting effect.
* Provides a sound feedback by a piezoelectric speaker.

### Necessary Parts

* PCB x 1
* Top plate x 1
* Bottom plate x 1
* Pro Micro x 1
* Head pins (12 pins) x 2
* Tact switch (2 feet) x 1
* Diode (1N4148W) x 11
* LED Tape (five WS2812B) x 1
* Key socket (Cherry MX Compatible) x 11
* piezoelectric speaker (PKLCS1212E4001-R1) x 1
* Register 1kΩ x 1
* M2 spacer 7.5mm x 4
* M2 bolt 5mm x 4
* USB Micro B cable x 1
* Key switch（Cherry MX compatible） x 11
* Key cap（Cherry MX compatible, 1U） x 11


## For Keyboard Developers

All PCB designs were created with KiCAD. And, all plate designs were drawn with Inkscape. 

### Dependencies

To open each KiCAD project normally, ou need to add following dependencies to your KiCAD as configure paths for each PCB file:

* "YOICHIRO_KBD_PATH" - https://github.com/yoichiro/yoichiro-kbd
* "SPEAKER_PATH" - https://www.snapeda.com/parts/PKLCS1212E4001-R1/Murata/view-part/
* "KBD_PATH" - https://github.com/foostan/kbd
* "KEEBIO_PATH" - https://github.com/keebio/Keebio-Parts.pretty

[foostan/kbd](https://github.com/foostan/kbd): Copyright (C) Kosuke Adachi, all rights reserved and published under MIT License.

[keebio/Keebio-Parts.pretty](https://github.com/keebio/Keebio-Parts.pretty): Copyright (C) Keebio, all rights reserved and published under MIT License.

## License

All files are published under [Lunakey License](https://github.com/yoichiro/lunakey/blob/main/LICENSE). This license consists of dual licenses, for commercial use and non-commercial use. Users who want to use files for the commercial purpose need to agree the commercial-use license. Otherwise, users need to agree the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license.
