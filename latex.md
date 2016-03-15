# Latex - Aufgabenheft

## Zielsetzung

* Ziel dieses Themas ist es, dich mit "Latex" vertraut zu machen.


## Hilfsmittel

* [Deutschsprachige Anwendervereinigung TeX e.V.](http://www.dante.de)
* [Der Latex-Index](http://www.weinelt.de/latex/)
* [LaTeX-Kurs](http://lefti.amigager.de/latex/index.html)
* [Wikipedia - Latex](https://de.wikipedia.org/wiki/LaTeX)


## Voraussetzungen

* Latex


## Aufgaben

### Erste Schritte

* Liste die Möglichkeiten (Programme) auf die ein Benutzer hat um Dokumente (Briefe, Plakate, wissenschaftliche Texte, Zeitungen) zu erstellen.
* Erkläre in kurzen Stichpunkten was Latex ist. Nenne die wichtigsten Eigenschaften von Latex.

### Vertiefung

* Erläutere die Unterschiede zwischen Latex und den herkömmlichen Anwendungsprogrammen um Dokumente zu erstellen.
* Informiere dich über die Geschichte von Latex. Notiere dir die wichtigsten Fakten.
* Welche Dateiformate spielen bei Latex eine Rolle ? Nenne die Tools und Programme mit denen man diese Formate erstellen und anschauen kann. Schreibe jeweils ein Beispiel wie die Kommandos aussehen würden.
* Bei der Verarbeitung einer .tex Datei kann es dazu kommen das ein Fehler gefunden wird. Du hast dann folgende Möglichkeiten: (siehe unten) Was bewirken diese Eingaben ?
  * Enter
  * H, Enter
  * R, Enter
  * Q, Enter
  * x, Enter
* Bei dem Kommando pdflatex datei.tex werden ausser der Datei datei.pdf noch weitere Dateien erstellt. Nenne diese und wozu sie erzeugt wurden.
* Liste vorhandene grafische Benutzeroberflächen für Latex auf.
* Erwähne die formalen Details eines Latex-Dokuments. (Wie schreibt man Text ? Wie schreibt man Kommentare ? Wie führt man Befehle aus ?)
* Schreibe das Grobgerüst für einen deutschsprachigen Artikel auf. Erläutere die einzelnen Befehle.
* \documentclass Beschreibe die gängigsten Dokumenklassen und Dokumentklassenoptionen.
* \usepackage Beschreibe einige stark verbreitete Pakete die man zusätzlich einfügen kann.
* Erläutere mögliche Gliederungsbefehle für ein Latex-Dokument. (Teil, Kapitel, ...) Schreibe zur Übung ein Dokument in dem diese Gliederungsbefehle vorkommen.
* Notiere die Befehle die zur Gestaltung des Schriftbilds verwendet werden. (Schriftattribute, Schriftgrösse)
* Erstelle eine Tabelle mit den meist benutzten Sonderzeichen.

Sonderzeichen | Bedeutung | Darstellung von Sonderzeichen im Text
--------------|-----------|--------------------------------------
              |           |                                      
              |           |                                      


* Mache dich damit vertraut wie man Tabellen in Latex definiert. Füge die Tabelle mit den Sonderzeichen zweimal in ein Latex-Dokument ein. (mit tabbing und tabular)
* Informiere dich über die Formatierung von Aufzählungen. Was passiert bei Verschachtelungen ? Schreibe zwei Beispiele, einmal mit itemize und einmal mit enumerate.
* Untersuche die Befehle die notwendig sind um mehrspaltigen Text und Text in Rahmen und Boxen zu gestalten.
* Erstelle eine Übersicht mit den Befehlen die das Seitenformat (Layout) des Dokuments beeinflussen können.
* Erläutere die Seitestile die bei \pagestyle zum Einsatz kommen können.
* Erkläre die Formen die für die Seitenzahl zur Auswahl stehen. Welche Befehle werden zur Änderung der Seitenzahlform benutzt ?
* Schreibe ein Dokument in dem Kopfzeilen, Fussnoten und Randbemerkungen zum Vorschein kommen.
* Erläutere die Anwendung und den Zweck folgender Befehle: \label \pageref \ref
* Wenn man Bücher oder Hefte schreibt ist es ganz günstig ein Inhaltsverzeichnis einzufügen. Erkläre wie man das bewerkstelligen kann.
* Verwende Ausrichtungsbefehle um folgenden Text einmal rechtsbündig, einmal linksbündig und als letztes zentriert darzustellen. Text: Ich weiss nur das ich nichts weiss.
* Entwerfe eine Übersicht mit Befehlen die Abstände und Einzüge definieren können. (Neue Zeile, Neue Seite, Zeilenumbruch, Zeilenabstand, etc.)
* Beschreibe wozu es die Befehle \include \includeonly \input gibt.
* Lese in der Literatur nach wie man mathematische Formeln auf dem Dokument erscheinen lässt. Nimm dir ein Blatt aus deinem Mathe- oder Physik-Unterricht und schreibe drei komplexe Formeln in ein Latex-Dokument.
* Informiere dich wie man Grafiken bzw. Bilder mit einbauen kann. Entwerfe ein Zeitungsblatt mit Bildern, z.B. über das Thema Linux, und schreibe ein Latex-Dokument dazu. (Wenn dir selbst nichts einfällt, bilde ein vorhandenes Zeitungs- oder Buchblatt nach. Bilder müssen nicht die gleichen sein)
* Erkläre wie du es erreichst das du sich immer wiederholenden Text nur einmal schreiben brauchst.
* Erläutere was Makros sind und wie man sie im Latex-Dokument definiert bzw. einsetzt.


## Mögliche Testfragen

* Was ist Latex ?
* Welche Kennung haben Latex-Dateien ? (tex, div, ltx, wks, doc)
* Wenn ein Fehler bei Latex auftritt, wie beendest du Latex sofort ?
* Wie erzeugst du aus dem Latex-Dokument ein PDF-Dokument ?
* Du hast vor ein Buch zu schreiben. Welcher Texttyp bei dem Befehl \documentclass ist am günstigsten dafür ?
* Wie schaffst du es Zusatzpakete einzufügen die deutschen Text unterstützen ?
* Du möchtest das deine Überschrift fett und kursiv erscheint. Was machst du ?
* Folgende Zeile steht in deinem Latex-Dokument: {\huge Ganze 95% aller Computerbenutzer benutzen Linux.} Das Dokument sieht nicht so aus wie du es dir erhoffst hast. Warum ?
* Du möchtest ein Und-Zeichen (&) in dein Text mit rein bringen. Wie machst du das ?
* Wie leitet man eine Aufzählung ein ?
* Mit welchem Befehl kannst du einen Text in einen Rahmen darstellen ?
* Du hast gerade pdflatex doku.tex ausgeführt und schaust dir das PDF-Dokument an. Dir fällt auf das trotz keinem Fehler das Inhaltsverzeichnis nicht zu finden ist. Was unternimmst du dagegen ?
* Wann wird der Befehl \marginpar eingesetzt ?
* Mit welcher Anweisung fängt man eine neue Seite an ?
* Wie fügst du ein Bild in deinen Text mit ein ?


