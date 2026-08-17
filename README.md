# Ghost Client

Ein eigener Minecraft-Launcher: Profile, Mods und Modpacks von Modrinth, mehrere Konten,
Skin- und Cape-Verwaltung, Auto-Updates – und im Spiel ein Client-Menü mit HUD-Editor und
Kosmetik.

> **KEIN OFFIZIELLES MINECRAFT-PRODUKT. NICHT VON MOJANG ODER MICROSOFT GENEHMIGT ODER MIT IHNEN VERBUNDEN.**
> Minecraft ist eine Marke von Mojang AB. Zum Spielen brauchst du dein eigenes gekauftes Minecraft.

## Installieren

**[Ghost Client herunterladen](https://client.ghostsmp.net/download)** und
ausführen – dieser Link liefert immer die neueste Version.

Windows SmartScreen warnt beim ersten Start, weil die Datei nicht signiert ist:
**„Weitere Informationen" → „Trotzdem ausführen"**.

Danach im Launcher unter **Konten** mit dem Microsoft-Konto anmelden. Neue Versionen meldet der
Launcher selbst und installiert sie auf Klick.

Voraussetzungen: Windows 10 oder 11 (64 Bit). Java bringt der Launcher passend zur
Minecraft-Version selbst mit.

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

Konten, Anmeldedaten und Profile bleiben **auf deinem Rechner**. Die Anmeldung läuft über den
offiziellen Microsoft-Login; dein Passwort sieht der Launcher nie.

An den Ghost-Client-Server geht nur das hier:

- eine zufällig erzeugte Installations-Kennung und die Launcher-Version
- **während du spielst**: Minecraft-Name und UUID des spielenden Kontos. Daran hängen die
  Online-Anzeige und der kleine Ghost neben den Namen von Mitspielern, die ebenfalls mit Ghost
  Client spielen. Nach dem Beenden verschwindet der Eintrag wieder.
- deine **Kosmetik**: was für dein Konto freigeschaltet ist und was du davon angelegt hast –
  sonst könnten die anderen es nicht an dir sehen
- deine **Kosmetik-Keys**: dein Guthaben, wofür du es ausgegeben hast, und – wenn du über einen
  Einladungslink dazugekommen bist – von wem du eingeladen wurdest. Ohne das ließe sich weder
  ein Key gutschreiben noch verhindern, dass ein Konto ihn mehrfach auslöst
- **beim Anmelden**: ein Nachweis, dass dir dein Minecraft-Konto wirklich gehört. Der Client
  benutzt dafür das Schlüsselpaar, das Mojang jedem angemeldeten Spieler ausstellt – dasselbe,
  mit dem Minecraft deine Chatnachrichten signiert. Übertragen werden nur der öffentliche Teil
  samt Mojangs Signatur und eine damit unterschriebene Zufallsfrage. Dein Zugangs-Token bekommt
  dabei nur Mojang, nie der Ghost-Client-Server

Nicht gesendet werden Passwörter, Zugangs-Tokens, Chats, Welten oder deine Mod-Liste.

Kosmetik, Guthaben und wer wen eingeladen hat bleiben gespeichert, auch wenn du länger nicht
spielst – Freigeschaltetes und Bezahltes darf niemandem nach einer Pause abhandenkommen. Name und
UUID werden gelöscht, wenn ein Konto 90 Tage nicht mehr mit dem Client gespielt hat.

Diese Übertragung gehört zum Client und lässt sich derzeit nicht abschalten. Wer das nicht
möchte, sollte den Launcher nicht verwenden.

Zwei weitere Dinge, die der Launcher am Spiel ändert: Der Server **GhostSMP.net** steht in deiner
Serverliste an erster Stelle, und in Profilen mit passender Minecraft-Version wird die Client-Mod
mitgeladen (dafür laufen auch Vanilla-Profile still über Fabric).

## Dieses Repository

Hier liegt **kein Quellcode** – das Projekt ist privat. Das Repository dient der Verteilung:

- die **Releases** mit dem fertigen Installationsprogramm
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
