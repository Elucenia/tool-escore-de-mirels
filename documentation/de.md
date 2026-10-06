<!-- ELUCENIA technical documentation · escore-de-mirels · de · no clinical/professional/rights approval -->

# Mirels-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-de-mirels)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Lokalisation der Läsion

`local`

- `1` — Obere Extremität
- `2` — Untere Extremität
- `3` — Peritrochantär

### Schmerz

`dor`

- `1` — Leicht
- `2` — Mäßig
- `3` — Funktionell (bei Belastung)

### Röntgenbefund

`lesao`

- `1` — Blastisch
- `2` — Gemischt
- `3` — Lytisch

### Größe (Anteil des Knochendurchmessers)

`tamanho`

- `1` — Weniger als 1/3
- `2` — 1/3 bis 2/3
- `3` — Mehr als 2/3

## Fassung der Methode

Mirels 1989: Ort/Schmerz/Läsion/Größe 1–3, Gesamt 4–12

## Dokumentierte Formel

Vier Items, je 1 bis 3: Ort (obere Extremität 1, untere 2, pertrochantär 3), Schmerz (leicht 1, mäßig 2, funktionell 3), Läsion (blastisch 1, gemischt 2, lytisch 3), Größe bezogen auf Knochendurchmesser (\<1/3: 1; 1/3 bis 2/3: 2; \>2/3: 3). Gesamt 4 bis 12.

## Grenzen und Population

Mirels von 1989 wurde bei ohne prophylaktische Fixierung bestrahlten metastatischen Läsionen langer Knochen mit Frakturbeurteilung nach sechs Monaten entwickelt. Das Originalabstract und spätere interpretierende Versionen verwenden nicht notwendigerweise dieselbe Entscheidungsschwelle; Ausgabe und entsprechendes Vorgehen müssen ausdrücklich benannt sein. Die Summe allein entscheidet nicht zwischen Strahlentherapie und Operation.

## Referenzen

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Bis zu 7 Punkte: geringes Frakturrisiko (etwa 4 %)

Strahlentherapie und Beobachtung.


### 2

8 Punkte: intermediäres Risiko (etwa 15 %)

Klinische Beurteilung: prophylaktische Stabilisierung erwägen.


### 3

9 Punkte oder mehr: hohes Frakturrisiko (33 % oder mehr)

Prophylaktische Fixierung vor der Strahlentherapie.


### 4

9 Punkte oder mehr: hohes Frakturrisiko (33 % oder mehr)

Prophylaktische Fixierung vor der Strahlentherapie.

