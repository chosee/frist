# Schweizer Fristenrechner

Berechne juristische Fristen nach der Schweizerischen Zivilprozessordnung (ZPO).

**[frist.ch](https://frist.ch)**

## Funktionen

- Berechnung von Tages- und Monatsfristen
- Berücksichtigung von Wochenenden und Feiertagen
- Gerichtsferien (Art. 145 ZPO)
- Basierend auf aktueller Bundesgerichts-Rechtsprechung

## Rechtliche Grundlagen

Der Rechner implementiert die Artikel 142-145 ZPO:

| Artikel | Inhalt |
|---------|--------|
| Art. 142 | Fristbeginn und -berechnung |
| Art. 143 | Fristeinhaltung |
| Art. 144 | Fristerstreckung |
| Art. 145 | Gerichtsferien |

### Gerichtsferien

- **Ostern**: 7 Tage vor bis 7 Tage nach Ostersonntag
- **Sommer**: 15. Juli – 15. August
- **Winter**: 18. Dezember – 2. Januar

## Technologie

Statische Single-Page-App ohne Backend. Alle Berechnungen erfolgen clientseitig.

## Lizenz

MIT
