# Changelog

## 2.3

- Security hardening: update manifest pinned to the official site host, with optional signature check; settings import now shows a preview and lets you choose what to import; zone input re-validates the foreground after each step; closing a keymap ends any active gesture; an unknown Android user is refused instead of passing; keeper locks are per phone with a bounded release; sessions stop in parallel within a bounded shutdown; orphan cleanup compares canonical paths only; diagnostic reports mask bare transport serials.
- Upstream fixes: thermal readings ignore stale values with a 5 °C hysteresis; a refused input injection is re-checked after 30 seconds.
- Licence unchanged, still signed for Deaa and verified at startup.
- No settings changes: older settings files keep loading as they are.

## 2.2

- Mouse: new global option "Right-click sends Back", with a single switch shared by the Windows tab and the Shortcuts tab. Off by default: right-click sends nothing. Shift + right-click always sends Back.
- Keep-awake: while you play on Android 14 or earlier, the phone is now kept awake by one windowless session per phone. When the last account closes, the phone's own sleep delay is restored.
- Fixed a race where a replacement keep-awake or screen-off session could start while the previous one was still stopping.
- No settings changes: older settings files keep loading as they are.

## 2.1

- Support window: a Liberapay button and the USDT (TRC20) address, with a copy button.
- Update check: on startup, in the background, the app reads the version file on the website and shows a discreet link under the version badge when a newer version is available. Nothing is downloaded or installed automatically.
- Light edition: a smaller download that uses the .NET 10 Desktop Runtime already installed on the machine, with the same application inside.
