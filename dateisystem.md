# Linux - Umgang mit Dateisystemen - Aufgabenheft

## Zielsetzung

* Um Ordner und Dateien auf Festplatten abzuspeichern ist es notwendig, die Festplatte in einen Zustand zu bringen der dies ermöglicht. Ziel dieses Themas ist es, dich mit dem „Umgang mit Dateisystemen“ vertraut zu machen.


## Hilfsmittel

* [selflinux - Zugriffe auf Laufwerke](http://www.selflinux.org/selflinux/html/zugriff_auf_laufwerke.html)
* [selflinux - Das Partitionieren](http://www.selflinux.org/selflinux/html/partitionieren.html)
* [selflinux - Journaling Dateisysteme](http://www.selflinux.org/selflinux/html/dateisysteme_journaling.html)
* [ubuntuusers - Dateisystem](https://wiki.ubuntuusers.de/Dateisystem/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit den wichtigsten Begriffen des Linux-Dateisystems vertraut.
* Erstelle eine Übersicht mit den bekanntesten Festplattentypen. Nenne ihre Vor- und Nachteile.
* Nenne die wichtigsten Dateisysteme die in Linux eingesetzt werden und dessen Eigenschaften. (Unterteilt in: Linux-Dateisysteme, Dateisysteme anderer Betriebssysteme, CD-ROM- und DVD-Dateisysteme, Netzwerk-
dateisysteme, Sonstige)

### Vertiefung

* Erläutere was es mit den Begriffen Journaling und Swapping auf sich hat.
* Finde heraus wie die I-Nodes eines Linux-Dateisystems aussehen. Erstelle eine kleine Übersicht dazu.
* Notiere dir die Kommandos mit denen du die Festplatte partitionieren und mit denen du ein Dateisystem erstellen kannst. Probiere die Kommandos mit allen wichtigen Optionen aus.
* Fülle folgende Tabelle aus. (Kommandos für die Dateisystemintegrität)

 Kommando | Beschreibung | Beispiel
----------|--------------|---------
 du       |              |
 df       |              |
 fsck     |              |
 e2fsck   |              |
 mke2fs   |              |
 debugfs  |              |
 dumpe2fs |              |
 tune2fs  |              |
 badblocks|              |


* Erkläre wie die Partitionierung eines Linux-Dateisystems aussehen sollte. Welche Verzeichnisse sollten ihre eigene Parition bzw. eigene Festplatte bekommen ?
* Mache dich mit folgenden Kommandos und Dateien vertraut. mount, umount, /etc/fstab, /etc/mtab
* Definiere das Format der Datei /etc/fstab. Welche Optionen mit welcher
Wirkung können in /etc/fstab eingesetzt werden ? (siehe Ausgabe von "cat /etc/fstab")
* Erarbeite einen Plan um eine zweite Festplatte zu installieren und bei Linux auch zu nutzen. Notiere die notwendigen Schritte, Befehle bzw. Dateiveränderungen.

## Mögliche Testfragen

* Du möchtest die Daten einer neuen CD lesen. Welche Schritte machst du um das zu erreichen ?
* Du möchtest erfahren welche Dateisysteme gerade gemountet sind. Was gibst du in den Computer ein ?
* Wann setzt du das Kommando mke2fs ein ?
* Du möchtest herausfinden auf welcher deiner Festplatten noch genug Speicher ist um ein Abbild einer DVD zu machen. Welches Kommando kann dir dabei helfen ?
* Was bedeutet der Begriff Swapping ?
* Welche Dateisysteme enthalten keine Journal-Funktion ? ext2, ext3, ReiserFS, iso9660
* Wozu ist die Datei /etc/fstab vorhanden ?
* Du vermutest einen Fehler in deinem Dateisystem. Was machst du ?

