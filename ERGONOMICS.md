Physical ergonomics
---

# Posture

- [8 Steps To A Pain-Free Back (Esther Gokhale)](https://www.goodreads.com/book/show/2275868.8_Steps_to_a_Pain_Free_Back) - More like 8 chapters to a pain-free back, but still good. I did every exercise in this book and it fixed my lumbar pain in one week.
- Your eyes should be level with the top of your screen; measure the distance you need and buy a riser accordingly. I've been using a $20 knockoff of the portable "Roost" laptop stand for several years and I love it.
- The average ergonomic desk chair is terribly proportioned for short people, and I am unable to sit back against one without sitting cross-legged in it. As a very short person I've had the most luck with armless drafting chairs, benches, tailbone cushions, and floor cushions, but that's just me. Don't buy stuff just because marketing tells you to.
- A soft posture corrector can be helpful to remind your shoulders not to slouch forward.

# Software

- [Vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb) adds vim bindings to your browser so you don't have to use your mouse.

# Peripherals

[This lightning talk I made](https://docs.google.com/presentation/d/1rMRcxihBgw_P92T4y_71fgIy3SFMkRZEC9HJ8hEzxTY/edit?slide=id.g22d6dd4f5a9_0_5#slide=id.g22d6dd4f5a9_0_5) mostly focuses on keyboards, but includes diagrams on the natural position your body parts want to be in, and how to debug some common ergonomics issues you might have from computer use.

## Mouse

TBD but vertical mice work well for people with wrist pronation issues

## Keyboard

Ergonomic keyboards are intensely personal and varied, and no single one will work for everyone. Your best bet is to try [printing up some layouts](https://jhelvy.shinyapps.io/splitkbcompare/) to see what feels natural for your hands, and collect advice from people with similar use cases and similar types of repetitive strain injury.

In particular, when asking for keyboard recommendations, it is helpful to describe your particular RSI & situation. 
- is the pain in your wrist, pinky, thumb, forearm, etc?
- is the pain in your nerves, joints, or muscles?
- do you feel the pain on extension, flexion, movement in general, while pressing keys, etc?
- are there particular things about your current layout that give you pain? bad wrist angle, overreliance on pinky, etc?
- do you have any specialized workflows that benefit from potentiometers (rotary dials) or other hardware besides just keys? (video editing, CAD, etc; note that you can get low-cost `qmk` macropads with potentiometers if you don't want to deal with them on your primary keyboard.)
- how big are your hands? more importantly, what position do your hands prefer to rest in?
- what's your budget?
- how severe are your hand injuries / how fast do you need to acquire a different keyboard?

### Resources for finding the right keyboard layout for you

- [splitKbCompare](https://jhelvy.shinyapps.io/splitkbcompare/): a split keyboard layout comparison site where you can print life-size layouts to get a feel for them
- [aposymbiont's filterable split keyboard gallery](https://aposymbiont.github.io/split-keyboards/)
- [awesome-split-keyboards](https://github.com/diimdeep/awesome-split-keyboards): quick visual overview of split keyboards
- [r/ErgoMechKeyboards](https://www.reddit.com/r/ErgoMechKeyboards/): extremely friendly and knowledgeable community of ergonomic mechanical keyboard enthusiasts. (Note that although [r/MechanicalKeyboards](https://reddit.com/r/MechanicalKeyboards) may appear superficially similar and has some overlap, it is on average significantly more focused on aesthetics, collecting, and gaming; I would not refer to it for ergonomics issues.)
- [Infographic of mechanical keyboard form factors](https://i0.wp.com/superanked.com/wp-content/uploads/2020/10/SupeRanked-X04-Custom-Mechanical-Keyboard-Infographic-Desk-Mat-V3-Main.jpg?fit=2048%2C2048&ssl=1) by [SupeRanked](https://superanked.com)
- [kbd.news](https://kbd.news) posts cool custom keyboard builds and projects. Dangerously distracting if you are tempted by collecting keyboards, useful if you are looking for inspiration for a very specific mod you want to build.

### Notes on my RSI & setup

Body context: I am a vim user and touch typist with pinky nerve issues from ulnar nerve damage, minor thumb arthritis, and no wrist issues (yet). The pinky issues are the worst for me. QWERTY was not the source of my pain, so I have stayed on it. I don't like tucking my thumbs underneath my hands; there are some layouts you can try if you prefer that. I span a ninth chord on the piano. [My custom layout](https://github.com/rfong/shibui/blob/main/KEYMAP.md) requires 36 physical keys. I have 4 layers that give me 124 virtual "physical" key slots, not counting my mod-tap slots. The 3rd layer is mostly for shortcuts/macros and the 4th layer is mostly for hardware functions such as bluetooth connection switching; in practice. I only use around 100-110 of my available key slots, depending how you count my mod-taps.

My first split ergomech keyboard in 2021 was a wired [crkbd/Corne](https://github.com/foostan/crkbd) (open-source split 40% ortholinear keyboard), which makes great use of layers and has an exceptionally comfortable thumb layout that lets you transfer a lot of traditional pinky work to the thumbs. I used [Hako Violet](https://input.club/the-comparative-guide-to-mechanical-switches/tactile/hako-violet/) light tactile switches with 28g actuation force, which are the lightest tactiles available. I also hand-built a custom [trackpoint hotswap mod](https://github.com/manna-harbour/crkbd/issues/1#issuecomment-953258378) so that I don't have to use a mouse. I got RGB LED underlighting to look cool. In practice, I don't really use the LEDs.

In 2024, [I upgraded](https://rfong.github.io/rflog/2024/12/24/chocofi/) to the much more portable [Chocofi](https://shop.beekeeb.com/collections/chocofi), a wireless low-profile 36-key crkbd variant with Kyria stagger (this means that the pinky columns are vertically staggered downward to sit in a more natural hand position). Wireless keyboards use `zmk` rather than `qmk` firmware. `zmk` doesn't yet support PS/2 pointing devices, so I can't use my trackpoint mod with the chocofi. Battery life lasts a couple weeks and has never really been an issue because I am always using my keyboard with my laptop, so I can charge it straight off my laptop if I am running low.

Do not be fooled by how wacky [my keyboard setup](https://rfong.github.io/rflog/tag/keyboard) looks. I can type 140wpm on it just fine and code at approximately full speed (some things are a little slower, some things are a little faster). Ortholinear slowed me down to 20wpm at first, but after about 2 days of [monkeytype](https://monkeytype.com/) practice, I was back at full speed, and can still seamlessly switch to using a standard keyboard layout at full speed. It is very comfortable for me. Hope you also find something that works well for your hands!

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
- Interpret custom franken-keyboard hardware, such as a keyboard with a mini trackball soldered on
