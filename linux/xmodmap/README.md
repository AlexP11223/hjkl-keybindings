# xmodmap

The simplest method but does not work well in some cases.

Consider using [xkb](/linux/xkb) instead.

## Usage

    xmodmap FILE # such as xmodmap ./hjkl

Run `setxkbmap` (without parameters) to revert, or just log out/restart.

Add the command to `~/.xinitrc` to run on startup.

## Known issues

- Breaks non-English layouts: when you switch the input language (`Super` + `Space`) e.g. to Russian the letters on these keys will be disabled (and `caps` + `hjkl` will not work too) until you switch back to English.
- `shift` + `caps` + `hjkl` (text selection) doesn't work in some apps like IntelliJ IDE.
