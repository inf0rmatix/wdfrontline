# Farben, Schriften und Maße

## Farben

Die Grundfarben wurden am 26. September 2026 aus der Website geprüft.

| Rolle | Wert | Verwendung |
| --- | --- | --- |
| Hintergrund | `#0a0b0d` | Gesamte Grafik |
| Fläche | `#121417` | Karte und Vorschau |
| Hervorgehobene Fläche | `#191c21` | Kernaussage und abgesetzte Bereiche |
| Primärer Text | `#ececf0` | Überschrift und Aussagen |
| Sekundärer Text | `#9ca3af` | Erläuterungen und Quellenzeile |
| Struktur | `#262a30` | Raster und Trennlinien |
| Signal | `#f59e0b` | Hot Zone, ×2-Bonus, wichtigste Hervorhebung |
| Zonengrenze | `#828a99` | Gestrichelte Control-Zone-Grenze |

Amber bezeichnet in dieser Grafik die Hot Zone und ihren Bonus, keine Fraktion. Primärer Text erklärt Regeln und Zonen. Labels, Konturen und Positionen müssen die Bedeutung auch ohne Farbe verständlich machen.

## Schriften

| Rolle | Familie | Verwendung |
| --- | --- | --- |
| Display | Barlow Condensed, 700 | Guide-Titel, ×2, kurze Hauptaussagen |
| Lesetext | Geist | Erklärungen, Legende, Kernaussage, Bedienelemente |
| Technische Labels | Geist Mono | Zonenlabels, Abschnittsnummern und Quellenzeile |

Alle drei Schriftdateien sind als WOFF2 eingebettet. Die Datei verwendet die lateinischen Subsets der Website, einschließlich deutscher Umlaute. Weitere Schriftsysteme sind nicht geprüft. Die Lizenzen liegen unter `licenses/` und sind auch im SVG enthalten, damit der SVG-Export die Hinweise mitnimmt.

## Maße und Hierarchie

Die folgenden Werte beziehen sich auf die SVG-Zeichenfläche, nicht auf eine bestimmte Bildschirmgröße.

| Merkmal | Aktueller Wert |
| --- | --- |
| Zeichenfläche | 1440 × 960, Verhältnis 3:2 |
| PNG-Standardexport | 2880 × 1920, Faktor 2 |
| Alternativer PNG-Export | 1440 × 960, Faktor 1 |
| Außenrand der Grafik | 56 |
| Haupttitel | 88 |
| Unterzeile | 27 |
| Abschnittslabels | 19 |
| Legende | 22 |
| Kernaussage | 25 |

Textgrößen richten sich nach der Aufgabe und dem Platz. Längere Aussagen werden gekürzt oder umgebrochen; Texte dürfen nicht durch die Zeichenflächenkante abgeschnitten werden.

## Anzeige und Zugänglichkeit

Die Vorschau wird proportional verkleinert. Bei schmalen Bildschirmen kann sie über **Vorschau vergrößern** bewusst horizontal gescrollt werden. Das Exportformat bleibt unverändert. Eine eigene Hochkantvariante gibt es bisher nicht.

Das SVG hat einen Titel und eine Beschreibung. Formulare und Buttons besitzen Beschriftungen und sichtbare Fokusmarkierungen; der Exportstatus wird angekündigt. Beim Einbinden des PNGs einen passenden Alternativtext und eine Erklärung im Guide ergänzen. Das Bild enthält Text und ersetzt keinen zugänglichen Guide-Absatz.
