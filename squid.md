# Linux - Squid - Aufgabenheft

## Zielsetzung

* Jeder Administrator möchte das auch jeder im Netz Web-Zugang hat. Hier bietet sich ein Proxy-Server an. Squid ist ein Web-Proxy der oft zum Einsatz kommt. Ziel dieses Themas ist es, dich mit „Squid“ vertraut zu machen.


## Hilfsmittel

* [Squid - Administrationshandbuch zum Proxyserver](http://www.squid-handbuch.de/hb/)
* [Squid](http://www.squid-cache.org/)
* [selflinux - Der Web-Proxy Squid](http://www.selflinux.org/selflinux/html/squid.html)
* [ubuntuusers - Squid](https://wiki.ubuntuusers.de/Squid/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Forsche nach, was der Begriff Proxy bedeutet und wann ein Proxy-Server eingesetzt wird.
* Lese die angegebene Dokumentation und mache dir Notizen.
* Installiere selbst ein Squid-Proxy-Server und probiere alle wichtigen Konfigurationspunkte aus.
* Mache dich mit den Mustern der Log-Dateien vertraut.


### Vertiefung

* Installiere mögliche Hilfs-, Webfilter- und Managementprogramme. Erstelle eine Liste mit dessen Vor- und Nachteilen.
* Finde heraus welche weiteren Proxy-Server es gibt, auf welchen Betriebssystemen sie funktionsfähig sind und wann sie bevorzugt eingesetzt werden.
* Installiere mögliche Log-Datei-Analyseprogramme. Vergleiche sie in allen Kategorien und notiere dir die besten.
* Erstelle selbst ein Skript das eine Funktion eines Log-Datei-Analyseprogramms deckt. (z.B. eine Liste, welcher Benutzer hat wieviel Byte heruntergeladen)
* Soweit du mit einer Skript-Programmiersprache vertraut bist, erstelle ein CGI-Programm mit dem du den Benutzern Zugriff zum Proxy-Server erteilen oder verweigern kannst.


## Mögliche Testfragen

* Du hast einige Änderungen in der Konfigurationsdatei squid.conf durchgeführt. Wie schaffst du es das diese auch sofort zum Einsatz kommen ?
* Du hast eine Datei erstellt mit allen IP-Adressen die den Squid-Proxy-Server benutzen dürfen. Wie sehen die entsprechenden Einträge in der Konfigurationsdatei aus ?
* Mehrere Benutzer beschweren sich bei dir weil sie seit kurzem kein Zutritt zum Squid-Proxy-Server haben. Dir fällt ein das gerade eine neue Firewall eingeführt wurde. Was machst du ?
* Wie konfigurierst du den Webclient Firefox wenn der Squid-Proxy-Server genutzt werden soll ?
* In deinem Netzwerk wird ein Squid-Proxy-Server benutzt. Wie findest du heraus wieviel Benutzer die Webseite www.pingos.org besuchen ?

