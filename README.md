# Algorithmen auf Sequenzen
Alle Projekte im Modul 'Algorithmen auf Seuqenzen', B.Sc. Bioinformatik, THM

## Projekt 1: Exaktes Patternmatching
- Implementierung des Simple Search und Horspool Algorithmus, mit der Ausgabe der Anzahl der Vergleiche.
- Berechnung und Verwendung der Anzahl der Vergleiche zur Laufzeitanalyse in spezifischen Beispielen.

In diesem Projekt habe ich mich mit dem exakten Pattern-Matching beschäftigt und die Implementierung von zwei verschiedenen Algorithmen durchgeführt: den Simple Search und den Horspool Algorithmus. Ein wichtiger Aspekt dieses Projekts war die Berechnung und Ausgabe der Anzahl der Vergleiche, die während des Suchvorgangs durchgeführt wurden. Diese Anzahl der Vergleiche dient als Maß für die Laufzeit des Algorithmus und ermöglicht es, die Effizienz und Geschwindigkeit der Suchoperationen zu bewerten.

Ein weiterer Schwerpunkt lag auf dem Vergleichen und Schätzen der Laufzeiten in spezifischen Beispielen. Dies half dabei, die Performance der beiden Algorithmen unter verschiedenen Bedingungen zu analysieren und zu verstehen. Dieses Projekt trug dazu bei, ein besseres Verständnis für exaktes Pattern-Matching zu entwickeln und die Fähigkeiten im Bereich Algorithmusentwicklung und -analyse zu vertiefen.

 ## Projekt 2: Maximale Repeats
- Implemetierung eines Algorithmus zur Detektion der STEMs sowie der sekundären Struktur der RNAs
- Schätzen die Laufzeit des Algorithmus und vergleich mit der tatsächlichen Laufzeit durch das Beispiel mit der menschenlichen 12S rRNA

In RNA gibt es zahlreiche Substrings, die sich als komplementäre Paare zueinander verhalten. Diese komplementären Substrings werden als STEMs bezeichnet und sind maßgeblich für die Bildung der sekundären Struktur der RNA verantwortlich. Im ersten Schritt wurde eine Suchmethode mithilfe von Suffix-Arrays entwickelt, um STEMs in RNA-Sequenzen aufzuspüren. Die Methode wurde erfolgreich in einer kleiner RNA durchgeführt, wobei die zahlreiche potenzielle STEMs gefunden wurden. Die Methode wurde weiterentwicklt, um die überlappende STEMs auszusortieren sowie die besten RNA-Sekundärstruktur aufzubauen. Das Ergebnis war aber nicht ganz korrekt, wobei manche Stelle nicht komplementär gebunden wurden.

Im nächsten Schritt wurde die Pseudocode der Detektion erstellt und die geschätzte Laufzeit wurden berechnet. Das Messen der Laufzeit des Algorithmus in der menschenlichen rRNA war unvollständig geschafft.
