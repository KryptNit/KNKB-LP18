# KNKB-LP18

![Screenshot 2025-04-19 190141](https://github.com/user-attachments/assets/697888f0-7fcd-4500-b16b-3a89b81bc8b3)
![IMG_1448](https://github.com/user-attachments/assets/c77d7c40-db00-454c-b300-a1af70a0650b)



*A short description of the keyboard/project*

* Keyboard Maintainer: [KryptNit](https://github.com/KryptNit)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make knkblp18:default

Flashing example for this keyboard:

    make knkblp18:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
