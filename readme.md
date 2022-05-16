# Keyboard Layouts

I use the Keebio Iris keyboard as a standard, at work and at home. At work, I use a rev5 with mousekeys on the right hand, since I have a buttonless trackball for my left hand.

Because I use mousekeys in my layouts, you really should compile these yourself with QMK, rather than using QMK Configurator online, which has erratic mousekeys support. Just compile the JSON files into HEX locally with QMK and you'll be good.

## compiling

- install QMK

- do the compile

qmk compile -kb /keebio/iris/rev5 iris_v5_mac.json
qmk compile -kb /keebio/iris/rev6 iris_v6_nix_win.json

- grab firmware files from qmk_firmware folder in your home dir