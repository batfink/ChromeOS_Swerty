# Swerty keyboard layout from Chrome OS
## Why?
For the people who like the US ANSI keyboard layout more than standard Swedish. This allows you to type Swedish effectively on a US keyboard.  
## Who is it for?
* Swedish people who want to type on thier US keyboard
* Developers that want a basic working script for making custom key remapping for thier Chromebooks without Crouton.
## Inspiration, resources and credit
##### Swerity
http://johanegustafsson.net/projects/swerty/  
##### Remap tutorial / inspiration
https://dgopstein.github.io/articles/chrome-keymapper/  
https://github.com/google/extra-keyboards-for-chrome-os  
##### API resource
https://developer.chrome.com/extensions/input_ime
##### Locale resource
https://developer.chrome.com/webstore/i18n#localeTable  
## Installation
1. Go to chrome://extensions.
2. Check Developer mode
3. Click on "Load unpacked extensions...".
4. Pick the directory containing the manifest for the extension you want to
enable.
5. Logout and then login again. (This may not be necessary.)
6. Go to chrome://settings/languages.
7. Make sure you have added swedish as a language
8. Select Swerty keyboard layout from the list.
9. Optionally, remove any keyboard layouts or input methods that are no longer
required.  
## How to Use
1. Press Ctrl + Shift + Space to cycle through the enabled keyboard languages.
2. Type away…
3. Ctrl + Space to toggle between the most recently used keyboard languages.  
## Known Limitations
- These extensions are not allowed on the login/lock screen.
- These extensions are not allowed on password fields.  
## Extra
Layouts that can be used in manifest.json to this date;  
  "be",
  "br",
  "ca",
  "ca(eng)",
  "ca(multix)",
  "ch",
  "ch(fr)",
  "cz",
  "cz(qwerty)",
  "de",
  "de(neo)",
  "dk",
  "ee",
  "es",
  "es(cat)",
  "fi",
  "fr",
  "fr(oss)",
  "gb(dvorak)",
  "gb(extd)",
  "hr",
  "hu",
  "ie",
  "is",
  "it",
  "jp",
  "latam",
  "lt",
  "lv(apostrophe)",
  "mt",
  "no",
  "pl",
  "pt",
  "ro",
  "se",
  "si",
  "tr",
  "us",
  "us(altgr-intl)",
  "us(colemak)",
  "us(dvorak)",
  "us(dvp)",
  "us(intl)",
  "us(workman)",
  "us(workman-intl)"
