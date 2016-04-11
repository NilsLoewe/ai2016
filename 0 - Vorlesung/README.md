# Softwarearchitektur SS2016

### Altes Konzept

  * Motivation und Grundlagen
  * Hibernate
  * Entwurf von Architekturen
  * Architekturansichten -> Vier Sichten auf Architekturen
  * UML -> Die gleichen vier Sichten
  * Vorgehensweise bei der Architekturentwicklung
  * Qualität von Lösungsstrategien
  * Konnektoren / Schnittstellen
  * Prinzipien des Architekturentwurfs (Architekturmuster)
  * Architekturstile (auch Muster?)
  * NoSQL als Fallbeispiel


## Konzept

1. Organisation & Motivation
2. Begriffe
3. Geschichte und Trends
4. Sichten auf Architekturen
5. Qualiät und andere nichtfunktionale Anforderungen
6. Architekturmuster
7. Dokumentation von Architekturen
8. Technologien und Frameworks

## Plan fürs Semester

1.  17.03.16 - Motivation, Überblick, Organisation
2.  24.03.16 - Geschichte, Sichten
3.  31.03.16 - Qualität und andere nichtfunktionale Anforderungen
4.  07.04.16 - Qualität und andere nichtfunktionale Anforderungen
5.  14.04.16 - Architekturmuster: Antipatterns, Layers
6.  21.04.16 - Rückblick 1. Praktikumsaufgabe, Architekturmuster:
7.  28.04.16 - Dokumentation von Architekturen: arc42
8.  12.05.16 - Dokumentation von Architekturen: Schnittstellen
9.  19.05.16 - Technologie: Spring Boot (Jan) | Rails (ich)
10. 26.05.16 - Technologie: ???               | Docker (Ben)
11. 02.06.16 - Technologie: ???               | Microservices (Jens)
12. 09.06.16 - Rückblick, Wiederholung, Klausurvorbereitung


### Vorlesung 1

#### Einleitung & Motivation

* Vorstellung: Wer bin ich?
* Überblick über die Veranstaltung
  * 12 Vorlesungen
  * 4 Praktika: Aufeinander aufbauende Aufgaben
  * Eine Klausur
  * Termine
* Motivation
  * Was ist Softwarearchitektur?
  * Was ist nicht Softwarearchitektur?
  * Wozu braucht man Softwarearchitektur?
  * Die Rolle des Softwarearchitekten (Status, Aufgaben, Karriere, ...)

### Vorlesung 2+3

* Todo: Zettel für Raumänderung
* Zettel für Umfrage

#### Geschichte und Trends
  * Großrechner mit Thin-clients
  * Personalcompuer
  * Web / Smartphones / Tables -> Browser als OS
  * Internet of Things

#### Sichten auf Architekturen

  * Motivation: Warum überhaupt Sichten?
  * Überblick über die vier Sichten
    * Kontext
    * Baustein
    * Laufzeit
    * Verteilung
  * Jeweils
    * Was ist die Aufgabe der Sicht?
    * Für wen ist sie speziell interessant?
    * Was für Informationen sind darin enthalten?
    * Was ist NICHT drin? Was kann ich also alles nicht wissen, wenn ich zu einer Architektur nur diese Sicht habe?
    * Weitere Fragen aus 'Effektive Architekturen' ...

  * Statische vs. Dynamische Sichten
  * Jeweils einige Details wichtig
  * UML als Anwendung der Sichten

#### Qualiät und andere nichtfunktionale Anforderungen

  * Was ist Qualität?
  * Skalierbarkeit
  * Performance
  * Sicherheit
  * Wartbarkeit
  * Testbarkeit

### Vorlesung 4: Architekturmuster

http://www.itwissen.info/definition/lexikon/Architekturmuster-architectural-style.html
http://www.lab4inf.fh-muenster.de/lab4inf/docs/OO-Systeme/08-ArchitekturMuster.pdf
https://www.wi1.uni-muenster.de/pi/lehre/ws0405/seminar/10Architekturmuster.pdf
https://www.st.cs.uni-saarland.de/edu/einst/08-arch.pdf
http://www.enzyklopaedie-der-wirtschaftsinformatik.de/lexikon/is-management/Systementwicklung/Softwarearchitektur/Architekturentwicklung/architekturmuster
https://de.wikipedia.org/wiki/Architekturmuster
https://www4.in.tum.de/misc/perlen/perlen-folien/PDW_Architektur_IK_Druckversion.pdf

1. Rückblick
  * Sichten
  * Qualität
2. Praktikumsaufgabe 2
3. Architekturmuster

  * Einleitung / Intro
    * Was sind Architekturmuster? -> Verallgemeinertes Wissen, Best Practices
    * Warum Architekturmuster? -> Ordnung ins Chaos bringen
    * Wo sind die Grenzen von Architekturmustern? --> Hypes etc.
    * Video: SoCoded 2015
  * Überblick - Welche Arten von Architekturmustern gibt es?
    * Chaos zu Struktur / Mud-to-structure)
      * Pipes und Filter
      * Schwarzes Brett bzw. Blackboard
      * Schichtenarchitektur
      * Domain-driven Design
      * Naked Objects
      * Data Context Interaction
      * Command Query Responsibility Segregation
    * Verteilte Systeme
      * Serviceorientierte Architektur (SOA)
      * Peer-to-Peer
      * Client-Server
    * Interaktive Systeme
      * Model View Controller (MVC)
      * Model View Presenter
      * Presentation-Abstraction-Control (PAC)
    * Adaptive Systeme
      * Mikrokernel
      * Reflexion
      * Dependency Injection
    * Anti-Patterns
      * The Blob. Ein Objekt ( Blob“) enthält den Großteil der Verantwortlichkeiten
      * The Golden Hammer. Ein bekanntes Verfahren ( Golden ”Hammer“) wird auf alle moglichen Probleme angewandt
      * Cut-and-Paste Programming. Code wird an zahlreichen Stellen wiederverwendet
      * Spaghetti Code. Der Code ist weitgehend unstrukturiert; keine Objektorientierung oder Modularisierung
      * Mushroom Management. Entwickler werden systematisch von Endanwendern ferngehalten.
      * Vendor Lock-In. Ein System ist weitgehend abhangig von einer proprietaren Architektur oder proprietaren Datenformaten.
      * Design by Committee. Das typische Anti-Muster von Standardisierungsgremien
      * Reinvent the Wheel. Da es an Wissen über Produkte und Losungen fehlt
      * Lava Flow (schnell wechselnder Entwurf)
      * Boat Anchor (Komponente ohne erkennbaren Nutzen)
      * Dead End (eingekaufte Komponente, die nicht mehr unterstützt wird)
      * Swiss Army Knife (Komponente, die vorgibt, alles tun zu können)

### Dokumentation von Architekturen

  * Warum dokumentieren?
  * Wie dokumentieren?
  * Beispiele
    * ARC42 Framework
    * ISO Normen (Luftfahrt, Safety)
  * Framework-Dokumentation
    * JavaDoc
    * Lesen von Framework-Dokumentation
  * Tools zur Dokumentation
    * Swagger als API Dokumentation

### Technologien und Frameworks

  * Was sind Architketurframeworks?
  * Vorteile/Nachteile von Frameworks?
  * Beispiele für Frameworks
    * Ruby on Rails
    * .NET
    * Twitter Bootstrap
  * Kriterien für die Auswahl eines Frameworks
    * Funktionale Anforderungen: Wieviel Framework brauche ich?
    * nichtfunktionale Anf.: Was muss das FW noch so können?
    * Unternehmensanforderungen: Was gibt es schon? (Vorgängerprojekte, Sprachen im Einsatz, ...)
    * Verbreitung des Frameworks? (Reife, gibt es in x Jahren noch Entwickler, Wartung, Breaking Changes, ...)
