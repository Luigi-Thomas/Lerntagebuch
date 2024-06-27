---
title: "Metadaten modellieren und Schnittstellen nutzen 2/2"
date: 2024-04-24
---

Metadaten modellieren und Schnittstellen nutzen 2/2

Liebe Talia

Diese Vorlesung war ganz schön heftig, sehr technisch und komplex. Doch ich versuche mein Bestes, dir zu schildern, was wir behandelt haben.

Nach einem kurzen Recap zu OpenRefine und zur Reconciliation von Daten wendeten wir uns den Schnittstellen für Metadaten zu. Zunächst schauten wir drei der Übertragungsprotokolle für Metadaten im Bibliotheks- und Archivbereich an: Z39.50 und SRU von der Library of Congress, sowie OAI-PMH von der Open Archives Initiative. Der Dozent erzählte uns von den verschiedenen Einsatzzwecken der einzelnen Protokolle, so sind Z39.50 und SRU besser für Live-Abfragen oder gezielten Datenabruf mit vielen Parametern geeignet, während OAI-PMH eher für grössere Datenabzüge ausgelegt ist. Zudem können SRU und OAI-PMH ohne Installation einer Software einfach über den Browser verwendet werden. 

Als nächstes folgte eine Übung. Wir öffneten wieder einen Codespace und machten uns an den Import von Metadaten über OAI-PMH mit VuFindHarvest. Über einen Command importierten wir Daten von Koha, ArchivesSpace und DSpace, die wir ja alle in früheren Vorlesungen behandelt hatten. OAI-PMH musste zuerst über die Administrationsoberfläche aktiviert werden. Der Dozent führte dies vor, doch ich muss zugeben, dass ich da kurz abgelenkt war. Offenbar aktivierte der Dozent OAI-PMH generell, denn beim Import von den Koha-Daten gab es anschliessend keine Probleme. Nach dem Import war nun aus jedem Eintrag eine eigene Datei geworden. Dies Daten sollen aus ihren ursprünglichen Formaten (MARC21-XML, EAD und DC) nun einheitlich in MARC21-XML umgewandelt werden.

Um diese Konvertierung durchzuführen, verwendeten wir XSLT Crosswalks. Als Crosswalks bezeichnet man die Konvertierung eines Metadatenstandards in einen anderen. Dazu wird Mapping angewendet, das heisst es werden vorhandene Regeln über die Zuordnung von Elementen und Werten verwendet. Die Konvertierung mittels Crosswalk ist im Idealfall verlustfrei, es kann aber dennoch zu Abweichungen kommen. Für die Umwandlung verwendeten wir zunächst das Online-tool xsltransform (http://xsltransform.net). 

Dieses Tool benötigt für die Konvertierung zusätzlich zu der XML Datei auch eine XSL Datei, welche die Regeln zur Konvertierung beinhaltet. Diese wurde uns vorgegeben und wir mussten sie zum Glück nicht selbst schreiben. Die Konvertierung funktionierte ohne Probleme.

Bei der Konvertierung von EAD zu MARC21 scheiterte xsltransform jedoch. Wir mussten das Tool MarcEdit verwenden. Dieses musste zuerst auf dem Rechner installiert werden. Nach einer kurzen Lektion über das Tool sowie seine Nutzungsbedingungen unternahmen wir einen zweiten Versuch, die Transformation durchzuführen. Die Konvertierung verlief ohne grössere Probleme, doch es waren zwei Schritte notwendig: Zuerst musste EAD in MARC21, danach MARC21 in MARC21XML umgewandelt werden. Leider ist bei diesem Prozess die Konvertierung nicht verlustfrei. 

Zum Schluss wurden uns noch einige weitere Tools präsentiert, die zur Metadatentransformation verwendet werden kann. Zu diesem Zeitpunkt war meine Konzentration leider nicht mehr so ganz auf der Höhe, weshalb ich jetzt hier nicht detailliert darüber Auskunft geben kann. 

So, nun hast du etwa 3 Wochen Ruhe von mir. 
Bis dann!
Lukas 




