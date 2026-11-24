<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png">
    <img src="logo-light.png" alt="Task-Organizer-Logo" width="120">
  </picture>
</p>

<h1 align="center">Task Organizer</h1>

<p align="center">Deutsch · <a href="README.md">English</a></p>

<p align="center">
Ein Kanban-Board für Arbeiten, Aufgaben und To-dos – getrennt in <b>Privat</b> und <b>Geschäftlich</b>, in einer einzigen HTML-Datei.<br>
Ohne Server, ohne Konto, ohne Internetverbindung.
</p>

<p align="center"><b>Version 0.4.0 (Beta)</b> · <a href="CHANGELOG.de.md">Änderungen</a> · <a href="https://alpine-marmot.github.io/task-organizer/">App öffnen</a></p>

![Task Organizer im hellen Design, Bereich Geschäftlich](screenshots/light.png)

## Funktionen

- **Boards:** standardmässig Privat und Geschäftlich, dazu eigene Boards (z. B. für einen Verein) über das **+** in der Kopfzeile – je mit eigenen Aufgaben und Kategorien; Boards ein- und ausschalten, umbenennen, sortieren oder löschen
- **Vier Spalten:** Offen → Geplant → Warten → Erledigt
- **Aufgaben** mit Priorität 1–3, Kategorie, Fälligkeitsdatum und Notiz
- **Kategorien mit Farben:** entstehen beim ersten Eintippen und werden danach vorgeschlagen; die Farbe erscheint als Rand der Karte
- **Kunden** (Boards mit eingeschaltetem Kundenfeld): entstehen automatisch, werden beim Tippen vorgeschlagen, mit Ansprechperson, Telefon und E-Mail
- **Kundenkarte:** Telefon und E-Mail zum Anklicken, alle offenen Aufgaben nach Spalte, erledigte und archivierte Aufgaben, «Neue Aufgabe für …»
- **Kunden-Import** aus CSV (Excel, Outlook …) oder vCard (.vcf, Apple Kontakte): Spalten werden automatisch erkannt und lassen sich neu zuordnen, Daten werden bereinigt (Telefon im Schweizer Format, E-Mail, Zeichensatz), Vorschau mit An-/Abwählen und Umgang mit Doppelten (zusammenführen, behalten, ersetzen)
- **Kunden verwalten:** mehrere per Kästchen auswählen und gemeinsam löschen, Doppelte finden und zusammenführen
- **Wiederkehrende Aufgaben:** täglich, wöchentlich, alle 2 Wochen, monatlich, jährlich oder eigenes Intervall – ab Erledigt oder nach festem Plan
- **Sortierung pro Spalte:** Priorität, Erfassungsdatum, Fälligkeit, Farbe oder manuell
- **Drag & Drop** zwischen und innerhalb der Spalten, dazu ein Menü «Verschieben nach …» auf jeder Karte
- **Kachel «+ Aufgabe hinzufügen»** unter der letzten Karte in Offen, Geplant und Warten – oder Doppelklick auf eine leere Stelle – öffnet eine neue Aufgabe in dieser Spalte
- **Archiv:** per Knopf oder automatisch nach 14 Tagen (einstellbar), durchsuchbar, wiederherstellbar, CSV-Export für Excel
- **Speichern in eine Datei** nach Wahl (Chrome und Edge), dazu Sicherung exportieren und importieren als JSON
- Helles und dunkles Design, Deutsch und Englisch, Tastenkürzel, Hilfe mit Ablauf-Diagramm

![Task Organizer im dunklen Design](screenshots/dark.png)

## Loslegen

**Variante 1 – lokale Datei (empfohlen)**

1. `index.html` herunterladen (auf GitHub: Datei öffnen → «Download raw file»).
2. In Google Chrome oder Microsoft Edge öffnen.
3. Im gelben Hinweis auf «Datei wählen» und dann auf «Neue Datei anlegen» klicken. Einen Ordner wählen, zum Beispiel *Dokumente*.
4. Ab jetzt wird jede Änderung automatisch in diese Datei gespeichert. Nach einem Neustart des Browsers einmal auf «Wieder verbinden» klicken.

**Variante 2 – GitHub Pages**

<https://alpine-marmot.github.io/task-organizer/> öffnen und wie oben eine Datendatei einrichten. Die Seite selbst kommt von GitHub, die Aufgaben bleiben trotzdem auf deinem Computer.

## Bedienung

| Was | Wie |
|---|---|
| Neue Aufgabe | Knopf «Neue Aufgabe», `Alt+N`, Kachel «+ Aufgabe hinzufügen» in einer Spalte oder Doppelklick auf eine leere Stelle |
| Aufgabe bearbeiten | Karte anklicken |
| Aufgabe verschieben | Karte ziehen oder Pfeil-Symbol («Verschieben nach …») |
| Board wechseln | Reiter oben oder `Alt+B` |
| Neues Board | **+** neben den Boards oder Einstellungen › Boards |
| Kundenkarte | blauen Kunden-Chip auf einer Karte oder Knopf «Kunden» anklicken |
| Archivieren | «Archivieren» auf einer erledigten Karte, «Alle archivieren» oder automatisch |
| Kunden importieren | «Importieren» im Kunden-Fenster oder unter Einstellungen › Kunden |

### Boards

Neben *Privat* und *Geschäftlich* legst du beliebig viele Boards an: Klicke auf das **+** neben den Boards, gib einen Namen ein, wähle ein Symbol und entscheide, ob die Aufgaben ein Feld *Kunde* haben. Die Kundenliste ist für alle Boards mit Kundenfeld gemeinsam.

Unter **Einstellungen › Boards** kannst du:
- **Boards ein- und ausschalten** – ein ausgeschaltetes Board verschwindet aus der Kopfzeile, seine Aufgaben bleiben erhalten (praktisch, wenn du nur *Privat* brauchst)
- Boards umbenennen, Symbol und Kundenfeld ändern
- die Reihenfolge mit den Pfeilen ändern
- Boards löschen – nach einer Rückfrage, inklusive Aufgaben und Kategorien

Mindestens ein Board bleibt immer eingeschaltet. `Alt+B` wechselt der Reihe nach durch die eingeschalteten Boards.

![Einstellungen › Boards](screenshots/boards-de.png)

![Neues Board](screenshots/new-board-de.png)

### Wiederkehrende Aufgaben

Unter **Wiederholen** wählst du, wie oft eine Aufgabe anfällt:

- **Ab Erledigt:** Das nächste Datum zählt ab dem Tag, an dem du die Aufgabe erledigst (z. B. Staubsaugen: 7 Tage später).
- **Nach festem Plan:** Das nächste Datum folgt dem Kalender ab dem Fälligkeitsdatum (z. B. Rechnung immer am 1.).

Sobald eine Karte in **Erledigt** landet, wird die nächste in **Geplant** vorbereitet. Sie erscheint erst kurz vor der Fälligkeit – bei täglich am selben Tag, sonst 2 Tage vorher. Vorbereitete Karten stehen unten in «Geplant» unter «kommende Wiederholungen».

![Kundenkarte](screenshots/customer-de.png)

### Kunden importieren

Klicke im Kunden-Fenster oder unter *Einstellungen › Kunden* auf **Importieren** und wähle eine CSV-Datei (Excel, Outlook …) oder eine vCard (.vcf, z. B. aus Apple Kontakte).

1. Ein Ladebalken zeigt die Umwandlung.
2. **Spalten-Zuordnung:** Spalten wie *Firma*, *Vorname*, *Nachname*, *Mobiltelefon* oder *E-Mail* werden automatisch erkannt. Jede Zuordnung lässt sich per Auswahlfeld ändern – die Vorschau passt sich sofort an.
3. **Bereinigung:** Überflüssige Leerzeichen werden entfernt, E-Mail-Adressen klein geschrieben, Schweizer Telefonnummern vereinheitlicht (`079 000 11 22` → `+41 79 000 11 22`), Umlaute aus Excel/Windows korrigiert und doppelte Einträge in der Datei zusammengeführt.
4. **Vorschau:** Alle Kontakte sind ausgewählt – nicht gewünschte abwählen und Felder direkt korrigieren. Bei bereits vorhandenen Kunden wählst du *Zusammenführen* (leere Felder ergänzen, Standard), *Bestehenden behalten* oder *Durch Import ersetzen*.

![Import-Vorschau mit Spalten-Zuordnung](screenshots/import-de.png)

Unter *Einstellungen › Kunden* wählst du mit den Kästchen mehrere Kunden aus und löschst sie gemeinsam. **Doppelte finden** führt Einträge mit gleichem Namen zusammen (Gross-/Kleinschreibung, Akzente und Satzzeichen werden ignoriert) – deren Aufgaben gehen an den Eintrag, der bleibt.

![Kundenliste mit Mehrfachauswahl](screenshots/customers-de.png)

### Tastenkürzel

| Kürzel | Aktion |
|---|---|
| `Alt+N` | Neue Aufgabe |
| `Ctrl+Enter` | Speichern (im Formular) |
| `Alt+1` / `2` / `3` | Priorität (im Formular) |
| `Alt+B` | Board wechseln |
| `Ctrl+F` | Suche |
| `Esc` | Fenster oder Menü schliessen |

Auf dem Mac: `Alt` = Wahltaste (⌥), `Ctrl` kann auch Cmd (⌘) sein.

## Browser

| Browser | Speichern in Datei | Hinweis |
|---|---|---|
| Google Chrome | ✓ | empfohlen |
| Microsoft Edge | ✓ | empfohlen |
| Safari | – | Daten nur im Browser; regelmässig eine Sicherung exportieren |
| Firefox | – | Daten nur im Browser; regelmässig eine Sicherung exportieren |

Das Speichern in eine Datei nutzt die *File System Access API*, die nur Chromium-Browser unterstützen. Aus Sicherheitsgründen zeigt der Browser nur den Dateinamen, nicht den Ordner.

**Safari:** Safari kann Website-Daten von Seiten löschen, die 7 Tage nicht benutzt wurden. Wer Safari verwendet, sollte regelmässig eine Sicherung exportieren.

## Daten und Datenschutz

| | |
|---|---|
| **Wo die Daten liegen** | Nur in der gewählten Datendatei und im Browser-Speicher (localStorage / IndexedDB) auf deinem Computer |
| **Internet** | Die App stellt **keine** Verbindung ins Internet her – importierte Dateien werden nur in deinem Browser verarbeitet: kein Tracking, keine Cookies, keine Schriften oder Bibliotheken von aussen |
| **Autor** | sieht nichts – es gibt keinen Server |
| **GitHub Pages** | Beim Öffnen der Online-Version erhält GitHub die üblichen Zugriffsdaten (z. B. IP-Adresse) wie bei jeder Website. Deine Aufgaben werden nicht übertragen |

**Kundendaten sind Personendaten.** Namen, Ansprechpersonen, Telefonnummern und E-Mail-Adressen fallen unter das Schweizer Datenschutzgesetz (DSG) bzw. die DSGVO. Nur erfassen, was du brauchst, aktuell halten und löschen, wenn es nicht mehr nötig ist.

**Cloud-Ordner:** Liegt die Datendatei in einem Ordner, der mit einer Cloud synchronisiert wird (iCloud Drive, OneDrive, Google Drive, Dropbox …), werden alle Daten dorthin kopiert, und es gelten die Bedingungen dieses Dienstes. Die App kann das nicht erkennen – bitte selbst prüfen.

Dies ist eine technische Beschreibung, keine Rechtsberatung.

## Lizenz

[MIT](LICENSE) © 2026 alpine-marmot

Ebenfalls von alpine-marmot: [Linkboard](https://github.com/alpine-marmot/linkboard) – eine Browser-Startseite in einer Datei.
