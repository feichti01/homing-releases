# Homing — Downloads

Signed and notarized `.pkg` installers for **Homing**, a small macOS menu-bar
app that brings your AirPods back to your Mac over Bluetooth with a single
click or a global keyboard shortcut.

This repository contains **only release downloads** — no source code. The
source lives at [feichti01/homing](https://github.com/feichti01/homing).

> Releases up to `v1.0` were published under the app's former name,
> *AirPods Switch*. Homing replaces it; install the new package and remove the
> old app from `/Applications`.

## Download

Grab the latest `.pkg` from the [Releases page](../../releases/latest).

## Features

- **Device list in the menu bar** — all paired AirPods and Beats as well as
  other Bluetooth audio devices at a glance.
- **Click to connect or disconnect** — one click connects a device or
  disconnects it again. No more digging through the Bluetooth menu.
- **Preferred device** — mark one device as preferred (star); it is the target
  of the global shortcut.
- **Global shortcut** (default **⌃⌥A**) — connects or disconnects the preferred
  device from anywhere, without opening the menu.
- **Automatic audio routing** — switches the system audio output to the device
  after it connects.
- **Launch at login** (optional) — the app can start when you log in.
- **Runs in the background** — no Dock icon, minimal footprint, App Sandbox
  with the Bluetooth entitlement only.

Ideal when your AirPods are set to **"Last connected to this Mac"**: one click
and they find their way home.

## Install

1. Download the `.pkg`.
2. Double-click it and follow the installer. The app launches afterwards.
3. Since the package is notarized by Apple, macOS Gatekeeper will not show a
   warning.

## Requirements

- macOS 13 or later.

## Uninstall

Move `Homing.app` from `/Applications` to the Trash. If you enabled "Launch at
Login", turn that off in the app's menu first.

## Privacy, support and legal

- [Privacy Policy](PRIVACY.md) — the app collects no data; full GDPR notice.
- [Support](SUPPORT.md) — FAQ, how to report a problem, what to include.
- [Legal Notice](LEGAL.md) — disclosure under Austrian law, licence, trademarks.
