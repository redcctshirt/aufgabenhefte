# Umgang mit bash - Aufgabenheft

## Zielsetzung

* Die bekannteste Shell unter Linux ist bash. Ziel ist es, dich mit der bash-Shell vertraut zu machen.


## Hilfsmittel

* [selflinux - Einführung in die Bourne Again Shell (bash)](http://www.selflinux.org/selflinux/html/bash_basic.html)
* [Bash](https://wiki.ubuntuusers.de/Bash)
* [Einführung in die Bash](http://bin-bash.de/)
* [Die GNU-Shell Bash (Bourne Again SHell)](https://www-user.tu-chemnitz.de/~hot/unix_linux_werkzeugkasten/bash.html)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit der angegebenen Dokumentation von bash vertraut.
* Erläutere in kurzen Stichpunkten den Begriff shell.
* Liste die bekanntesten Shells auf. Probiere einige Shells aus. Erkläre mit
welcher Shell du arbeitest und warum.


### Vertiefung

* Erkläre wie man die Standard-Shell einstellen kann und was in der Datei
/etc/shells steht.
* Informiere dich über die Dateien /etc/inputrc und ~/.inputrc. Was kannst
du in diesen Dateien einstellen ?
* Entwerfe eine Übersicht mit den wichtigsten Shell-Variablen. Beschreibe
wie man sie anzeigen lassen kann und wie man sie verändern kann.
* Erläutere wie man den Eingabe-Prompt verändern kann. Notiere dir alle
möglichen Einstellungsmöglichkeiten.
* Erstelle eine Tabelle mit den wichtigsten bash-Tastenkürzel. (Tastenkür-
zel, Funktion)
* Erläutere den Einsatz der Kommandos alias und unalias.
* Erkläre wie man alle Arten der Ein- und Ausgabeumleitungen durchführt.
Welche Vorteile hat eine Umleitung ?
* Fülle folgende Tabelle aus. (Kommandoausführung)

    Eingabe                | Beschreibung | Beispiel    
    Kommando1; Kommando2   |              |    
    Kommando1 && Kommando2 |              |    
    Kommando1 || Kommando2 |              |    
    Kommando &             |              |    
    Kommando1 & Kommando2  |              |    
    (Kommando1 ; Kommando2)|              |    

* Definiere den Begriff Kommandosubstitution. Wie leitest du eine Kom-
mandosubstitution ein ?


## Mögliche Testfragen

* Wie findest du heraus welche Shell bei dir gerade aktiv ist ?
* Du möchtest das Datum und Zeit in deiner Eingabe-Prompt erscheinen.
Was machst du ?
* Was bewirkt das Tastenkürzel Strg+L ?
* Du musst bei einer Wartungsarbeit immer das gleiche lange Kommando
eingeben. Wie kannst du das Tippen vereinfachen ?
* Was passiert bei folgendem Kommando ? ls -l /etc | tee ergebnis
* Du möchtest das ein zweiter Befehl durchgeführt wird wenn der erste
Befehl erfolgreich war. Was gibst du in den PC ein ?
* Was wird beim folgendem Kommando ausgegeben ? echo $[3+4]+$[2]
* Mit welchem Kommando listest du alle Shell-Variablen auf ?
* Was steht in der Shell-Variable PWD ?


