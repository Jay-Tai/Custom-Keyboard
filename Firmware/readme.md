# Firmware overview
This hackpad's firmware has been designed in [QMK](https://qmk.fm/). It is a powerful, yet simple way to design keyboards that have a lot of useful functions!
- The rotary encoder controls the volume of the computer, and when you hold FN, you can scroll. When you press the encoder, it will mute/unmute your zoom call.
- The 65 keys all perform different functions that can be adjusted by simply changing it's function in keymap.c.
- The OLED starts off with a startup animation, and then after, it turns into a cat! Specifically, the Bongocat!! <b>Credits to [nwii's bongocat](https://github.com/nwii/oledbongocat) for the source code!</b>
- All keys have SK6812 Mini-E LEDs beneath them and when you press a key, its LED will light up in a reactive typing way. Take a look [here](https://youtu.be/7f3usatOIKM?t=229)!
