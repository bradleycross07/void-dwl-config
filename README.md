# void-dwl-config

My dwl build: [dwl](https://codeberg.org/dwl/dwl) v0.9 plus my patches and config on `main`.

- patches: gaps, focusdir, swapdir, nextlayout, autostart, alwayscenter, swallow, pertag,
  per-keyboard layouts, cursorsize (respects XCURSOR_SIZE), natural scrolling on the touchpad only
- `config.h` is tracked
- also carries three upstream lock-screen fixes from dwl main until the next release

Update: rebase `main` onto the newest dwl release, `make && doas make install`,
then `git push --force-with-lease origin main`.
