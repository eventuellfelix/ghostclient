# GhostClient

Eigener Minecraft-Launcher mit Glass-UI – Profile, Modrinth-Mods & -Modpacks, Multi-Account, Skin-/Cape-Verwaltung, Auto-Updates.

> **KEIN OFFIZIELLES MINECRAFT-PRODUKT. NICHT VON MOJANG ODER MICROSOFT GENEHMIGT ODER MIT IHNEN VERBUNDEN.**
> Minecraft ist eine Marke von Mojang AB. Zum Spielen brauchst du dein eigenes gekauftes Minecraft.

## Installieren

**[GhostClient-Setup.exe herunterladen](../../releases/latest/download/GhostClient-Setup.exe)** und ausführen – dieser Link liefert immer die neueste Version.

Windows SmartScreen warnt beim ersten Start (die App ist nicht signiert): **„Weitere Informationen" → „Trotzdem ausführen"**.

Danach im Launcher unter **Konten** mit dem eigenen Microsoft-Konto anmelden – fertig. Neue Updates meldet der Launcher selbst und installiert sie auf Klick.

## Datenschutz

Konten, Profile und Anmeldedaten bleiben **auf deinem Rechner**. Die Anmeldung läuft über den offiziellen Microsoft-Login – GhostClient sieht dein Passwort nie.

Standardmäßig sendet der Launcher eine anonyme Nutzungsstatistik:

- eine zufällige Installations-ID und die Launcher-Version
- während du spielst: dein Minecraft-Name und deine UUID, damit Mitspieler sehen, wer gerade mit GhostClient online ist

Nicht gesendet werden Passwörter, Tokens, Chats oder Welten. Abschalten kannst du das jederzeit unter **Einstellungen → Anonyme Nutzungsstatistik senden**.

## Zugriffskontrolle (`allowlist.json`)

Steuert, wer den Launcher zum Spielen benutzen darf.

- `enabled: false` → jeder darf spielen.
- `enabled: true` → nur freigeschaltete Spieler dürfen starten (gespeichert als Hash, nicht im Klartext).
- Freigaben verwaltest du im Launcher unter **Konten → Admin**.

## Lizenz

Der Quellcode ist derzeit nicht veröffentlicht; die Releases dürfen frei genutzt werden. GhostClient ist ein privates Projekt von [eventuellfelix](https://github.com/eventuellfelix).
