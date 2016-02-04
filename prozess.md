# Linux - Prozesssteuerung - Aufgabenheft

## Zielsetzung

* Linux ist ein Multitasking-Betriebssystem. Das heißt, es können mehrere Programme zur selben Zeit ablaufen. Wichtig ist es also die Kontrolle zu behalten und die Prozesse zu verwalten. Ziel dieses Themas ist es, dich mit der „Prozesssteuerung“ vertraut zu machen.


## Hilfsmittel

* [selflinux - Prozessverwaltung](http://www.selflinux.org/selflinux/html/prozessverwaltung.html)
* [ubuntuusers - Prozesssteuerung](https://wiki.ubuntuusers.de/Shell/Prozesssteuerung/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit der angegebenen Dokumentation folgender Grundkommandos zur Prozesssteuerung vertraut. ps, pstree, top, fuser, kill, killall, nice, renice
* Probiere die Grundkommandos mit allen wichtigen Optionen aus.
* Welche weiteren Programme zur Prozesssteuerung gibt es ? Installiere mögliche Programme und teste die Funktionen aus.


### Vertiefung

* Erkläre in kurzen Stichpunkten was folgende Tastenkombinationen bzw. Kommandos bewirken. Strg-Z, Strg-C, bg, fg, jobs, kommando &
* Notiere die Bedeutung folgender Begriffe und was sie dir verraten. PID, PPID, UID, EUID, GID, EGID
* Fülle folgende Tabelle mit möglichen Signalen aus. Probiere die Signale aus.
    
Nr | Name |Beschreibung
---|------|------------
1  |      |
   | INT  | 
3  |      |
9  |      |
   |      | Beenden durch Software (Standard)
   | STOP |
   | TSTP |
   | CONT |
   | WINCH|
   | USR1 |
   | USR2 |
 
* Verwende ps und top mit allen möglichen Optionen. Welche Optionen werden genutzt um alle laufenden Prozesse anzuzeigen ? Erkläre wann du eher top nutzt und wann eher ps.
* Erstelle eine Übersicht zum Prozessstatus. (Status, Bedeutung)
* Erkläre was für Werte in den jeweiligen Spalten der Ausgabe von "ps lax" angezeigt werden.
* Ermittle mit ps und einem Skript den gesamten RSS-Wert.
* Finde heraus welche Dateien angezeigt werden und welche Informationen du aus den Dateien herauslesen kannst, wenn du ls /proc/[pid] eingibst.


## Mögliche Testfragen

* Du möchtest dein Clean-Skript, was du gerade geschrieben hast, im Hintergrund laufen lassen. Was gibst du in den PC ein ?
* Was bedeutet die Abkürzung PPID ?
* Welches Signal sendet kill wenn kein bestimmtes Signal angegeben wurde ?
* Wenn du top eingibst wird bei dem Kommando kapmd in der Statusspalte der Buchstabe S angegeben. Was bedeutet das ?
* Welcher Prozess hat gänzlich den PID 1 ?
* Welche Information steckt in der Datei /proc/[pid] /cmdline ?
* Dein Programm was du gerade installiert hast, läuft zu langsam. Mit welchem Kommando erhöhst du die Priorität deines Programmes ?
* Du möchtest herausfinden welches Programm im Moment den Prozessor am meisten beansprucht. Welche Anweisung nutzt du dafür ?

