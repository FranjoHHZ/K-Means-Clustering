# K-Means-Clustering

In dieser Übungsaufgabe verwenden wir den K Means Clustering-Algorithmus, um Universitäten in den USA in zwei Gruppen zu unterteilen: private und öffentliche Universitäten. K Means Clustering ist ein unüberwachter Lernalgorithmus, der normalerweise verwendet wird, um Daten zu gruppieren, deren Zuordnung zu einem bestimmten Cluster unbekannt ist. In diesem Fall kennen wir die Zuordnung bereits, verwenden sie jedoch nur zur Beurteilung der Leistung des Algorithmus.

# Ausführung 
Daten laden und vorbereiten: Lesen Sie die Daten in einen DataFrame ein und bereiten Sie sie für die Modellierung vor. Wir verwenden die Daten von 777 Universitäten und 18 Variablen, die verschiedene Aspekte der Universitäten beschreiben, wie z. B. die Anzahl der Bewerbungen, die Studiengebühren und die Abschlussrate.

Daten visualisieren: Erstellen Sie verschiedene Scatterplots und Histogramme, um die Verteilung und die Beziehungen zwischen den Variablen zu untersuchen. Beispielsweise können Sie ein Scatterplot erstellen, das die Abschlussrate (Grad.Rate) gegen die Zimmerkosten (Room.Board) für private und öffentliche Universitäten zeigt.

K Means Clustering anwenden: Verwenden Sie den K Means-Algorithmus mit 2 Clustern, um die Universitäten anhand ihrer Eigenschaften zu gruppieren. Ignorieren Sie dabei die Spalte Private, die die tatsächliche Klassifizierung angibt. Trainieren Sie das Modell mit den restlichen Variablen.

Auswertung der Clustering-Ergebnisse: Erstellen Sie eine Confusion Matrix und einen Classification Report, um zu sehen, wie gut das K Means Clustering die Universitäten in private und öffentliche Kategorien gruppiert hat.

#Erwartetes Ergebnis
Der K Means-Algorithmus erstellt zwei Cluster, die anhand der numerischen Eigenschaften der Universitäten gebildet werden. Da dies ein unüberwachter Lernalgorithmus ist, kennt er die wahre Zuordnung der Daten nicht. Wir vergleichen die vom Modell vorhergesagten Cluster mit der tatsächlichen Klassifizierung, um die Leistung zu bewerten.

Confusion Matrix und Classification Report: Die Confusion Matrix und der Classification Report zeigen, dass der Algorithmus zwar in der Lage ist, eine gewisse Struktur in den Daten zu erkennen, aber die Genauigkeit und Präzision des Modells relativ gering sind. Die Genauigkeit liegt bei 22 %, was zeigt, dass die Zuordnung nicht perfekt ist, was in der Regel bei unüberwachten Algorithmen der Fall ist, da sie nicht auf die wahre Zuordnung trainiert werden.

Diese Übung zeigt, dass K Means Clustering eine nützliche Technik ist, um Gruppen in Daten zu finden, deren Zugehörigkeit unbekannt ist. Es verdeutlicht auch die Herausforderung, einen unüberwachten Lernalgorithmus zu bewerten, wenn die wahre Zuordnung nicht bekannt ist


# Binder Bange
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FranjoHHZ/K-Means-Clustering/HEAD)
