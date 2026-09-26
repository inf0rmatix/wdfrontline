# Design-System für Guide-Grafiken

Stand: 26. September 2026 · Status: experimentell · Beispiel: Hot Zone.

Dieses System hält die Grafiken visuell zusammen und hilft beim Aufbau neuer Themen. Es enthält nur Muster, die in der vorhandenen Vorlage umgesetzt sind. Neue Themen dürfen eine andere Diagrammform brauchen.

## Grundlagen

[Farben, Schriften und Maße](foundations.md) beschreiben die Gestaltung. [Diagramme und Aufbau](patterns.md) beschreiben die Verwendung.

Die HTML-Datei ist für Darstellung und Export maßgeblich. Farben liegen in den CSS-Variablen der Bedienoberfläche und in den SVG-Stilen beziehungsweise SVG-Attributen. Das SVG ist bewusst eigenständig, damit der Export offline funktioniert. Änderungen müssen an beiden Stellen geprüft werden; es gibt noch keinen gemeinsamen Generator für Design-Tokens.

## Zusammensetzung

| Ebene | Aktueller Bestand |
| --- | --- |
| Grundlagen | Farben, Schriftrollen, Exportformat |
| Atome | Textstile, Linien, Zonenlabels |
| Moleküle | Beschrifteter Zonenbereich, Verbindung zwischen Bonus und Effekt |
| Organismen | Zonenskizze, ×2-Bonusdiagramm |
| Template | Kopfbereich, Erklärfläche, Kernaussage, Quellenzeile |
| Beispiel | Hot-Zone-Grafik mit konkreten Inhalten |

Die Ebenen beschreiben die Zusammensetzung; sie benötigen keine eigenen Komponentenpakete.

## Änderungen

Für ein neues Thema zuerst vorhandene Farben und Schriftrollen verwenden. Diagramme werden übernommen, wenn sie dieselbe Beziehung erklären. Bei einem anderen Zusammenhang wird eine passende neue Form gewählt.

Eine Änderung ist fertig, wenn HTML, Dokumentation und Bildexport zusammenpassen. Inhaltliche Änderungen brauchen eine Quelle oder die Bestätigung eines Guiders. Änderungen an räumlicher Anordnung, Farbrollen oder Beschriftungen werden am gerenderten Bild geprüft.

Vorlagen bleiben experimentell, bis sie in weiteren Guides verwendet wurden und sich Bearbeitung, Verständlichkeit und Export bewährt haben. Ein formales Versionsschema wird erst benötigt, wenn mehrere Vorlagen von einer gemeinsamen Implementierung abhängen.
