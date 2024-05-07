# Lily58 Minimal Code Friendly Layout

This layout aims to balance muscle memory from a typical QWERTY layout while
having all the keys used for software development at the first layer only.

Features:

- Only one extra toggled layer with arrows, media and brightness keys that
  follow VIM convention and F keys.
- Matrix scan rate is improved from 1353 Hz that the default keymap achieves, to
  1548 Hz.
- [N-Key Rollover](https://en.wikipedia.org/wiki/Key_rollover#n-key_rollover).
- The
  [debounce algorithm](https://docs.qmk.fm/#/feature_debounce_type?id=types-of-debounce-algorithms)
  is Symmetric Eager per Key with 5 ms debounce time.
- The OLED screen shows the current layer and the keymap name in both screens.
- The keylogger functionality has been disabled for security reasons.

## Base Layer

```text
  ,-----------------------------------------.                    ,-----------------------------------------.
  |  `   |   1  |   2  |   3  |   4  |   5  |                    |   6  |   7  |   8  |   9  |   0  |BackSP|
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  | Tab  |   Q  |   W  |   E  |   R  |   T  |                    |   Y  |   U  |   I  |   O  |   P  |  \   |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  | Esc  |   A  |   S  |   D  |   F  |   G  |-------.    ,-------|   H  |   J  |   K  |   L  |   ;  |   '  |
  |------+------+------+------+------+------|   [   |    |    ]  |------+------+------+------+------+------|
  |LShift|   Z  |   X  |   C  |   V  |   B  |-------|    |-------|   N  |   M  |   ,  |   .  |   /  |Delete|
  `-----------------------------------------/       /     \      \-----------------------------------------'
                    | LCtl | LAlt | LGUI | / Space /       \ Enter\  |  -   |  =   |LOWER |
                    |      |      |      |/       /         \      \ |      |      |      |
                    `----------------------------'           '------''--------------------'
```

## Lower Layer

```text
 ,-----------------------------------------.                    ,-----------------------------------------.
 |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |                    |  F7  |  F8  |  F9  | F10  | F11  | F12  |
 |------+------+------+------+------+------|                    |------+------+------+------+------+------|
 |      |      |      |      |      |      |                    |      |      |      |      |      |      |
 |------+------+------+------+------+------|                    |------+------+------+------+------+------|
 |      |      |      |      |      |      |-------.    ,-------| Left | Down |  Up  | Right|      |      |
 |------+------+------+------+------+------|       |    |       |------+------+------+------+------+------|
 |LShift|      |      |      |      |      |-------|    |-------| Prev | VolDn| VolUp| Next |      |      |
 `-----------------------------------------/       /     \      \-----------------------------------------'
                   | LCtl | LAlt | LGUI | / Mute  /       \ Play \  | BriDn| BriUp| BASE |
                   |      |      |      |/       /         \      \ |      |      |      |
                   `----------------------------'           '------''--------------------'
```
