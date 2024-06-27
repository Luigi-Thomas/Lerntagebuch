---
title: "Linked Data"
date: 2024-05-29
---

Linked Data

Liebe Talia

Letzte Vorlesung! Der Abschluss bestand in einer Lerneinheit zum Thema Linked Data. Dazu behandelten wir zunächst BIBFRAME. BIBFRAME wird seit 2012 als Nachfolger von MARC21 entwickelt. Es basiert grösstenteils auf  Functional Requirements for Bibliographic Records und Resource Description and Access (RDA). Diese werden jedoch nicht vollständig umgesetzt. Die beiden Bestandteile von BIBRAME sind das BIBFRAME Model und das BIBFRAME Vocabulary. Das Modell sieht die Unterteilung in die drei Typen Work, Instance und Item vor, sowie die drei Entitäten Agent, Subject und Event. Das Vokabular dient zur Beschreibung der Entitäten und definiert dazu Konzepte und Eigenschaften. Zum Vokabular gehören beispielsweise Klassen, welche Eigenschaften besitzen. Durch Zuordnen von Klassen können so einfach grössere Mengen an Eigenschaften vergeben werden. Klassen können auch Subklassen von anderen Klassen sein und so bestimmte Eigenschaften «erben». Das ganze basiert auf Kontepten von RDA. BIBFRAME beschreibt seine Records mit Beziehungen zu anderen Records oder Datensätzen, nicht wie beispielsweise MARC XML als eigenständige Einträge. Dies verhindert das mehrfache Speichern von gleichen Informationen. Anstatt also beispielsweise bei vielen Büchern den gleichen Eintrag zum Autor zu machen, wird einfach überall eine Verlinkung zum Eintrag des Autors erstellt.
Unter https://id.loc.gov/tools/bibframe/comparebf-lccn/2018958785.xml kann eine Gegenüberstellung von BIBRAME XML und MARC (XML) gefunden werden. Wieder einmal fällt auf, dass MARC XML deutlich schwieriger zu lesen ist, aufgrund der fehlenden sprechenden Bezeichnungen der Datenfelder. Bei BIBFRAME werden zudem Links verwendet, um auf eine Bezeichnung oder Entität zu verweisen, was den Informationsbezug erleichtert.

Das nächste Thema war Records in Context (RIC). Dieser Standard basiert auf den Linked-Data-Prinzipien. Wir haben ihn schon in anderen Modulen behandelt. Das Modell sieht ebenfalls die Darstellung von Metadaten durch Beziehungen zu anderen Datensätzen vor. Im Gegensatz zu BIBFRAME wird dieser Standard aber bereits in der Praxis verwendet. 

Wir beschäftigten uns dann mit Linked Open Usable Data (LOUD). Dazu wird JSON verwendet. JSON haben wir bereits in anderen Modulen behandelt, es handelt sich um ein Datenformat, welches verschiedenen Keys bestimmte Values zuordnet. Beim Konzept der LOUD wird nun JSON-LD verwendet. Dabei handelt es sich um ein JSON-Format, welches zugleich als RDF nutzbar ist. Grundsätzlich erhält eine JSON-Datei einfach noch einen Link um den Kontext des Datensatzes zu erhalten. Somit können Beziehungen und Eigenschaften in regulärem JSON-Format festgehalten werden.

Beim Thema Large Language Model befragten wir verschiedene Programme, wie ChatGPT, zu den aktuell behandelten Themen. Die Antworten reichten von ziemlich gut bis zu nicht benutzbar. So lieferte Copilot auf die Frage, inwiefern BIBRAME bereits in Bibliotheken eingesetzt wird, eine Abhandlung über die Geschichte, die Eigenschaften und Vorzüge von BIBFRAME. Fachlich deckte sich alles mit dem bisher gelernten, jedoch wurde die Frage überhaupt nicht beantwortet. ORKG antwortete, die erste Verwendung von BIBFRAME sei in Bibelzitaten. Na ja.

Als Nächstes schauten wir uns Wikidata an. Wikidata hatten wir schon im Modul Grundlagen semantischer Technologien behandelt. Dort lernten wir die Query-Sprache. Hier lernten wir den Query Builder kennen, welcher das Lernen der Sprache überflüssig macht. 

Zum Schluss zeigte uns der Dozent noch einmal, wie die Reconciliation funktioniert, also die Verknüpfung von importierten Daten mit einem Service wie Wikidata. 

Dies war die letzte Vorlesung im Modul Bibliotheks- und Archivinformatik. Als letzter Eintrag folgt nun nur noch eine Zusammenfassung, was ich alles gelernt, beziehungsweise nicht gelernt habe. Also, auf zum Endspurt!

Bis dann,
Lukas

 


