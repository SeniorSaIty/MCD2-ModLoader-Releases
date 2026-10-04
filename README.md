# MCD2 ModLoader — Downloads

Mod manager for **Minecraft Dungeons II** on Windows. This repository only holds the ready-to-use,
signed builds. Grab the newest one from **[Releases](../../releases)**.

> *Deutsche Fassung weiter unten.*

---

## What it does

- **Install mods** from `.zip`, `.7z`, `.rar` or loose `.pak/.utoc/.ucas` files — by file dialog,
  drag & drop, or straight from a Nexus Mods link. Each mod gets its own folder under
  `Content\Paks\~mods`.
- **Blueprint Loader** (by ewanhowell5195) is detected, installed, updated and repaired from Nexus with
  one click — Blueprint mods do not run without it.
- **Enable / disable** mods without deleting them (files get a `.disabled` suffix — the same convention
  as the MCDII Mod Manager, so both tools can be used side by side). Bulk actions, search, filter, sort.
- **Update check** against Nexus Mods for every linked mod, the Blueprint Loader and the loader itself.
  Local archives are recognised on Nexus automatically (MD5) and linked.
- **Repair**: installed files are checksummed; damaged or missing files are detected and the mod can be
  reinstalled from Nexus.
- **Skip intro**: replaces the startup videos with an empty clip; the originals are backed up and can be
  restored any time.
- Steam and Xbox app / Game Pass / Minecraft Launcher installations are found on all drives.

## Install

1. Download the newest `MCD2ModLoader-x.y.z-Setup.exe` (or the `.zip`) from **[Releases](../../releases)**.
2. Run the setup (no admin rights needed) or unpack the ZIP anywhere and start `MCD2ModLoader.exe`.
3. Requires the [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) (10.0.12 or newer).

## Good to know

- **Mods are used at your own risk.** Read each mod's page before installing it.
- **Nexus downloads with a free account** go through the "Mod Manager Download" button on the Nexus page,
  on purpose. The loader opens the page and takes over once you click; it does not bypass the wait or
  the click. Premium accounts download directly.
- **Updates of the loader are signed.** The loader only installs updates from this repository that carry
  a valid signature from the publisher.
- The source code lives in a separate, private repository.

---

# Deutsch

Mod-Manager für **Minecraft Dungeons II** unter Windows. Hier liegen nur die fertigen, signierten
Programmdateien — die neueste Fassung gibt es unter **[Releases](../../releases)**.

## Was er kann

- **Mods installieren** aus `.zip`, `.7z`, `.rar` oder losen `.pak/.utoc/.ucas` — per Dateidialog,
  Drag & Drop oder direkt über einen Nexus-Mods-Link. Jeder Mod bekommt einen eigenen Ordner unter
  `Content\Paks\~mods`.
- **Blueprint Loader** (von ewanhowell5195) wird erkannt, mit einem Klick von Nexus installiert,
  aktualisiert und repariert — ohne ihn laufen Blueprint-Mods nicht.
- **Aktivieren / deaktivieren**, ohne zu löschen (Dateien bekommen die Endung `.disabled` — dieselbe
  Konvention wie beim MCDII Mod Manager, beide lassen sich nebeneinander nutzen). Sammelaktionen,
  Suche, Filter, Sortierung.
- **Update-Prüfung** gegen Nexus Mods für jeden verknüpften Mod, den Blueprint Loader und den Loader
  selbst. Lokale Archive werden per MD5 bei Nexus erkannt und verknüpft.
- **Reparieren**: Installierte Dateien werden mit Prüfsummen erfasst; beschädigte oder fehlende Dateien
  fallen auf und der Mod lässt sich von Nexus neu installieren.
- **Intro überspringen**: ersetzt die Start-Videos durch einen leeren Clip; die Originale werden
  gesichert und lassen sich jederzeit zurückholen.
- Steam und Xbox-App / Game Pass / Minecraft Launcher werden auf allen Laufwerken gefunden.

## Installation

1. Neuestes `MCD2ModLoader-x.y.z-Setup.exe` (oder das `.zip`) unter **[Releases](../../releases)** laden.
2. Setup ausführen (keine Adminrechte nötig) oder das ZIP irgendwohin entpacken und `MCD2ModLoader.exe` starten.
3. Voraussetzung: [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) (10.0.12 oder neuer).

## Wissenswertes

- **Mods werden auf eigene Gefahr verwendet.** Vor dem Installieren die Seite des Mods lesen.
- **Nexus-Downloads mit kostenlosem Konto** laufen bewusst über „Mod Manager Download“ auf der
  Nexus-Seite. Der Loader öffnet die Seite und übernimmt nach dem Klick; Wartezeit und Klick werden
  nicht umgangen. Mit Premium geht der Download direkt.
- **Loader-Updates sind signiert.** Der Loader installiert Updates aus diesem Projekt nur mit gültiger
  Signatur des Herausgebers.
- Der Quellcode liegt in einem eigenen, privaten Projekt.

---

*Inoffizielles Werkzeug, nicht mit Mojang Studios oder Microsoft verbunden. Minecraft Dungeons II ist eine
Marke von Mojang Studios / Microsoft.*
