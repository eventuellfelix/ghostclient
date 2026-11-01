# Ghost Client

Ein eigener Minecraft-Launcher für **Windows und macOS**: Profile, Mods und Modpacks von
Modrinth, mehrere Konten, Skin- und Cape-Verwaltung, Auto-Updates – und im Spiel ein
Client-Menü mit HUD-Editor und Kosmetik.

> **KEIN OFFIZIELLES MINECRAFT-PRODUKT. NICHT VON MOJANG ODER MICROSOFT GENEHMIGT ODER MIT IHNEN VERBUNDEN.**
> Minecraft ist eine Marke von Mojang AB. Zum Spielen brauchst du dein eigenes gekauftes Minecraft.

## Installieren

**[Ghost Client herunterladen](https://ghostclient.app/download)** – dieser Link liefert
immer die neueste Version und erkennt von selbst, ob du an einem Windows-Rechner oder an einem
Mac sitzt.

**Windows:** Datei ausführen. SmartScreen warnt beim ersten Start, weil sie nicht signiert ist:
**„Weitere Informationen" → „Trotzdem ausführen"**.

**macOS:** Das Installationsbild öffnen und **Ghost Client in den Programme-Ordner ziehen** –
nicht direkt aus dem Fenster starten, sonst kann er sich später nicht selbst aktualisieren.
Beim ersten Start meldet macOS, der Entwickler sei nicht überprüft: **Systemeinstellungen →
Datenschutz & Sicherheit**, dort ganz unten auf **„Dennoch öffnen"**. Nur dieses eine Mal.

Danach im Launcher unter **Konten** mit dem Microsoft-Konto anmelden. Neue Versionen meldet der
Launcher selbst und installiert sie auf Klick – auf beiden Systemen.

Voraussetzungen: **Windows 10 oder 11 (64 Bit)** oder **macOS 12 oder neuer**. Für den Mac gibt
es eine einzige Datei, die auf Apple Silicon und auf Intel läuft. Java bringt der Launcher
passend zur Minecraft-Version selbst mit.

## Was drin ist

- **Profile** je Minecraft-Version und Loader, jedes mit eigenem Ordner, Mods und Texturepacks
- **Mods & Modpacks von Modrinth** installieren und aktualisieren – und die Version einer
  einzelnen Mod gezielt wechseln, vorwärts wie rückwärts
- **Absturzhilfe**: Stürzt Minecraft ab, sucht der Launcher die Ursache im Protokoll, erklärt sie
  in Klartext und bietet, wo möglich, eine Lösung auf Knopfdruck an
- **Mehrere Konten**, umschaltbar auch mitten im Spiel
- **Skins & Capes** verwalten, mit 3D-Vorschau
- **Im Spiel** (rechte Umschalttaste): Client-Menü mit HUD-Editor, Mod-Übersicht und
  Kosmetik-Shop
- **Freunde einladen**: Jeder hat unter „Konten" einen eigenen Einladungslink. Meldet sich jemand
  darüber zum ersten Mal mit seinem Minecraft-Konto an, gibt es einen **Kosmetik-Key** – die
  Währung, mit der im Shop im Spiel Kosmetik gekauft wird. Ein Key je Konto, nie mehr

## Datenschutz

Konten und Anmeldedaten bleiben **auf deinem Rechner**. Die Anmeldung läuft über den offiziellen
Microsoft-Login; dein Passwort sieht der Launcher nie.

Für die Online-Funktionen geht das hier an den Ghost-Client-Server:

- **Konto und Installation:** Minecraft-Name und UUID, eine zufällige Installations-Kennung und
  die Client-Version
- **Verbindung:** deine IP-Adresse und der daraus abgeleitete ungefähre Standort (Land, Region,
  Stadt, Postleitzahl, Zeitzone) sowie dein Internetanbieter
- **System:** Betriebssystem, Prozessor, Arbeitsspeicher, Bildschirm und Sprache
- **Profile und Mods:** deine Profilliste und, wenn der Support danach fragt, welche Mods ein
  laufendes Spiel nutzt
- **Während du spielst:** Spielversion, Serveradresse und Profilname
- **Online-Funktionen:** Freunde, Kosmetik, Kosmetik-Keys und Einladungen
- **Wallet:** Aufträge, Guthaben und die dafür nötigen Chat-Zeilen des Servers
- **Beim Anmelden:** ein Nachweis, dass dir dein Minecraft-Konto gehört. Dein Zugangs-Token bekommt
  dabei nur Mojang, nie der Ghost-Client-Server

Das Ghost-Client-Team kann für den Support Aktionen in deinem Client auslösen, zum Beispiel ein
Profil starten, einen Server betreten oder verlassen oder eine Chat-Nachricht senden.

Nicht gesendet werden Passwörter, Zugangs-Tokens und Welten.

Andere Ghost-Client-Spieler sehen, dass du online bist und welche Kosmetik du trägst. Kosmetik,
Guthaben und wer wen eingeladen hat bleiben gespeichert, auch wenn du länger nicht spielst.

Diese Übertragung gehört zum Client und lässt sich derzeit nicht abschalten. Wer das nicht
möchte, sollte den Launcher nicht verwenden.

Der Server **GhostSMP.net** steht in deiner Serverliste an erster Stelle. Die Client-Mod läuft in
Fabric-, Forge- und NeoForge-Profilen, Vanilla-Profile bleiben unverändert.

## Dieses Repository

Hier liegt **kein Quellcode** – das Projekt ist privat. Das Repository dient der Verteilung:

- die **Releases** mit den fertigen Dateien für Windows und macOS
- `allowlist.json` – steuert, wer den Launcher zum Spielen benutzen darf; gespeichert sind nur
  Prüfsummen, keine Klartextnamen
- `release.json` – eine kleine Steuerdatei für den Launcher

Die Quellcode-Archive, die GitHub automatisch an jedes Release hängt, enthalten deshalb nur diese
Dateien.

## Fragen, Fehler, Wünsche

Über [Issues](../../issues) oder auf dem Discord-Server, der im Launcher unten links verlinkt ist.

## Rechte

Ghost Client ist ein privates Projekt von [eventuellfelix](https://github.com/eventuellfelix).
Alle Rechte vorbehalten.

Du darfst den Client kostenlos herunterladen und benutzen, so viel du magst. Nicht erlaubt ist,
ihn zu verändern, zurückzuentwickeln, nachzubauen oder unter eigenem Namen bzw. über andere
Wege weiterzuverbreiten. Wenn du ihn weiterempfehlen willst: verlink einfach dieses
Repository – so bekommt jeder die echte, aktuelle Fassung.
