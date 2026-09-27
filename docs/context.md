# Kontext

## Ziel

Ein Guider der Wardogs-Frontline-Community möchte die Guides mit verständlichen Grafiken verbessern. Die Grafiken werden in HTML erstellt und als Bilder in die bestehende Website eingebunden. Die Website selbst ist kein Bestandteil dieses Repositorys.

## Anforderungen

- Farben an wdfrontline.com orientieren.
- Originalschriften verwenden oder eine bewusst kontrastierende Schrift wählen.
- Spielmechaniken durch räumliche Beziehungen, Vergleiche oder Abläufe erklären.
- Natürliche Sprache verwenden, die zum Gaming-Umfeld passt.
- Bearbeitung und Bildexport ohne Build oder externe Dienste ermöglichen.

Die erste Vorlage verwendet die Originalschriften und eingebettete Schriftdateien. Sie benötigt keine Netzwerkverbindung.

## Beispiel: Die Hot Zone

Die [Hot Zone](https://wdfrontline.com/guides/hot-zone) liegt innerhalb der Control Zone. Die Grafik verbindet zwei Aussagen:

1. In der Hot Zone gilt der ×2-Bonus für die Spielerwertung bei der Siegpunktberechnung, und für Geld.
2. Siegpunkte erhält das Team mit der größten gewerteten Spielerzahl in der gesamten Control Zone. Der Hot-Zone-Bonus wird dabei berücksichtigt; die Hot Zone muss nicht dauerhaft besetzt sein.

Die Hot Zone bewegt sich. Die passende Taktik hängt von der Situation ab: Gegner können beispielsweise in der Hot Zone gegeneinander kämpfen, bevor das eigene Team sie von hinten angreift. Die Grafik gibt deshalb keine feste Squad-Aufteilung vor. Diese Einordnung stammt aus dem Guider-Feedback.

Die Website bestätigt doppelte Spielerwertung und doppeltes Geld. Am 27. September 2026 hat der Guider klargestellt, dass die Hot Zone keinen XP-Bonus gibt. Diese Korrektur ersetzt die frühere XP-Angabe.

Die doppelte Spielerwertung bedeutet nicht, dass die Fraktion automatisch doppelt so viele Siegpunkte erhält. Der Bonus verändert die Spielerzahl, die für die Mehrheitsberechnung berücksichtigt wird.

Die Skizze zeigt keine echte Karte. Zonengeometrie und Position der Hot Zone dienen nur der Erklärung. Die Skizze zeigt keine taktischen Spielerpositionen.

## Gestaltungsentscheidungen

| Entscheidung | Grund |
| --- | --- |
| Anthrazit und Amber | Schließt an die Website an; der Bonus fällt sofort auf |
| Barlow Condensed, Geist, Geist Mono | Entspricht der geprüften Typografie der Website |
| ×2 mit zwei verbundenen Effekten | Zeigt den gemeinsamen Bonus statt einer einzelnen Zahlenrechnung |
| Zonenskizze links | Zeigt die Hot Zone als beweglichen Teil der Control Zone |
| Kernaussage unten | Erklärt, welches Team Siegpunkte bekommt |
| SVG innerhalb einer HTML-Datei | Scharfer Export und eingebettete Schriften ohne zusätzliche Ressourcen |

Der ursprüngliche Vergleich „2 Spieler zählen wie 4“ wurde nach Feedback ersetzt. Maßgeblich ist jetzt das übergeordnete Konzept **„Der ×2-Bonus“**, konkret auf Spielerwertung und Geld bezogen.

## Umfang und Verantwortung

Das Design-System gilt zunächst für diese Guide-Grafiken, nicht für die gesamte Website. Es ist experimentell: Eine Vorlage ist vorhanden, weitere Anwendungen sind noch nicht erprobt.

Guider prüfen die Spielmechaniken und den Text vor der Veröffentlichung. Änderungen an Markenfarben und Schriftwahl werden mit den für die Website zuständigen Community-Mitgliedern abgestimmt. Konkrete Personen sind noch nicht festgelegt.
