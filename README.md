# GhostClient

Eigener Minecraft-Launcher mit Glass-UI – Profile, Modrinth-Mods & -Modpacks, Multi-Account, Skin-/Cape-Verwaltung, Auto-Updates.

## Installieren

Neueste Version herunterladen und ausführen: **[Releases](../../releases/latest)** → `GhostClient Setup x.y.z.exe`.

Windows SmartScreen warnt beim ersten Start (die App ist nicht signiert): **„Weitere Informationen" → „Trotzdem ausführen"**.

Danach im Launcher unter **Konten** mit dem eigenen Microsoft-Konto anmelden – fertig. Ab dieser Version meldet der Launcher neue Updates selbst und installiert sie auf Klick.

## Zugriffskontrolle (`allowlist.json`)

Steuert, wer den Launcher zum Spielen benutzen darf.

- `enabled: false` → jeder darf spielen (Standard).
- `enabled: true` → nur Spieler in `allowed` (Minecraft-Name **klein geschrieben** oder UUID) dürfen starten.
- Jemanden **rauswerfen**: Namen aus `allowed` löschen und die Datei hier auf GitHub speichern. Wirkt beim nächsten Spielstart.
