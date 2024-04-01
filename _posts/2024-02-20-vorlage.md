---
title: "Tag 1 - Nachmittag"
date: 2024-02-15
---

Liebe Talia

Vom Mittagessen gestärkt ging es am Nachmittag mit dem zweiten Teil des ersten Tages Bibliotheks- und Archivinformatik weiter. 

Der erste Programmpunkt war das Ausfüllen einer Umfrage. Darin ging es um Chur, insbesondere um Chur als Studierendenstadt. Obschon sehr interessant, war die Umfrage ein wenig witzlos, da wir in letzter Zeit sehr viel Onlineunterricht hatten und Chur deshalb gar nicht so geniessen konnten. Nun ja, immerhin ist dieses Semester ein wenig besser als das letzte.

Als nächstes haben wir eine Einstellung der Codespaces geändert. Wir haben das Zeitlimit auf 240 Minuten, die maximal mögliche Zeit, erhöht. Das Zeitlimit gibt vor, wie lange ein Codespace läuft, bevor er automatisch geschlossen wird. Dies sollte sicherstellen, dass sich unser Codespace nicht inmitten einer Übung schliesst.

Nachdem alle ihre Einstellungen angepasst hatten, ging es an die erste Übung. Uns wurde ein GitHub Repository zur Verfügung gestellt, sowie eine Aufgabensammlung (Library Carpentry: The Unix Shell: Navigating the filesystem), aus der wir die Kapitel 2 (Navigating the file system) und 3 (Working with files and directories) bearbeiten sollten. Wir hatten Unixbefehle schon in mehreren Modulen behandelt, aber ich bin immer um eine Auffrischung froh, da wir damit noch nie länger gearbeitet und deshalb auch nie richtig im Langzeitgedächtnis abgespeichert haben. Um eine schnell griffbereite Ressource bereit zu haben, stelle ich hier die wichtigsten Befehle noch einmal zusammen:
* pwd (print working directory) – zeigt den path des aktuell geöffneten Ordner an
* ls (list) – zeigt eine Auflistung aller Inhalte des aktuellen Ordners an
* ls -l – gibt die gleiche Liste mit zusätzlichen Informationen, wie die Dateigrösse, an
* ls -lh – gibt die Dateigrösse in nutzbarerer Form an
* cd «Name des Ordners» (change directory) – bewegt sich zum Angegebenen Ordner (Anführungszeichen sind nötig, um mehrere * durch Abstände getrennte worte zu einem Namen zusammenzufügen)

* cd – ohne Argumente bewegt sich zum Home Directory
* cd .. – bewegt sich einen Ordner «nach oben» in der Baumstruktur
* mkdir «Name des neuen Ordners» - erschafft einen Ordner an der aktuellen Stelle mit dem gewünschten Namen
* cat «Name eines Textdokuments» - druckt den gesamten Text eines Dokuments in die Konsole
* head «Name eines Textdokuments» - druckt die ersten zehn Zeilen eines Dokuments
* tail «Name eines Textdokuments» - druckt die letzten Zehn Zeilen
* less «Name eines Textdokuments» - zeigt das Dokument Seite für Seite an, Leertaste für nächste Seite, q um die Ansicht zu beenden
* Wildcards: ? steht für genau ein Zeichen, * steht für beliebig viele Zeichen
	Bsp: 	dokument?.txt 	= dokument1.txt, dokument2.txt
		*.txt 			=dokument1.txt, dokument2.txt, text.txt
* mv «alter Name» «neuer Name» (move) – umbenennen einer Datei oder eines Ordners
* mv «Datei» «Ordner» - bewegt die Datei in den angegebenen Ordner
* cp «Datei» «Kopie» - erstellt eine Kopie einer Datei mit dem angegebenen Namen
* rm (remove) – löscht Dateien
* rm -r – löscht Ordner mitsamt den Inhalten
* Nützlicher Tipp: Nutze tab zur Autovervollständigung von Ordner- und Dateinamen

Als nächstes hat uns der Dozent noch git und GitHub näher erklärt. Git ist eine Software zur Versionskontrolle. GitHub ist eine Plattform, auf der Repositories angelegt werden können, so dass mehrere Entwickler an den gleichen Dateien arbeiten können. Dies erfolgt nicht wie bei bsp, Google Docs per live-Bearbeitung sondern über verschiedene Branches, die dann, nach etwaiger Kontrolle, einander überführt werden. 

Zum Abschluss wurde uns noch einmal das Löschen von Codespaces gezeigt und ein Ort angelegt, wo wir die Links zu unseren Lerntagebüchern einfügen können. 

Somit lag der erste Tag von BAIN hinter uns. Ich bin gespannt, was wir das nächste Mal anschauen werden.

Bis dann!

Lukas

