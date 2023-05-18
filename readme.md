# Getting volume support for the rotary knob on MacOS:

1. run `qmk setup` in root folder
2. Create a layout using the QMK Configurator and save the JSON file to root folder as `gmmk_keymap.json`. Make sure to map “Quantum/Reset” – it’ll make your your life easier.
3. Compile your layout with `qmk compile -c ./gmmk_keymap.json`
4. Flash the resulting `gmmk_pro_gmmk_keymap.bin` to your keyboard, using qmk toolbox
