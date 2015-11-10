Title: Machine Learning Grundlagen
Date: 2015-06-15 10:20
Category: Allgemein
Tags: Allgemein, Klassifikation, Iris dataset
Authors: Martin Thoma

Im folgenden werden Grundlagen des maschinellen Lernens erklärt.


## Was ist maschinelles Lernen?

Beim maschinellen Lernen geht es darum einen Algorithmus zu schreiben, der mit
Daten lernt was relevant ist. Der Algorithmus kennt also eine allgemeine
Struktur, wo er Teile anpassen kann, sodass eine Aufgabe "möglichst gut"
erfüllt wird. Was "möglichst gut" bedeutet, muss der Programmierer festlegen.

Tom Mitchel hat maschinelles Lernen wie folgt Definiert:

> A computer program is said to learn from experience $E$ with respect to some
> class of tasks $T$ and performance measure $P$, if its performance at tasks
> in $T$, as measured by $P$, improves with experience $E$.


## Ein Beispiel

Angenommen man hat eine [Schwertlilie](https://de.wikipedia.org/wiki/Schwertlilien).
Es ist klar, dass es eine Schwertlilie ist, aber es könnte entweder eine
Iris Setosa, eine Iris Virginica oder eine Iris Versicolor sein. Man muss nun
ein Programm schreiben, welches die 3 Arten von einander unterscheiden kann.
Der Einfachkeit halber werden diese im Folgenden als Klasse I, II und III
bezeichnet.

Biologen haben für je 50 konkrete Pflanzen (Instanzen der drei Arten) vier
Größen gemessen:

* [Kelchblatt](https://de.wikipedia.org/wiki/Kelchblatt): Länge und Höhe, in cm.
* [Kronblatt](https://de.wikipedia.org/wiki/Kronblatt): Länge und Höhe, in cm.

Wie kann man diese Information nun nutzen um zu lernen, was eine Iris
Versicolor von einer Iris Virginica unterscheidet?

Der einfachste Ansatz wäre die Daten für einfache Klassifikatoren zu
betrachten. Vielleicht hat Klasse I ja immer eine deutlich kleinere
Kelchblattgröße. Oder vielleicht ist das Verhältnis zwischen Kelchblattlänge
und Kelchblattbreite deutlich unterschiedlich bei den Arten.

Das wäre eine einfache Lösung für dieses Klassifikationsproblem.

<!-- ## Klassifikatoren vergleichen

Natürlich gibt es viele weitere Möglichkeiten das Klassifikationsproblem zu
lösen. Und wir wollen die beste finden. Aber was ist die beste Möglichkeit?
Dafür muss man eine Fehlerfunktion haben.  -->

## Decision Trees

TODO: Kurz erklären, damit es später verwendet werden kann.


## Vorgehen

Es gibt jedoch auch kompliziertere Lösungen wie decision trees, Support Vector
Machines (SVMs) und neuronale Netze. Diese haben interne Parameter, welche
angepasst werden um eine Lösung zu finden. Bei allen diesen Klassifikatoren
kann man zwischen *Training* und *Evaluation* unterscheiden. Beim Training
lernt der Klassifikator was wichtig ist und in der Evaluation wendet er es an.

* Training / Validation / Development / Testset
* Hyperparameter
* Datengetriebene Entwicklung
* Overfitting
* Supervised <-> unsupervised
* Classification, Regression

## Abgrenzung

* Machine Learning <-> A.I. <-> Data science <-> Statistik <-> Big Data

Als 

## Siehe auch

* [Statistical classification](https://en.wikipedia.org/wiki/Statistical_classification)