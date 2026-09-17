# Color Picker for the Logitech MX Creative Keypad

Pick any color on any screen from one key.

- **Press the key**: a magnifying eyedropper appears. Click a pixel anywhere, on any monitor, and the key turns
  that color and shows its hex and RGB values.
- **The key's page** opens at the same time: your last six colours (press one to reuse it and copy its hex to
  the clipboard), the eyedropper, and the Windows color dialog for typing values or using custom swatches.
- **Keyboard while picking**: arrow keys nudge one pixel, Enter picks, Esc or right-click cancels. The back key
  on the keypad also cancels.

## Install

1. Download `ColorPicker_1_0_0.lplug4` from the latest release and double-click it. Logi Options+ installs it.
2. In Logi Options+, select the MX Creative Keypad, find **Color Picker** in the actions list and drag
   **Pick Color** onto a key. It works in every application profile.

Requires Windows and Logi Options+ 6.4 or newer. Nothing else to install.

**DO NOT give the key a custom icon in Logi Options+: the key draws itself, and any custom icon is removed so it
keeps showing the live colour.**

## Privacy

The plugin collects no data and makes no network connections. Your colors are stored only in Logi Options+'s
local plugin settings. The eyedropper takes a screenshot for the magnifier while it is open; it is never saved.

## Support

Report problems at the support link in the plugin's marketplace listing. The log is at
`%LOCALAPPDATA%\Logi\LogiPluginService\Logs\plugin_logs\ColorPicker.log`.

## Licence

MIT, see `LICENSE`.
