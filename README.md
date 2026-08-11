# AirPods Switch — Downloads

Signed and notarized `.pkg` installers for **AirPods Switch**, a small
macOS menu-bar app that reconnects your AirPods over Bluetooth with a
single click or a global keyboard shortcut.

This repository contains **only release downloads** — no source code.

## Download

Grab the latest `.pkg` from the [Releases page](../../releases/latest).

## Funktionen

- **Geräteliste in der Menüleiste** — zeigt alle gekoppelten AirPods/Beats
  sowie weitere Bluetooth-Audiogeräte auf einen Blick.
- **Klick zum Verbinden/Trennen** — ein Klick auf ein Gerät verbindet es
  oder trennt es wieder. Kein Suchen mehr im Bluetooth-Menü.
- **Bevorzugtes Gerät** — ein Gerät lässt sich als "bevorzugt" markieren
  (Stern); es ist das Ziel des globalen Tastenkürzels.
- **Globaler Tastenkürzel** (Standard **⌃⌥A**) — verbindet/trennt das
  bevorzugte Gerät von überall aus, auch ohne das Menü zu öffnen.
- **Automatisches Audio-Umschalten** — schaltet die System-Audioausgabe
  nach dem Verbinden automatisch auf das Gerät um.
- **Start bei Login** (optional) — die App kann sich beim Anmelden
  automatisch starten.
- **Läuft im Hintergrund** — kein Dock-Icon, minimaler Ressourcenbedarf.

Ideal, wenn deine AirPods auf **"Zuletzt mit diesem MacBook verbunden"**
stehen: ein Klick, und sie verbinden sich wieder mit deinem Mac.

## Install

1. Download the `.pkg`.
2. Double-click it and follow the installer.
3. Since the package is notarized by Apple, macOS Gatekeeper will not
   show a warning.

## Requirements

- macOS 13 or later.

## Uninstall

Move `AirPods Switch.app` from `/Applications` to the Trash. If you
enabled "Launch at login", turn that off in the app's menu first.
