# Changelog

## 2.2

- Mouse: new global option "Right-click sends Back", with a single switch shared by the Windows tab and the Shortcuts tab. Off by default: right-click sends nothing. Shift + right-click always sends Back.
- Keep-awake: while you play on Android 14 or earlier, the phone is now kept awake by one windowless session per phone. When the last account closes, the phone's own sleep delay is restored.
- Fixed a race where a replacement keep-awake or screen-off session could start while the previous one was still stopping.
- No settings changes: older settings files keep loading as they are.

## 2.1

- Support window: a Liberapay button and the USDT (TRC20) address, with a copy button.
- Update check: on startup, in the background, the app reads the version file on the website and shows a discreet link under the version badge when a newer version is available. Nothing is downloaded or installed automatically.
- Light edition: a smaller download that uses the .NET 10 Desktop Runtime already installed on the machine, with the same application inside.
