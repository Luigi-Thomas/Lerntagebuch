---
title: "Suchmaschinen und Discovery-Systeme 2/2"
date: 2024-05-22
---

Suchmaschinen und Discovery-Systeme 2/2

Liebe Talia

Der zweite Teil der Suchmaschinen und Discovery-Systeme startete gleich mit einer Gruppenübung. Diese befasste sich erneut mit VuFind und behandelte die Datenintegration. Da diese Vorlesung wie alle anderen remote stattfand, wurde die Gruppenarbeit erledigt, indem ein Gruppenmitglied den Bildschirm teilte und für die anderen mitverfolgbar die Aufgaben bewältigte. Mir fiel die Ehre zu, die Arbeiten auszuführen. Dazu setzte der Dozent für beide Gruppen einen eigenen Server auf. Zuerst sollten wir über Putty den Zugriff herstellen. Wir hatten Putty bereits in anderen Modulen verwendet und ich hatte das Programm gerade geöffnet, als ein Mitstudent bemerkte, dass das Ganze auch einfach in der Windows Powershell bedient werden konnte. So viel zur Verwendung von bereits Gelerntem. 

Die Aufgabe bestand zunächst darin, die bereits vorhandenen Testdaten zu löschen. Ich tat dies, konnte aber nicht nachvollziehen, ob da tatsächlich etwas passiert war. Der Rest der Übung funktionierte aber korrekt, deshalb gehe ich davon aus, dass die Commands das taten, was ich wollte. In einem nächsten Schritt wurden Daten aus vier Quellen importiert: Aus Koha, ArchivesSpace, DSpace und DOAJ. Damit man die Quelle der Datensätze später in VuFind besser nachvollziehen konnte, sollte jedem Datensatz vor dem Import (aber nach dem Laden) eine Institution zugewiesen werden. Dies konnte man durch bearbeiten der marc_local.properties Datei erreichen. Ich legte für jeden Datensatz eine andere Institution fest. In VuFind waren dann 1001 Einträge vorhanden, aber alle unter der default Institution. Wir probierten eine Weile herum, bis uns der Dozent darauf aufmerksam machte, dass die ganze Datei auskommentiert war und daher keine Wirkung zeigte. Nach Entkommentieren der Institution und erneutem Import konnten wir dann 1 Koha und 1000 OpenRefine Einträge finden, mit der von uns festgelegten Institution. Zwischendurch hatte ich ein wenig mit der Navigation zu kämpfen, ich kam nicht mehr aus dem Bearbeitungsmodus heraus. Als der Dozent dann erklärte, dass das ^-Zeichen für Ctrl steht, funktionierte dann alles korrekt. Noch nie habe ich mich so nach einer Mausnavigation gesehnt.

Der Import von den ArchivesSpace und DSpace Daten schlug übrigens fehl, wie in der Aufgabenstellung schon vorgemerkt. Als Fehlermeldung wurde angezeigt, dass das Feld «id» fehlen würde. Die Daten konnten deshalb nicht korrekt eingelesen werden.

Als zweiter Teil sollten wir nun VuFind selbst konfigurieren. Dazu wurde die config-Datei von VuFind bearbeitet. Man kann dabei die globale oder die lokale Datei bearbeiten. Der Unterschied dabei ist, dass die Globale regelmässig zurückgesetzt wird, die Lokale nicht. Wir fanden uns nur schwer zurecht, schafften es aber dennoch, eine Suchfunktion zu löschen und «Spanisch» bei der Sprachauswahl in «blabla» umzubenennen. Wenn das mal kein Erfolg ist.

Der Dozent zeigte uns danach ein paar Discovery-Systeme, wie sie im echten Leben verwendet werden. So beispielsweise das der Herzogin-Anna-Amalia-Bibliothek. Dieses System basiert auf VuFind, arbeitet aber mit anderen Systemen zusammen. Zum Schluss wurde uns noch ein Marktüberblich über verwendete Discovery-Systeme gegeben, beispielsweise über den Marktführer Primo von Ex Libris. 

Nach dieser sehr interaktiven Lektion nähern wir uns rapide dem Ende des Moduls. Ich bin gespannt, was uns zum Schluss noch erwartet!

Bis dann,
Lukas






