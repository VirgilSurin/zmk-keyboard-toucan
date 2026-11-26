# ZMK config for beekeeb Toucan Keyboard

[The beekeeb Toucan Keyboard](https://beekeeb.com/toucan-keyboard/) is a wireless split 42-key column‑stagger keyboard that a display and a trackpad, with an aggressive stagger on the pinky columns.

# Keymap (Colemak-DH)

![Keymap](keymap-drawer/toucan.svg)

The diagram is redrawn by the `Draw keymap` workflow whenever `config/toucan.keymap` changes.

## Editing workflow

1. Edit `config/toucan.keymap`. It uses [urob/zmk-helpers](https://github.com/urob/zmk-helpers) macros (`ZMK_LAYER`, `ZMK_COMBO`, `ZMK_HOLD_TAP`, …) and the key-position labels from `zmk-helpers/key-labels/42.h`.
2. Push. `Build ZMK firmware` builds the firmware and `Draw keymap` commits an updated diagram, so run `git pull` before your next push.
3. Download `firmware.zip` from the workflow run, double-tap reset on the XIAO, and copy the `.uf2` onto the drive that appears. A keymap-only change only needs the left (central) half.

# License

The code in this repo is available under the MIT license.

The included shield nice_view_gem is modified from https://github.com/M165437/nice-view-gem licensed under the MIT License.

ZMK code snippets are taken from the ZMK documentation under the MIT license.

The embedded font QuinqueFive is designed by GGBotNet, licensed under under the SIL Open Font License, Version 1.1.
