# Keyboard Layouts

I use the Keebio Iris keyboard as a standard, at work and at home. I moved from QMK to VIA when I moved to Iris v6 and v7, so note that my QMK maps may be a little out of date, and one of them has the vestiges of a system in which I had mousekeys on the thumb cluster to work with my buttonless trackball.

## VIA
VIA is so much easier to handle than QMK if you have the Iris in an aluminum case, or in any case without a window for the reset button. Just download VIA, import my keymap JSON, and modify as you see fit; changes will work live.

If you haven't yet flashed your Iris to work with VIA, check the keebio website for the latest VIA firmware. And remember to clear the EEPROM before you flash it with the VIA firmware.

## QMK

If you want to use my layout with mousekeys, you really should compile these yourself with QMK, rather than using QMK Configurator online, which has erratic mousekeys support. Just compile the JSON files into HEX locally with QMK and you'll be good.

### compiling

- install QMK

- do the compile

qmk compile -kb /keebio/iris/rev5 iris_v5_mac.json
qmk compile -kb /keebio/iris/rev6 iris_v6_nix_win.json

- grab firmware files from qmk_firmware folder in your home dir