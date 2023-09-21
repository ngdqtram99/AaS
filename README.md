# Algorithmen auf Sequenzen
Alle Projekte im Modul 'Algorithmen auf Seuqenzen', B.Sc. Bioinformatik, THM

## Projekt 1: Exaktes Patternmatching
- Implementierung des Simple Search und Horspool Algorithmus, mit der Ausgabe der Anzahl der Vergleiche.
- Berechnung und Verwendung der Anzahl der Vergleiche zur Laufzeitanalyse in spezifischen Beispielen.

Das Projekt war mit dem exakten Pattern-Matching beschäftigt, wobei der Simple Search und Horspool-Methode implemetiert wurden. Ein wichtiger Aspekt dieses Projekts war die Berechnung und Ausgabe der Anzahl der Vergleiche, die während des Suchvorgangs durchgeführt wurden. Diese Anzahl der Vergleiche dient als Maß für die Laufzeit des Algorithmus und ermöglicht es, die Effizienz und Geschwindigkeit der Suchoperationen zu bewerten.

Ein weiterer Schwerpunkt lag auf dem Vergleichen und Schätzen der Laufzeiten in spezifischen Beispielen. Dies half dabei, die Performance der beiden Algorithmen unter verschiedenen Bedingungen zu analysieren und zu verstehen. Dieses Projekt trug dazu bei, ein besseres Verständnis für exaktes Pattern-Matching zu entwickeln und die Fähigkeiten im Bereich Algorithmusentwicklung und -analyse zu vertiefen.

 ## Projekt 2: Detektion der Sekundärstruktur der RNA
- Implemetieren eines Algorithmus zur Detektion der STEMs sowie der sekundären Struktur der RNAs
- Schätzen die Laufzeit des Algorithmus und vergleich mit der tatsächlichen Laufzeit durch das Beispiel mit der menschenlichen 12S rRNA

In RNA gibt es zahlreiche Substrings, die sich als komplementäre Paare zueinander verhalten. Diese komplementären Substrings werden als STEMs bezeichnet und sind maßgeblich für die Bildung der sekundären Struktur der RNA verantwortlich. Im ersten Schritt wurde eine Suchmethode mithilfe von Suffix-Arrays entwickelt, um STEMs in RNA-Sequenzen aufzuspüren. Die Methode wurde erfolgreich in einer kleiner RNA durchgeführt, wobei die zahlreiche potenzielle STEMs gefunden wurden. Die Methode wurde weiterentwicklt, um die überlappende STEMs auszusortieren sowie die besten RNA-Sekundärstruktur aufzubauen. Das Ergebnis war aber nicht ganz korrekt, wobei manche Stelle nicht komplementär gebunden wurden.

Im nächsten Schritt wurde die Pseudocode der Detektion erstellt und die geschätzte Laufzeit wurden berechnet. Das Messen der Laufzeit des Algorithmus in der menschenlichen rRNA war unvollständig geschafft.

## Projekt 3: Paarweise Alignments
- Implementieren des Needleman-Wunsch- und Smith-Waterman-Algorithmus
- Testen in einem konkreten Beispiel und vergleichen die Algorithmen
- Schätzen die Signifikant der Änhlichkeit durch Neadleman-Wunsch-Score
- Schätzen die Effezienz der Parameter
  
Zuerst wurden der Needleman-Wunsch- und der Smith-Waterman-Algorithmus implementiert. Diese Algorithmen nehmen zwei Sequenzen, eine Substitutionsmatrix und eine Gap-Penalty als Parameter entgegen und geben das Score des besten Alignments zurück.

Die Algorithmen wurden anschließend durch das Alignen der Sequenzen des Onkogens KRAS beim Menschen und bei der Maus getestet. Dabei lag der Fokus auf der Berechnung der Sequenzidentität in beiden Alignments und dem Vergleich dieser Alignments.

Die nächste Aufgabe befasste sich mit der Überprüfung, ob die beobachteten Ähnlichkeiten zwischen Sequenzen eine biologische Bedeutung haben oder zufällig sind. Hierzu wurden Zufallsalignments generiert, wobei eine der Sequenzen zufällig permutiert wurde. Die Wahrscheinlichkeit, ein Alignment mit einem Score größer oder gleich dem Originalalignment zu finden, wurde anhand des Gens von TRA2 in C. elegans und eyeless in D. melanogaster untersucht.

Die letzte Aufgabe betraf die Untersuchung des Einflusses von Alignmentparametern. Dabei wurden die Werte der Gap-Penalty, Match- und Mismatch-Scores variiert.

## Projekt 4: Hidden Markov Modelle
- Implementation des Viterbi-Algorithmus
- Generierung von Sequenzen
- Testen des Viterbi-Algorithmus
- Anpassung des Modells

In der ersten Aufgabe wurde der Viterbi-Algorithmus implementiert. Der Algorithmus erhielt eine Sequenz von Emissionen, Übergangswahrscheinlichkeiten von Zuständen (einschließlich des Startzustands) sowie Emissionswahrscheinlichkeiten für jeden Zustand als Eingabe. Das Ziel bestand darin, den wahrscheinlichsten Pfad (Zustandspfad) auszugeben.

Die nächste Aufgabe bestand drin, ein Hidden Markov Modell (HMM) zu verwenden, das Seqeunzbereiche mit erhöhtem GC-Gehalt und normale Sequenzbereiche modellierte. Hierbei wurde eine Methode erstellt, die dieses Modell und eine Sequenz erhielt und daraus Sequenzen (einschließlich Pfad und Symbolsequenz) erzeugte.

Im Rahmen der dritten Aufgabe erfolgte die Bewertung der Leistung des Viterbi-Algorithmus. Dazu wurden 1000 Sequenzen mit einer Länge von 1000 Basenpaaren erzeugt, zusammen mit ihren Zustandspfaden, unter Verwendung des vorgegebenen Hidden Markov Models (HMM). Im Anschluss erfolgte ein Vergleich der Viterbi-Pfade mit den tatsächlichen Pfaden, um die Qualität des Algorithmus anhand der Sensitivität und Spezifität der Ergebnisse zu schätzen.

Die Schätzungen aus der vorherigen Aufgabe dienten dazu, das Modell zu verbessern, wobei das Hauptziel darin bestand, die Sensitivität im Durchschnitt zu erhöhen. Dies führte zu der Annahme, dass die Anpassung der Übergangswahrscheinlichkeiten eine entscheidende Rolle spielt. Die abschließenden Ergebnisse bestätigten, dass die Modifikation dieser Wahrscheinlichkeiten das angestrebte Ziel erreichen konnte.




