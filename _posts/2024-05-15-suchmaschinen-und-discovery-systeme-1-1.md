---
title: "Suchmaschinen und Discovery-Systeme 1/2 "
date: 2024-05-15
---


Suchmaschinen und Discovery-Systeme 1/2 

Liebe Talia

Heute haben wir uns mit Suchmaschinen und Discoverysystemen beschäftigt. Dazu haben wir VuFind sowie Solr verwendet. VuFind ist ein modulares Discoverysystem, welches benutz werden kann, um Suchen in Datensätzen vorzunehmen. Solr ist, soweit ich das verstanden habe, das Suchsystem mit welchem VuFind dann schlussendlich läuft. Kurzgesagt, VuFind stellt die Benutzeroberfläche für eine Solr-Suchanfrage zur Verfügung. Mehr zum Vergleich der beiden Anwendungen später.

Der erste Teil der Vorlesung war eine relativ lange Einführung sowie Anleitung der Installation von VuFind. Ich bin da nicht ganz mitgekommen, aber da wir sowieso alle auf einem Server arbeiten würden, spielte dies keine grosse Rolle. Der Dozent führte uns die Installation vor und setzte den Server auf, über welchen wir dann Zugriff auf VuFind hatten. Danach gab er uns eine Einführung in das Programm. Solr ist, zusammen mit einer anderen Anwendung namens Elasticsearch der Industriestandard. Um korrekt zu funktionieren, benötigt Solr beim Datenimport ein Schema, in welchem festgelegt wird, welche Felder existieren und welche Datentypen in die Felder eingefügt werden dürfen. Die Suchoberfläche von Solr ist eigentlich nur zu Demo-Zwecken gedacht, kann aber verwendet werden, was wir im Verlauf der Vorlesung auch tun werden. Um eine bessere, oder zumindest übersichtlichere Suchoberfläche zu erhalten, werden Discoverysysteme wie VuFind benötigt.

Es folgte eine Auflistung der Differenzen zwischen Suchindexen (wie Solr) und Datenbanken (wie zum Beispiel MySQL). Suchindexe behandeln flache Dokumente und führen eine lexikalische Suche durch. Es wird keine Konsistenzprüfung verwendet und es ist auf statische Daten ausgelegt. MySQL dagegen verwendet relationale, also verknüpfte Datensätze. Die Suche gestaltet sich als reiner Glyphenvergleich. Es wird Transaktionssicherheit gewährleistet und vor Allem veränderliche Daten verwendet. Der bedeutendste Unterschied aber ist, dass die Hauptfunktion von Suchindexen das Retrieval, also die Suche und Beschaffung ist, während Datenbanken auf Storage, die Lagerung ausgelegt ist.

Als nächstes behandelten wir die Unterschiede zwischen Horizontalen und Vertikalen Suchmaschinen. Eine horizontale Suche erfolgt in heterogenen Datenbeständen. Sie erfordert kein Datenschema und erlaubt auch keine semantischen Abfragen oder Feldsuchen. Horizontale Suchen werden beispielsweise bei Google-Suchen angewendet. 
Vertikale Suchen benötigen ein Datenschema. Feldsuchen sind möglich, doch dafür müssen die Datenbestände vereinheitlicht sein. Dies funktioniert am besten, wenn die Datensätze die selbe Quelle oder das selbe Erfassungssystem haben, wie beispielsweise bei Bibliothekskatalogen.

Ein grosser Teil der Vorlesung war eine Übung, bei welcher wir verschiedene Suchanfragen bei VuFind und Solr durchführen und unsere Erfahrungen vergleichen sollten. Dazu nutzen wir den vom Dozenten aufgesetzten Server. Die eigentlichen Suchergebnisse unterschieden sich nicht, was irgendwie logisch ist, da sie ja das selbe System verwenden. Der grösste Unterschied lag in der Darstellung: Solr gibt die Ergebnisse im XML Format zurück. Wenn man ein bisschen sucht, findet man die Anzahl der Ergebnisse, aber ansonsten ist die Ergebnisliste recht unübersichtlich. Bei VuFind werden die Ergebnisse in einer übersichtlichen Liste angegeben. Sie können für weiter Information angeklickt werden. Auch kann durch anklicken der vergebenen Schlagworte oder Autoren die Suche gleich weitergeführt werden. Bei Solr müsste man den Begriff extra im richtigen Feld eingeben. VuFind besitzt nur ein Suchfeld, dieses kann jedoch mittels eines Drop-Down-Menüs angepasst werden (alle Felder, Schlagworte, Autoren, etc.) 
(Side Note: Wir starteten mit dem Suchbegriff «Psychology». Die beiden Systeme sind nicht fehlertolerant, auch mit nur kleinen Tippfehlern wird kein Ergebnis gefunden. Seltsamerweise führte der Begriff «Psychologi» zu den selben Resultaten, ähnliche Schreibweisen wie «Psychologu», «Psichology» oder «Psycholojy» jedoch nicht. Ich habe keine Erklärung dafür, fand es aber spannend.)
Die Übung stellte den Schluss der Vorlesung dar. Viele Einträge sind es nicht mehr, aber ich bin gespannt auf den Endspurt!

Bis dann!

Lukas





