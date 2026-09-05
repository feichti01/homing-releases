---
title: Privacy Choices
layout: default
permalink: /privacy-choices/
---

# Privacy Choices — Homing

**Version 1.0, 5 September 2026**

Homing collects no personal data, uses no tracking, no analytics and no
advertising, and never connects to the internet. There is therefore nothing to
opt in to or out of, no account to delete and no data to request from us.

This page lists what you can control yourself on your Mac.

## Bluetooth permission

Homing works only with your Bluetooth permission. You can withdraw it at any
time:

1. Open **System Settings > Privacy & Security > Bluetooth**.
2. Switch off **Homing**.

The app then shows nothing but a menu item that reopens this setting. Switch it
on again whenever you like.

## Launch at login

If you enabled **Launch at Login**, disable it in the Homing menu or under
**System Settings > General > Login Items**. macOS removes the entry
automatically when you delete the app.

## Settings stored on your Mac

Homing stores four values in its sandbox container: the preferred device's
Bluetooth address, your keyboard shortcut, the audio-switch setting and whether
the first-run prompt was shown. To erase them:

1. Quit Homing.
2. Delete the folder `~/Library/Containers/at.feichtinger.homing`.

The next launch starts with default settings. Deleting the app with an
uninstaller that removes containers has the same effect.

## Diagnostic logs

Homing writes diagnostic messages to the macOS unified log on your Mac. Device
names are marked private and appear redacted. We never receive these logs;
they are only sent to us if you copy them into a support request yourself.

## Mac App Store: sharing with the developer

If you installed Homing from the Mac App Store, macOS may share anonymised
crash and usage statistics with Apple and, if you allowed it, with us. You
control this under **System Settings > Privacy & Security > Analytics &
Improvements**: switch off **Share Mac Analytics** or **Share with App
Developers**. We cannot identify you from this data either way.

## Support requests

If you contacted us by e-mail or opened a GitHub issue, you can ask us to delete
that correspondence at any time by writing to christian@feichti.at. Public
GitHub issues can be edited or deleted by you directly.

## Your rights under the GDPR

Access, rectification, erasure, restriction, portability and objection
(Articles 15 to 22 GDPR): write to christian@feichti.at. You can also complain
to the Austrian data protection authority, the Datenschutzbehörde,
Barichgasse 40-42, 1030 Wien, dsb@dsb.gv.at.

See the full [Privacy Policy](../privacy/).
