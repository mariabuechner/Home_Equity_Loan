# Fallstudie: Kreditausfälle mit dem HMEQ-Datensatz vorhersagen

## Ausgangslage

Ein Finanzinstitut möchte besser einschätzen, bei welchen Immobilienkrediten ein erhöhtes Ausfallrisiko besteht. Dafür steht der **Home Equity Loan Dataset (HMEQ)** mit Informationen zu rund 6.000 Krediten zur Verfügung.

Die Zielvariable `BAD` zeigt, ob ein Kredit ausgefallen ist:

- `0`: Der Kredit wurde zurückgezahlt.
- `1`: Der Kredit ist ausgefallen.

Der Datensatz enthält reale Herausforderungen wie fehlende Werte, numerische und kategoriale Merkmale sowie unterschiedlich häufig vertretene Zielklassen.

## Aufgabe

Entwickelt mithilfe eines KI-Assistenten einen nachvollziehbaren Ansatz, um Kreditausfälle möglichst zuverlässig vorherzusagen. Untersucht zunächst den Datensatz und entscheidet anschließend selbst, welche Schritte der Datenaufbereitung, welche Modelle und welche Bewertungsverfahren für das Ziel geeignet sind.

Eure Lösung soll nicht nur ein Vorhersageergebnis liefern, sondern auch begründen, warum ihr euch für euren Ansatz entschieden habt. Vergleicht sinnvolle Alternativen und prüft kritisch, ob das Ergebnis für die Beurteilung von Kreditausfällen tatsächlich aussagekräftig ist.

## Leitfragen

Die folgenden Fragen dienen als Orientierung. Sie geben bewusst keinen festen Lösungsweg vor:

1. Welche Eigenschaften und Auffälligkeiten hat der Datensatz?
2. Welche Datenqualitätsprobleme könnten die Analyse oder die Vorhersage beeinflussen?
3. Wie lässt sich vermeiden, dass Informationen aus den Testdaten unbeabsichtigt in das Training einfließen?
4. Welche Modellansätze eignen sich für diese Fragestellung, und wie unterscheiden sie sich?
5. Anhand welcher Kennzahlen sollte die Modellqualität beurteilt werden? Welche Fehlerart ist im geschäftlichen Kontext besonders relevant?
6. Wie stabil und nachvollziehbar sind die Ergebnisse?
7. Welche Grenzen, Risiken oder ethischen Aspekte hätte der Einsatz des Modells in der Praxis?

## Erwartete Ergebnisse

Gebt Folgendes ab:

- ein ausführbares Notebook oder Skript mit eurem vollständigen Arbeitsablauf,
- eine kurze Beschreibung der Daten und der wichtigsten Erkenntnisse aus der explorativen Analyse,
- eine begründete Dokumentation eurer Datenaufbereitung und Modellauswahl,
- einen nachvollziehbaren Vergleich der untersuchten Ansätze,
- eine geeignete Bewertung des finalen Modells auf bisher ungesehenen Daten,
- eine Interpretation der Ergebnisse aus fachlicher Sicht,
- eine kurze Reflexion darüber, wie ihr die KI eingesetzt, ihre Vorschläge überprüft und gegebenenfalls verbessert habt.

## Einsatz von KI

Ihr dürft einen KI-Assistenten bei allen Arbeitsschritten verwenden, beispielsweise zum Strukturieren des Vorgehens, Erklären von Methoden, Erstellen oder Überarbeiten von Code und Interpretieren von Ergebnissen. Ihr bleibt jedoch für alle Entscheidungen und Aussagen verantwortlich.

Dokumentiert deshalb die wichtigsten Prompts und beschreibt mindestens ein Beispiel, bei dem ihr einen Vorschlag der KI kritisch geprüft, korrigiert oder bewusst verworfen habt. Code und Ergebnisse müssen von euch verstanden und reproduzierbar sein.

## Datensatz

- Datei in diesem Repository: `hmeq.xls`
- Ursprüngliche Quelle: [Kaggle – HMEQ Data](https://www.kaggle.com/datasets/ajay1735/hmeq-data)

> **Hinweis:** Die Dateiendung entspricht nicht zwingend dem tatsächlichen Dateiformat. Prüft beim Einlesen selbst, wie die Datei aufgebaut ist.
