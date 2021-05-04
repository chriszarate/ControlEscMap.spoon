# Hammerspoon Control / Escape smart map

Map <kbd>Control</kbd> to both <kbd>Esc</kbd> and <kbd>Control</kbd>—tap for
<kbd>Esc</kbd>, hold for <kbd>Control</kbd>.

This spoon works best when you map another key to <kbd>Control</kbd> to make it
more accessible. I recommend <kbd>Caps Lock</kbd>, which is [easy to do][map] in
MacOS.

## Loading the sppon

Clone this repo in `~/.hammerspoon/Spoons/`. (After doing so, the path to this
readme should be `~/.hammerspoon/Spoons/ControlEscMap.spoon/readme.md`.

Now load the spoon from your Hammerspoon config:

```lua
hs.loadSpoon('ControlEscMap')
spoon.ControlEscMap:start({timeout = 0.2})
```

# Configuration

- `timeout`: Maximum time in seconds that will be considered a tap (default 0.2)

[map]: https://coderwall.com/p/cq_lkg/remapping-caps-lock-key-to-something-more-natural-on-mac-os-x
