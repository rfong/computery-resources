# Physical ergonomics

## Keyboard
Ergonomic keyboards are intensely personal and varied, and no single one will work for everyone. Your best bet is to try printing up some layouts to see what your hands like, and get advice from people with similar use cases and similar types of repetitive strain injury.

- [awesome-split-keyboards](https://github.com/diimdeep/awesome-split-keyboards): quick visual overview of split keyboards
- [aposymbiont's filterable split keyboard gallery](https://aposymbiont.github.io/split-keyboards/)
- [splitKbCompare](https://jhelvy.shinyapps.io/splitkbcompare/): a split keyboard layout comparison site where you can print life-size layouts to get a feel for them
- [r/ErgoMechKeyboards](https://www.reddit.com/r/ErgoMechKeyboards/): extremely friendly and knowledgeable community of ergonomic mechanical keyboard enthusiasts. (Note that although [r/MechanicalKeyboards](https://reddit.com/r/MechanicalKeyboards) may appear superficially similar and has some overlap, it is on average significantly more focused on aesthetics, collecting, and gaming than on ergonomics issues.)
- [Infographic of mechanical keyboard form factors](https://i0.wp.com/superanked.com/wp-content/uploads/2020/10/SupeRanked-X04-Custom-Mechanical-Keyboard-Infographic-Desk-Mat-V3-Main.jpg?fit=2048%2C2048&ssl=1) by [SupeRanked](https://superanked.com)

As a vim user and touch typist with pinky RSI, minor thumb arthritis, and no wrist issues (yet), I use [light tactile switches](https://input.club/the-comparative-guide-to-mechanical-switches/tactile/hako-violet/) on a [crkbd/Corne](https://github.com/foostan/crkbd) (split 40% ortholinear keyboard), which makes great use of layers and has an exceptionally comfortable thumb layout that lets you transfer a lot of traditional pinky work to the thumbs.

### Firmware

Many indie keyboard users make use of [QMK](https://qmk.fm/), an open-source 
firmware project for heavily customizing computer input devices, with great 
support for layering and macros.

If you only need "basic functionality" (remapping keys and using layers and 
macros), there are some great streamlined tools for that which don't require 
you to write any code.
- [VIA](https://caniusevia.com/): an extremely user-friendly desktop app for quickly modifying keymaps and auto-reflashing your keyboard with the new configurations.
- [QMK Configurator](https://config.qmk.fm/): an online interface & tool for creating configurations for keyboards supported in `qmk_firmware`. Can use [QMK Toolbox](https://qmk.fm/toolbox/) to flash your board.

Some examples of advanced QMK functionality:
- Assigning a key different functions on tap vs. hold, or based on number of taps
- Custom LED/OLED behavior
- Interpret a joystick, trackball, etc