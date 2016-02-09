# Linux - Protokollierung - Aufgabenheft

## Zielsetzung

* Auf einem System laufen, selbst wenn man momentan gerade nicht damit arbeitet, stets mehrere Dienste. Um einen ordungsgemäßen Betrieb zu gewährleisten muss das System überwacht, und auf Fehler reagiert werden. Meldungen die protokolliert werden können dabei helfen. Ziel dieses Themas ist es, dich mit der „Protokollierung“ vertraut zu machen.


## Hilfsmittel

* [selflinux - syslog](http://www.selflinux.org/selflinux/html/syslog.html)
* [Wikipedia - syslog](https://de.wikipedia.org/wiki/Syslog)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Nutze die angegebene Dokumentation um dich mit dem Dienst syslog vertraut zu machen.
* Mache dich mit der angegebenen Dokumentation folgender Kommandos vertraut. dmesg, logger, tail -f, logrotate
* Probiere die Kommandos mit den möglichen Optionen aus.


### Vertiefung

* Liste Vor- und Nachteile für folgende Protokollierungsstrategien auf. Nenne jeweils ein praktisches Beispiel.
  * Alle Protokolldaten sofort löschen
  * Protokolldaten werden nach einer kurzen Zeit gelöscht
  * Rotation der Protokolldaten, um sie länger behalten zu können
  * Protokolldaten werden komprimiert und auf einem anderen Datenträger gespeichert
* Erstelle eine Tabelle (Protokolldateien in /var/log) mit folgenden Spalten.

Logdatei | Programm das die Einträge macht | Inhalt
---------|---------------------------------|-------
         |                                 |
         |                                 |

* Erarbeite eine Übersicht mit allen Konfigurationsoptionen der Datei logrotate.conf.
* Erstelle selbst ein Skript um die Protokolldateien zu rotieren.
* Notiere dir alle Facilities, Levels und Aktionen der Konfigurationsdatei von syslog. Mache dir Stichpunkte zur jeweiligen Bedeutung.
* Schau dir das Abbild der Datei syslog.conf an und ekläre was die Angaben jeder Zeile bewirken.
* Nenne Vor- und Nachteile wenn ein zentraler Protokollieruns-Server in einem Netzwerk eingesetzt wird. Welche Möglichkeiten gibt es die Nachteile zu beseitigen ?
* Liste weitere Systemlogger auf. Liste Tools die genutzt werden um die Logdateien auszuwerten auf.
* Erkläre welche Informationen in den Feldern einer Zeile der Log-Datei /var/log/messages stecken.


## Mögliche Testfragen

* Was kannst du mit dem Befehl logger anstellen ?
* Mit welchem Befehl startest du syslogd neu ?
* Welches Programm macht Einträge in die Logdateien wtmp und lastlog ?
* Welche syslogd-Option und welcher Port ist für Remote-Logging notwendig ?
* Wie kannst du dir den Ablauf des Systemstarts nochmal genauer anschauen ?
* Du hast ein Skript erstellt das nach der Protokollierungsrotation ablaufen soll. Welche Option setzt du in der Datei logrotate.conf ein ?
* Welches Level von syslog hat die Bedeutung Panik-Situation ?
* Mit welcher Aktion legt man bei syslog.conf fest, dass die Meldung an einen anderen Host weitergegeben wird ?

