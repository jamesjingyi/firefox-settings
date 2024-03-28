# FireFox Settings
## Styling

### Both:
1 . Go to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to True
2. Also in `about:config`, set `browser.tabs.cardPreview.enabled` to True and `browser.tabs.cardPreview.delayMs` to `250`
3. Navigate to the profile folder by going to `about:support` and then using `Open folder` in the `Profile folder` section
4. Create a `chrome` folder
5. Download Firefox Mod Blur from [here](https://github.com/datguypiko/)
6. Copy `remove_homepage_shortcut_title_text.css` from `Homepage mods > Remove text from homepage shortcuts`
7. Copy `cleaner_extensions_menu.css` from `Compact extensions menu > Style 1` to `chrome`

### macOS
8. Copy `min-max-close_buttons.css` from `Left side MacOS style buttons` then edit the following:
In `#navigator-toolbox:not([inFullscreen]) #TabsToolbar .titlebar-buttonbox-container {`
`top: 2px` -> `top: 12px`
`left: 0` -> `left: 1px`

It should look like this:
`#navigator-toolbox:not([inFullscreen]) #TabsToolbar`
`     .titlebar-buttonbox-container {`
`          visibility: visible !important;`
`          position: absolute !important;`
`          top: 12px !important;`
`          left: 1px !important;`
`         right: unset !important;`
`}`
9. Done!

### Windows
8. Copy `min-max-close_buttons.css` from `Left side MacOS style buttons`
9. Done!
