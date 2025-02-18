# Modern restyle of Firefox's topbar.

![Theme showcase](./assets/Screenshot%202024-11-22%20210828.png "Theme showcase")

## Installation

1. Locate Firefox's profile directory by going to address `about:support`. The address will be under the `Profile directory` row.

2. `cd` into the profile directory and clone the repository into its `chrome` directory.

```bash
git clone https://github.com/dqvid/firefox-topbar.git chrome
```
3. Restart Firefox.

## ⚠️WARNING⚠️

This theme changes the `.titlebar-buttonbox-container` position property to `absolute`. It may cause interlap with the `List all tabs` button.

Move this button from topbar via `Customize toolbar` option in right click menu of topbar.
