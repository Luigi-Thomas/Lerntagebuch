---
title: "Metadaten modellieren und Schnittstellen nutzen 1/2"
date: 2024-04-16
---

Metadaten modellieren und Schnittstellen nutzen ½

Liebe Talia

Diesmal liess der nächste BAIN-Termin nur eine Woche auf sich warten. Wir behandelten vor Allem die Modellierung von Metadaten. Wir bekamen zunächst eine Einführung in OpenRefine. Bei OpenRefine handelt es sich um eine Software, die der Analyse, Bereinigung, Konvertierung und Anreicherung von Daten dient. Dabei werden die Daten in einer Tabelle angezeigt, die sich leicht anpassen und bearbeiten lässt.

OpenRefine unterstützt vor Allem tabellarische Daten, also Dateiformate wie CSV, TSV, XLS und XLSX, aber auch TXT Dateien mit Trennzeichen oder festen Spaltenbreiten sind möglich. Dateformate wie JSON oder MARCXML sind ein wenig schwieriger einzufügen, komplexere XML Formate wie zum Beispiel EAD können sogar nur mit zusätzlichen Tools importiert werden.

OpenRefine hat verschiedene Einsatzmöglichkeiten, wie die Exploration von Datenlieferungen, die Vereinheitlichung und Bereinigung von Daten oder den Abgleich mit Normdaten in Wikidata, GND und VIAF. OpenRefine ist ohne Zusatzsoftware nur für den lokalen Einsatz gedacht.

Ein kurzer historischer Abriss zeigte uns auf, dass OpenRefine (oder zumindest seine Vorgänger) schon seit 2010 existieren, was noch einmal die Wichtigkeit einheitlicher Daten aufzeigt.

Danach ging es schon mit einer Übung weiter. Wir öffneten einen Codespace (nachdem ich mir wieder ins Gedächtnis gerufen hatte, wie das alles überhaupt funktioniert) und starteten die OpenRefine Anwendung.

Zunächst kreierten wir ein neues Projekt und importierten die Beispieldaten über einen URL. Gemeinsam mit dem Dozenten lernten wir einige Basisfunktionen kennen. Als Erstes vereinheitlichten wir die Sprachen in der Spalte «Language». Danach splitteten wir die Autorennamen, so dass jeder Autor einzeln aufgelistet wurde, was uns eine Übersicht über die produktivsten Autoren gab. Die Cluster Funktion legte verschiedene Schreibweisen des selben Autors zusammen zu einem Eintrag, was ich recht faszinierend fand.

Als kleinere Übung extrahierten wir die vorhandenen Lizenzen und konnten dann sehr einfach feststellen, welche Lizenz am häufigsten vorhanden war und wie viele Artikel gar keine Lizenz hatten. Das gleiche machten wir mit dem Publisher, wobei einer aufgrund eines zusätzlichen Leerschlages bei einigen wenigen Artikeln zweimal vorkam. Dies konnte über einen einfachen Edit in der Übersicht korrigiert werden.

Als Nächstes kreierten wir eine neue Spalte mit Namen «Journal». Dazu splitteten wir den ersten Teil der Spalte «Citation» ab, also den Namen des Journals. Über die Reconcile Funktion konnte der Name mit den Daten von Wikidata abgeglichen und ergänzt werden. 

Als Letztes exportierten wir die vorhandenen CSV Daten nach MARCXML. Dazu nutzten wir die Templating Exporter Funktion. Dazu konnte ein Template eingegeben werden, was dann eine Voransicht der ersten zehn Einträge im angegebenen Format generierte. Aufgrund der MARCXML Regeln fügten wir neue Datenpunkte in das Template hinzu, welche dann korrekt in der Ansicht ergänzt wurden. 

Dieser Tag verlangte viel aktive Beteiligung, was es zwar leichter macht trotz online Unterricht dabei zu bleiben, aber doch auch recht anstrengend ist. Dennoch bin ich gespannt auf Teil 2 dieses Themas. In dem Sinne, einen schönen Abend noch.

Bis dann!

Lukas
