# Changelog

All notable changes to **RocketTunnel for Windows** are documented here.

This project adheres to [Semantic Versioning](https://semver.org/). Each entry is
tagged with its release version and build number (`version#build`).

## 3.1.2 (build 39)

### Added

- **Receive configs from another device** — just like the TV app, Windows can
  now accept configurations sent from your phone with "Send to Device", so you
  no longer need to copy links or export files by hand.

### Improved

- **Engine improvements** — better connection reliability and performance.

### Fixed

- **Various bug fixes** — stability and smaller issues throughout the app.

## 3.0.8 (build 23)

### Added

- **Update suggestion** — the app now checks for newer releases and lets you
  know when one is available, so you can update without having to check the
  website yourself.

## 3.0.7 (build 22)

### Added

- **Clear installation errors** — a failed installation now stops with the
  reason shown and a log file you can send to support, instead of finishing as
  if it had worked.

### Fixed

- **Stuck on "Connecting"** — a failed connection attempt no longer leaves the
  app stuck; it returns to Disconnected and tells you what went wrong.
- **Faster status updates** — connection status now updates immediately instead
  of lagging behind the actual state.
- **Reinstalling** — installing over an existing installation no longer fails.
- **Logs screen** — logs now load reliably instead of showing an empty screen.
- **Proxy screen** — proxy status and details now refresh instead of showing
  stale values.
- **Various UI fixes** — small layout and rendering issues throughout the app.

## 3.0.6 (build 8)

### Added

- **Deep links** — `rockettunnel://` links and shared config links now open
directly in the app and import their configuration automatically.
- **Config export** — export your configurations from within the app.
- **Unsupported-Windows check** — the installer now detects unsupported Windows
versions and stops with a clear message instead of installing an app that
cannot run (see [system requirements](README.md#system-requirements)).

### Fixed

- **Stability**


