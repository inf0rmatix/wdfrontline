# Projektregeln

Dieses Repository enthält deutschsprachige Wardogs-Guides und HTML-Vorlagen für deren Bildgrafiken. Die Website selbst liegt außerhalb dieses Repositorys.

## Kontext zu Beginn lesen

- [README](README.md): Ablage und Einstieg.
- [Projektkontext](docs/context.md): Anforderungen, fachliche Ergänzungen und bisherige Entscheidungen.
- [Sprache](docs/language.md): Begriffe und Ton der Guides.
- Bei Grafiken zusätzlich [Design-System](docs/design-system/README.md), [Grundlagen](docs/design-system/foundations.md), [Diagrammregeln](docs/design-system/patterns.md) und [Workflow](docs/workflow.md) lesen.
- Vor einer Änderung den betroffenen Guide und die zugehörige HTML-Vorlage prüfen. Quellen stehen in [Quellen](docs/sources.md).

## Sprache und Inhalt

- Klar und natürlich schreiben, wie ein erfahrener Spieler einem anderen Spieler etwas erklärt. Für narrative Texte humanizer verwenden, sofern verfügbar; für Bedienelemente ux-writing.
- Begriffe wie Squad, FOB, Loadout, Respawn und XP beibehalten, wo sie passen. Einzelne Spieler mit „du“, gemeinsame Squad-Handlungen mit „ihr“ ansprechen.
- Für die Siegpunktberechnung „Spielerwertung“ verwenden oder direkt erklären, dass ein Spieler doppelt zählt. „Spielergewicht“ vermeiden: Wardogs hat ein eigenes Gewichtssystem für Ausrüstung.
- Konkrete Handlungen und Folgen beschreiben. Sperrige Wortschöpfungen wie „Nachrückweg“ durch Alltagssprache ersetzen, etwa „Weg zurück in die Zone“.
- Spielregeln, situative Empfehlungen und schematische Beispiele auseinanderhalten. Keine pauschale Squad-Aufteilung als allgemeine Taktik vorgeben.
- Aussagen aus Website, Guider-Bestätigung und eigener Prüfung getrennt dokumentieren. Fehlende Fakten nicht erfinden. Bei neuen oder geänderten Spielregeln passende aktuelle Quellen prüfen oder fachliche Bestätigung einholen.

## Fachliche Grundlage: Hot Zone

Die Hot Zone bewegt sich innerhalb der Control Zone. Sie verdoppelt Spielerwertung, XP und Geld. Siegpunkte bekommt das Team mit der größten gewerteten Spielerzahl in der gesamten Control Zone; Spieler in der Hot Zone zählen dabei doppelt. Das bedeutet keine automatisch verdoppelten Siegpunkte.

Die Hot Zone muss nicht dauerhaft besetzt sein. Ob man sie besetzt, Gegner abfängt oder einen anderen Teil der Control Zone nutzt, hängt von der Situation ab. Die Herkunft dieser Aussagen und der XP-Ergänzung ist in `docs/context.md` festgehalten.

## Gestaltung

- Die dokumentierten Website-Farben und Schriftrollen verwenden: Anthrazit und Amber; Barlow Condensed, Geist und Geist Mono.
- Beziehungen sichtbar machen. Für Zonen eine beschriftete Zonenskizze, für einen gemeinsamen Bonus verbundene Effekte verwenden. Die Diagrammform nach der Aussage wählen.
- Schematische Geometrie als solche kennzeichnen. Keine erfundenen Spielkarten, Abstände oder Spielerpositionen als Spielvorgabe darstellen.
- Vorlagen als einzelne offline-fähige HTML-Dateien mit eingebettetem CSS, SVG und Schriften erhalten. Ohne konkreten Bedarf kein Framework oder Build-System ergänzen.
- CSS und SVG enthalten getrennte Farbdefinitionen. Änderungen in beiden Bereichen abgleichen; die HTML-Vorlage ist für Darstellung und Export maßgeblich.
- Eingebettete Schriftlizenzen und die Dateien unter `licenses/` erhalten.

## Ablage und Änderungen

- `guides/<thema>.md`: Guide-Text mit passendem Bildverweis und Alternativtext.
- `templates/<thema>.html`: Bearbeitbare Vorlage.
- `exports/<thema>.png`: Fertiger Bildexport.
- `docs/`: Kontext, Gestaltung, Sprache, Quellen und Workflow.
- Für neue Themen denselben Themennamen verwenden und Guide-Link, Exportnamen, Quellenstand, SVG-Titel und SVG-Beschreibung anpassen.
- Formular-Standardwerte und SVG-Texte zusammen aktualisieren. Formularänderungen gelten nur für die aktuelle Ansicht und den Export; sie speichern die HTML-Datei nicht zurück.
- Bei Änderungen Guide, Grafik und Dokumentation konsistent halten. Nach visuellen oder inhaltlichen Grafikänderungen das PNG neu exportieren; Zwischenstände und Prüfserver gehören nicht ins Repository.

## Prüfung und Lieferung

- HTML im Browser rendern und das gespeicherte PNG visuell prüfen: Schriften, Umlaute, Ausrichtung, Textabstände, Überlappungen und abgeschnittene Inhalte.
- Bei Layout- oder Bedienänderungen Desktop und eine schmale Ansicht um 375 Pixel prüfen. Kleine Vorschauen dürfen über die vorgesehene Vergrößerung bewusst gescrollt werden.
- PNG-Export, relevante Bedienelemente und relative Dokumentlinks prüfen. Standardexport: 2880 × 1920; Zeichenfläche: 1440 × 960.
- Nur tatsächlich durchgeführte Prüfungen als erfolgreich melden. Verbleibende Einschränkungen benennen.
- Bestehende fremde Änderungen erhalten. Commit und Push nur auf ausdrücklichen Auftrag ausführen; Commit-Nachrichten als Conventional Commits schreiben.
