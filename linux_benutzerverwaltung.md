# Linux-Benutzerverwaltung - Aufgabenheft

## Zielsetzung

* Um Zugang zu einem Linux-Rechner zu erhalten, muß man ein Benutzerkonto auf dem Rechner besitzen. Einer der wichtigsten Aufgaben eines Administrators ist die Verwaltung von Benutzerkontos. Ziel dieses Themas ist es, dich mit der Benutzerverwaltung vertraut zu machen

## Hilfsmittel

* [selflinux - Benutzer](http://www.selflinux.org/selflinux/html/nutzer_unter_linux.html)
* [ubuntuusers - Benutzer](https://wiki.ubuntuusers.de/Benutzer_und_Gruppen/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit der angegebenen Dokumentation folgender Grundkommandos zur Benutzerverwaltung vertraut. useradd, userdel, usermod, groupadd, groupdel, groupmod, passwd, gpasswd
* Erarbeite die Muster folgender Dateien, in denen Daten über Benutzer und Gruppen gespeichert sind. /etc/passwd, /etc/shadow, /etc/group, /etc/gshadow
* Probiere die Grundkommandos mit allen Optionen aus und beobachte die Änderungen in den Konfigurationsdateien.


### Vertiefung

* Mache dich mit der angegebenen Dokumentation weiterer Kommandos zur Benutzerverwaltung vertraut. chage, chsh, chfn, newgrp, groups, id, pwck, grpck, pwconv, pwunconv, grpconv, grpunconv
* Finde heraus was folgende Kommandos bewirken und welche Informationen in den angegebenen Log-Dateien stecken. w, who, finger, last, lastlog, /var/run/utmp, /var/log/wtmp, /var/log/lastlog
* Erstelle Anweisungen die folgende Zeilen aus der Log-Datei /var/log/messages herausfiltern. Anmelden von Benutzern, Abmelden von Benutzern, fehlgeschlagenes Anmelden von Benutzern
* Installiere weitere Programme zur Benutzerverwaltung und probiere sie aus.
* Welche Dienste können ebenfalls zur Anlegung von Benutzerdaten genutzt werden ? Erstelle eine Liste mit sämtlichen Vor- und Nachteilen aller Möglichkeiten zur Benutzerverwaltung.

## Mögliche Testfragen

* Mit welchen Kommando überprüft man die Integrität der Passwort-Dateien ?
* Du möchtest Passwort-Dateien aus einem sehr alten Linux-Server bei deiner neuen Installation übernehmen. Welches Kommando wird dir die Aufgabe leichter machen.
* Was stimmt bei der Zeile aus /etc/passwd nicht ? root:x:0:0:Hans Muster,Administrator:/bin/bash:/root
* Welche Information kannst du aus dem 3. Feld der Datei /etc/shadow entnehmen.
* Lege ein neues Benutzerkonto mit dem Namen Paul an. Der Benutzer soll zur Gruppe Manager gehören und die Benutzeridentifikationsnummer 600 besitzen. Welche Anweisung gibst du in den Rechner ein ?
* Du möchtest erfahren welche Benutzer momentan angemeldet sind und wann sie sich eingeloggt haben. Welche Tools können dir dabei helfen ?

