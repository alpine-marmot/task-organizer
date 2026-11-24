# Änderungen

Deutsch · [English](CHANGELOG.md)

Alle wichtigen Änderungen am Task Organizer. Die Versionen folgen [Semantic Versioning](https://semver.org/lang/de/); 0.x-Versionen sind Beta.

## 0.4.0 – 24.11.2026

### Neu
- Mehrere Boards: neben Privat und Geschäftlich eigene Boards über das **+** in der Kopfzeile anlegen – mit Name, Symbol und Kundenfeld
- Einstellungen › Boards: Boards ein-/ausschalten (Aufgaben bleiben erhalten), umbenennen, Symbol und Kundenfeld ändern, sortieren, löschen (mit Rückfrage)

### Geändert
- Kategorien, Archiv und `Alt+B` berücksichtigen alle Boards; Kundenfeld, Kundenfilter und Knopf «Kunden» erscheinen nur in Boards mit Kundenfeld
- Bestehende Daten werden automatisch übernommen (Privat ohne, Geschäftlich mit Kundenfeld)

## 0.3.1 – 24.11.2026

### Neu
- Kachel «+ Aufgabe hinzufügen» unter der letzten Karte in Offen, Geplant und Warten (auch in leeren Spalten); ein Klick öffnet «Neue Aufgabe» mit dieser Spalte vorausgewählt

## 0.3.0 – 19.11.2026

### Neu
- Kunden-Import mit Vorschau: jeden Kontakt an- oder abwählen (alle vorausgewählt) und Felder direkt korrigieren
- Automatische Spaltenerkennung bei CSV-Dateien (z. B. Firma, Vorname, Nachname, Mobile) mit änderbarer Zuordnung; Ladebalken während der Umwandlung
- Bereinigung beim Import: Leerzeichen, E-Mail-Adressen, Telefonnummern im Schweizer Format (z. B. 079 539 95 32 → +41 79 539 95 32), Zeichensatz von Excel/Windows, doppelte Einträge in der Datei
- Bereits vorhandene Kunden: zusammenführen (Standard), bestehenden behalten oder ersetzen – pro Kontakt
- vCard-Import (.vcf), z. B. aus Apple Kontakte oder Outlook
- Einstellungen › Kunden: Kästchen für Mehrfachauswahl und «Ausgewählte löschen», «Doppelte finden» mit Zusammenführen
- Kunden-Fenster: Knopf «Importieren» neben «Kundendaten bearbeiten»

### Geändert
- Telefonnummern werden in den Kundenlisten vollständig angezeigt
- Kurzmeldungen erscheinen jetzt auch vor geöffneten Fenstern

## 0.2.2 – 19.11.2026

### Geändert
- Veröffentlichung auf GitHub: Autor «alpine-marmot», Fusszeile mit Logo und Links zu Repository und Profil

## 0.2.1 – 18.11.2026

### Neu
- Doppelklick auf eine leere Stelle in den Spalten Offen, Geplant oder Warten öffnet «Neue Aufgabe» mit dieser Spalte vorausgewählt

## 0.2.0 – 14.11.2026

### Neu
- Wiederkehrende Aufgaben: täglich, wöchentlich, alle 2 Wochen, monatlich, jährlich oder eigenes Intervall
- Nächstes Datum pro Aufgabe «ab Erledigt» oder «nach festem Plan»; die neue Karte kommt in «Geplant» und erscheint kurz vor der Fälligkeit
- «Kommende Wiederholungen» unten in der Spalte «Geplant»
- Kunden-Ansicht: Kundenkarte mit Kontaktdaten zum Anklicken, offenen und erledigten Aufgaben, «Neue Aufgabe für …»
- Neues Kundenfeld «Ansprechperson» (Erfassung, Einstellungen, CSV-Import und -Export)

### Geändert
- Sortier-Menü in den Spalten etwas breiter

## 0.1.0 – 14.11.2026

### Neu
- Erste Beta: Bereiche Privat und Geschäftlich, vier Spalten (Offen, Geplant, Warten, Erledigt)
- Aufgaben mit Priorität 1–3, Kategorien mit Farben, Fälligkeitsdatum und Notiz; im geschäftlichen Bereich Kunden mit Telefon und E-Mail
- Kategorien und Kunden entstehen beim ersten Eintippen und werden danach vorgeschlagen
- Sortierung pro Spalte, Drag & Drop, Menü «Verschieben nach …»
- Archiv (per Knopf oder automatisch nach 14 Tagen), Suche, Wiederherstellen, CSV-Export
- Speichern in eine Datei (Chrome/Edge), Zwischenspeicher im Browser, Sicherung exportieren und importieren
- Einstellungen mit Reitern Allgemein, Kategorien und Kunden; Hilfe mit Ablauf-Diagramm und Datenschutz-Hinweisen
- Hell/Dunkel, Deutsch/Englisch, Tastenkürzel
