# firefox-theme-frame
A simple Firefox theme that disables everything but the titlebar

## How to use

1. Check out this repository.
   - `git clone git@github.com:garrett/firefox-theme-frame.git`
2. Run Firefox, pointing it at your checked out repo.
   - `firefox --new-instance --window-size 1024,768 --profile $PWD/firefox-theme-frame https://example.com/`

To test running things for the first time, do a `git clean -ffxd` to remove extra files.

## Develop

To customize this theme further, make sure you open up devtools in the browser toolbox mode. This has been enabled in `user.js` already. To activate it, use the keyboard combo `Shift`+`Ctrl`+`Alt`+`i`. (Yes, it's really this many keys.) Then, you can use the picker icon (next to the inspector tab) to select a part of the Firefox UI, which is made up of HTML + CSS.

## License
Released under the public domain (CC0). Do with it as you wish.
