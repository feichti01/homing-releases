---
title: Support
layout: default
permalink: /support/
---

# Support — Homing

Homing is a free, open-source macOS menu-bar app maintained by one person.
Support is provided on a best-effort basis; you will normally hear back within
seven days.

## Before you ask

1. Read the [User Guide](https://github.com/feichti01/homing/blob/main/USER_GUIDE.md).
2. Check that your AirPods or headphones are already paired with this Mac in
   System Settings > Bluetooth. Homing only shows paired devices.
3. Check System Settings > Privacy & Security > Bluetooth: the switch for
   "Homing" must be on. Relaunch the app after changing it.
4. Make sure you run the [latest release](https://github.com/feichti01/homing-releases/releases/latest). Only the
   latest version receives fixes.

## Frequently asked questions

**The menu says "No paired AirPods found".**
The device has never been paired with this Mac, or Bluetooth access is off.
Pair it once through System Settings > Bluetooth, then click the Homing icon
again.

**Clicking a device flashes red.**
The connection attempt failed. Typical causes: the AirPods are in the case
with the lid closed, they are connected to an iPhone that is actively using
them, or they are out of range. Open the lid or put them in your ears and try
again.

**The keyboard shortcut does nothing.**
Another app or macOS already uses the combination. Choose **Change Shortcut…**
in the menu; the recorder reports conflicts and lets you pick another one.

**"Launch at Login" asks me to approve something.**
macOS requires your approval for login items. Open System Settings > General >
Login Items and enable Homing there.

**I upgraded from "AirPods Switch".**
Homing is the same app under a new name and a new identifier. macOS asks once
more for Bluetooth access, and the preferred device has to be picked again.
Remove the old "AirPods Switch.app" from /Applications.

## How to reach us

| Topic | Channel |
| --- | --- |
| Bug, unexpected behaviour | [Open an issue](https://github.com/feichti01/homing-releases/issues/new) in this repository |
| Feature idea | [Open an issue](https://github.com/feichti01/homing-releases/issues/new) and label it "enhancement" |
| Question in private, or anything involving personal data | E-mail christian@feichti.at |
| Security vulnerability | E-mail christian@feichti.at with the subject `homing security`. Please do not post it publicly. |

## What to include

- macOS version and chip (`sw_vers`; Apple menu > About This Mac).
- Homing version: Finder > select `/Applications/Homing.app` > Get Info, or
  the name of the `.pkg` you installed.
- Your headphones model.
- What you clicked and what happened. If possible, the relevant lines from
  Console.app filtered for `Homing`.

Never include passwords, certificates or other people's device addresses. See
[PRIVACY.md](../privacy/) for how support requests are handled.
