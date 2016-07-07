## Aufgabe 1

1.1. Definitionen für Softwarearchitektur

* Die Architektur eines Softwaresystems ist die Menge der Haupt-Designentscheidungen über das System
* Die Software-Architektur ist die grundlegende Organisation eines Systems, dargestellt durch dessen Komponenten, deren Beziehungen zueinander und zur Umgebung sowie die Prinzipien, die den Entwurf und die Evolution des Systems bestimmen
* Software Architecture = { what, how, why }
* The software architecture of deployed software is determined by those aspects that are the hardest to change

1.2 Drei Gründe für Sichten
* Eine einzelne Darstellung kann die Vielschichtigkeit und Komplexität einer Architektur nicht ausdrücken.
* Sichten ermöglichen die Konzentration auf einzelne Aspekte des Gesamtsystems und reduzieren somit die Komplexität der Darstellung.
* Die Projektbeteiligten haben ganz unterschiedliche Informationsbedürfnisse.
* Mit Hilfe von unterschiedlichen Sichten lassen sich viele Aspekte von Architektur verständlich darstellen.

1.3 Was ist ein Architekturmuster?
* Ein Architekturmuster beschreibt eine bewährte Lösung für ein wiederholt auftretendes Entwurfsproblem
* Heuristiken kodifizieren Erfahrungen anderer Architekten und Projekte, auch aus anderen Bereichen der Systemarchitektur

1.4 Nennen Sie jeweils einen Vor- und Nachteil des Layers Musters

Vorteile
* Wiederverwendung und Austauschbarkeit von Schichten
* Unterstützung von Standards
* Einkapselung von Abhängigkeiten

Nachteile
* Geringere Effizienz
* Mehrfache Arbeit (z.B. Fehlerkorrektur)
* Schwierigkeit, die richtige Anzahl Schichten zu bestimmen

1.5. Drei Gründe für den Einsatz von Frameworks
* Wiederverwendung von Code
* Grundfunktionalität muss nicht immer wieder implementiert werden
* Es existieren genormte Schnittstellen z.B. zu Datenbanken
* Frameworks erleichtern die Programmierarbeit und sparen Entwicklungszeit
* Frameworks können den Stil entscheidend verbessern

## Aufgabe 2

2.a) Kontextsicht
* Welche Fremdsysteme gibt es?
* Welche Nutzer interagieren mit dem System?
* Wo ist die Grenze des systems?

2.b) Bausteinsicht
* Aus welchen Komponenten besteht die Anwendung?
* Welche Technologien setzen Sie ein?

## Aufgabe 3

* Architektur vs. Design               |      |  NEIN  |
* Möglichst viel Info                  |      |  NEIN  |
* Ideal vier Sichten                   |  JA  |        |
* Bausteinsicht in nur Referenz        |      |  NEIN  |
* Jede Sicht bekommt die gleiche Zeit  |      |  NEIN  |
* Gute Architektur -> Guter Code       |      |  NEIN  |
* Architekturmuster = Kontext          |  JA  |        |
* MVC ist eine Variante des Layers     |  JA  |        |
* ARC42 kommt von der IEEE             |      |  NEIN  |
* Keine Frameworks in krit. Projekten  |      |  NEIN  |
