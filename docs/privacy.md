---
title: Privacy Policy
layout: default
permalink: /privacy/
---

# Privacy Policy — Homing

**Version 1.0, 5 September 2026**

This policy explains what Homing does with your data. The short version: the
app collects nothing, sends nothing and stores only your own settings on your
Mac. The longer version below follows Article 13 of the General Data
Protection Regulation (GDPR, in Austria implemented together with the
Datenschutzgesetz, DSG) and Apple's App Store requirements.

## 1. Controller

Christian Feichtinger
Minna-Meinhardt-Straße 2, 4600 Wels, Austria
E-mail: christian@feichti.at

Homing is a free, open-source, non-commercial utility maintained by a private
individual. There is no data protection officer, because none is required for
this activity (Art. 37 GDPR).

## 2. What the app does with data

Homing is a macOS menu-bar app that lists the AirPods and Bluetooth headphones
already paired with your Mac and connects or disconnects them.

**The app does not collect, transmit or share any personal data.**

- **No network access.** The app runs in the macOS App Sandbox without the
  network entitlement. It cannot open a connection to any server, including
  ours. There is no telemetry, no analytics, no crash reporting, no
  advertising and no account.
- **Bluetooth.** With your permission (System Settings > Privacy & Security >
  Bluetooth) the app reads the list of devices paired with your Mac and their
  connection state through Apple's IOBluetooth and CoreBluetooth frameworks.
  This information is shown in the menu and used to connect or disconnect the
  device you click. It is not stored beyond the moment the menu is open and
  never leaves your Mac. The app does not scan for, pair with or connect to
  unknown devices.
- **Settings stored on your Mac.** The app remembers four things in its own
  sandbox container (`~/Library/Containers/at.feichtinger.homing`): the Bluetooth
  address of the device you marked as preferred, your keyboard shortcut,
  whether audio output should switch automatically, and whether the first-run
  Bluetooth prompt was shown. These values stay on your Mac. Deleting the app
  and its container removes them.
- **Logs.** The app writes diagnostic messages to the macOS unified log
  (visible in Console.app). Device names are marked private and appear
  redacted unless you enable private data in Console.app yourself. Logs stay
  on your Mac and are not read by us.
- **Launch at login.** If you enable it, macOS registers the app as a login
  item through Apple's ServiceManagement framework. Nothing is sent anywhere.

Apple's App Privacy label for Homing is therefore **"Data Not Collected"**.

## 3. Data processed when you download or contact us

Although the app itself processes no personal data, the channels around it do.
In each case the other party is an independent controller under its own
privacy policy; we receive only what is described here.

| Situation | Data | Purpose and legal basis | Recipient and retention |
| --- | --- | --- | --- |
| Downloading the installer from GitHub or browsing this repository | IP address, browser data, GitHub account if signed in | Providing the download; Art. 6(1)(f) GDPR (legitimate interest in distributing the software) | GitHub, Inc. (Microsoft), USA, under the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement). We do not receive personal data; GitHub shows us only aggregate download counts. |
| Installing from the Mac App Store | Apple ID, purchase record, optional crash reports and usage statistics if you enabled "Share with app developers" in macOS | Apple's purchase and distribution process; Art. 6(1)(b) GDPR between you and Apple | Apple Inc. / Apple Distribution International Ltd., Ireland, under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). We see anonymised crash and statistics data only if you opted in, and cannot identify you from it. |
| Opening a GitHub issue | Your GitHub username and everything you write | Answering your request; Art. 6(1)(b) GDPR (support you asked for) and Art. 6(1)(f) | Public on GitHub for as long as the issue exists; you can edit or delete your comments. |
| Writing to christian@feichti.at | Your e-mail address, name if given, message content | Answering your request; Art. 6(1)(b) and (f) GDPR | Our mailbox, hosted in the EU. Deleted when the matter is closed, at the latest after two years, unless a legal obligation requires longer retention. |

Both GitHub (via Microsoft) and Apple are certified under the EU-U.S. Data
Privacy Framework, which the European Commission recognises as providing
adequate protection (Art. 45 GDPR). We do not transfer data to third
countries ourselves.

## 4. Your choices

There is nothing to opt in or out of, because the app collects no data. What you can control yourself (Bluetooth permission, launch at login, stored settings) is listed on the [Privacy Choices](../privacy-choices/) page.

## 5. Your rights

Under Articles 15 to 22 GDPR you have the right to access, rectification,
erasure, restriction of processing, data portability and to object. Because the
app stores nothing about you on our side, these rights apply in practice to
support correspondence only; write to christian@feichti.at and we will answer
within one month.

You can lodge a complaint with the Austrian supervisory authority:

Österreichische Datenschutzbehörde
Barichgasse 40-42, 1030 Wien
Telephone +43 1 52 152-0, dsb@dsb.gv.at, https://www.dsb.gv.at

## 6. Children

Homing is a general-purpose utility and does not address children in particular.
It collects no data from anyone, regardless of age.

## 7. Changes to this policy

We update this document when the app's behaviour changes. The version number
and date at the top identify the current text; the revision history is public
in this repository's commit log.
