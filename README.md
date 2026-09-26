# Wardogs Frontline · Guide-Grafiken

HTML-Vorlagen für Grafiken in den Guides von [wdfrontline.com](https://wdfrontline.com). Die Grafiken erklären Spielmechaniken und Taktik. Guider können sie bearbeiten, als Bild speichern und in einen Guide einbinden.

## Direkt loslegen

1. [Hot-Zone-Vorlage](templates/hot-zone.html) herunterladen und im Browser öffnen.
2. Über **Texte bearbeiten** Überschrift, Unterzeile und Kernaussage anpassen.
3. Auflösung wählen und **PNG speichern** anklicken.
4. Die Grafik im Guide einbinden und die Aussage auch im Begleittext erklären.

Die Datei funktioniert offline. Schriften, Gestaltung und Diagramm sind eingebettet; ein Build ist nicht nötig. Änderungen im Texteditor werden direkt in der HTML-Datei gespeichert. Änderungen über das Formular gelten für die aktuelle Browseransicht und den Bildexport; sie werden nicht in die HTML-Datei zurückgeschrieben.

![Die Hot Zone: doppeltes Spielergewicht, doppelte XP und doppeltes Geld](exports/hot-zone.png)

## Ablage

| Ordner | Inhalt |
| --- | --- |
| `guides/` | Überarbeitete Guides als Markdown mit eingebundener Grafik |
| `templates/` | Bearbeitbare HTML-Vorlagen; maßgeblich für Darstellung und Export |
| `exports/` | Fertige PNGs für die Guides |
| `docs/` | Kontext, Sprache, Bearbeitung und Prüfschritte |
| `docs/design-system/` | Farben, Schriften, Aufbau und Diagrammregeln |
| `licenses/` | Lizenzen der eingebetteten Schriften |

Vorlage und Bild tragen denselben Themennamen. Für den aktuellen Guide sind das `hot-zone.html` und `hot-zone.png`.

## Guide

[Die Hot Zone](guides/hot-zone.md) – überarbeiteter Text mit Bonus, Siegpunktwertung und situativer Taktik.

## Dokumentation

- [Kontext und fachliche Grundlagen](docs/context.md)
- [Design-System](docs/design-system/README.md)
- [Sprache in Guides](docs/language.md)
- [Bearbeiten, exportieren und prüfen](docs/workflow.md)
- [Quellen und Schriftlizenzen](docs/sources.md)

Der Stand ist ein erster Entwurf mit einem Guide als Beispiel. Weitere Diagrammformen werden ergänzt, sobald ein konkreter Guide sie braucht.
