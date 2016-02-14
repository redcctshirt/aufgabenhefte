# Linux - Linux-Systemstart - Aufgabenheft

## Zielsetzung

* Wichtig für einen Systemadministrator ist es den Bootvorgang zu kennen und wie man ihn beeinflussen kann. Ziel dieses Themas ist es, dich mit dem „Linux-Systemstart“ vertraut zu machen.


## Hilfsmittel

* [ubuntuusers - Bootvorgang](https://wiki.ubuntuusers.de/Bootvorgang/)
* [ubuntuusers - Bootoptionen](https://wiki.ubuntuusers.de/Bootoptionen/)
* [ubuntuusers - Upstart](https://wiki.ubuntuusers.de/Upstart/)
* [ubuntuusers - systemd](https://wiki.ubuntuusers.de/systemd/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit der angegebenen Dokumentation des Starten und Herunterfahren von Linux vertraut.
* Mache dich mit den folgenden Kommandos vertraut und probiere sie aus. dmesg, init, telinit, halt, poweroff, poweron, reboot, shutdown
* Lies gründlich die Dokumentation der Programme grub, lilo und syslinux durch. Mache dir Stichpunkte zu allen wichtigen Fakten.


### Vertiefung

* Erkläre was das Wort Bootstrapping bedeutet.
* Zähle die Phasen eines Bootprozesses bei Linux auf. Was genau passiert in jeder Phase und wie hat der Administrator darauf Einfluss ?
* Erstelle eine Übersicht was es für Konfigurationsmöglichkeiten bei lilo, grub und syslinux gibt. Welche Optionen kann man direkt beim Booten verwenden und was bewirken sie ?
* Schreibe auf wie die Einstellungen bei lilo und grub aussehen würden wenn du einen Backup-Kernel hinzufügen würdest.
* Nenne Vorteile beim Multibooting. Wie würde die Konfiguration bei lilo und grub aussehen wenn es ein zweites Betriebssystem auf deiner Festplatte gibt ?
* Nenne wichtige Gründe warum man ein Linux-Betriebssystem nicht mit einem Knopfdruck ausschalten sollte.
* Nenne Unterschiede zwischen lilo, grub und syslinux.
* Nenne weitere Programme die dir dabei helfen die Runlevel-Skripts zu verwalten.
* Mache dich mit dem Programm loadlin.exe vertraut. Welche Schritte musst du durchgehen um Linux von DOS aus starten zu können ?
* Liste die Einstellungsmöglichkeiten in der Datei /etc/inittab auf. Welche Runlevels existieren in deiner Linux-Distribution ? (siehe Ausgabe von "cat /etc/inittab")
* Erkläre das Runlevel-Konzept deiner Linux-Distribution. Erstelle selbst ein Startup-Skript zu einem Dienst und füge es dem Runlevel 5 hinzu.

## Mögliche Testfragen

* Wie änderst du den Standard-Runlevel ?
* Mit welchem Kommando startest du den PC neu ?
* Mit welcher Anweisung fährst du den PC sofort herunter ?
* Du startest deinen PC neu. Als Bootmanager verwendest du lilo. Welche Option gibst du ein um im Einzelbenutzer-Modus zu booten ?
* Was passiert für gewöhnlich bei Runlevel 6 ?
* Die Wartezeit beim Bootmanager lilo soll 6 Sekunden betragen. Was gibst du in die Konfigurationsdatei ein ?
* Du hast bei der Konfigurationsdatei von lilo ein Backup-Kernel hinzugefügt. Beim PC-Neustart wird aber keine Änderung sichtbar. Woran könnte das liegen ?
* Du musst von der 5. Partition der 1. Festplatte booten. Was stimmt bei dieser grub-Konfiguration nicht ?

```
title linux
root (hd1,5)
kernel /boot/vmlinuz ro root=/dev/hda5 hdd=ide-scsi
initrd /boot/initrd.img
```

* Ein bestimmer Dienst lässt deinen PC beim booten immer wieder abstürzen. Du kommst nie zum einloggen. Was unternimmst du dagegen ?

