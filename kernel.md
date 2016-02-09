# Linux - Umgang mit dem Kernel - Aufgabenheft

## Zielsetzung

* Der Kernel ist das Herz einer Linux-Distribution. Er verwaltet alle Betriebsmittel eines Computers. Ziel dieses Themas ist es, dich mit dem „Kernel “ vertraut zu machen.


## Hilfsmittel

* [selflinux - kernel](http://www.selflinux.org/selflinux/html/kernel.html)
* [selflinux - Bibliotheken](http://www.selflinux.org/selflinux/html/bibliotheken.html)
* [ubuntuusers - Kernel](https://wiki.ubuntuusers.de/Kernel/)
* Befehle unter Linux: man kommando, info kommando


## Voraussetzungen

* Linux-Distribution


## Aufgaben

### Erste Schritte

* Mache dich mit der angegebenen Dokumentation des Kernel und der Modulverwaltung vertraut.
* Mache dich mit der angegebenen Dokumentation der Bibliothek vertraut.
* Informiere dich über die Geschichte des Kernels.
* Erkläre den Aufbau der Kernel-Versionsnummer und nenne die aktuelle Kernelausgabe.

### Vertiefung

* Nenne in kurzen Stichpunkten was für Aufgaben ein Kernel hat.
* Zähle die Vorteile bei einem Kernel mit bzw. ohne Modulen auf.
* Fülle folgende Tabelle aus. (Kernel-Parameter) Wenn du ein Kernel-Paramter ändern möchtest, wie machst du das ? Schreibe zwei Beispiele auf.

 Datei                      | Standard-Wert | Bedeutung
----------------------------|---------------|----------
/proc/sys/fs/               |               |
file-max                    |               |
inode-max                   |               |
/proc/sys/net/ipv4/         |               |
ip_forward                  |               |
icmp_echo_ignore_all        |               |
icmp_echo_ignore_broadcasts |               |
/proc/sys/kernel/           |               |
ctrl-alt-del                |               |
domainname                  |               |
hostname                    |               |
osrelease                   |               |
ostype                      |               |
pid_max                     |               |
shmall                      |               |
shmmax                      |               |
version                     |               |
/proc/sys/dev/cdrom/        |               |
autoeject                   |               |

* Erkläre wozu das Kommando sysctl bereit steht und wann man die Datei /etc/sysctl.conf modifiziert.
* Erstelle eine Übersicht welche Schritte man gehen muss bis man einen neuen angepassten Kernel nutzen kann. Erkläre was die einzelnen Kommandos bewirken.
* Liste auf welche Konfigurationsoptionen die Bootmanager lilo und grub an den Kernel weitergeben können. Was bedeuten diese Optionen ?
* Erkläre den Begriff shared libraries. Nenne Vorteile die es bei Programmen mit statisch bzw. dynamisch gelinkten Libraries gibt.
* Nenne Funktionen der Kommandos ldd und ldconfig. In welchen Verzeichnissen werden Bibliotheken gespeichert ?
* Finde heraus welche Kommandos bei der Modulverwaltung zum Einsatz kommen. Liste alle Kommandos und deren Funktionen auf.
* Erkläre die möglichen Anweisungen in der Datei /etc/modules.conf oder auch /etc/modprobe.conf. 


## Mögliche Testfragen

* Mit welchem Kommando listest du alle Bibliotheken auf die das Programm /bin/mv braucht ?
* Was bedeutet die Kernel-Versionsnummer 2.5.1 ?
* Welches Programm erzeugt die Datei /etc/ld.so.cache ?
* Du möchtest die maximale Anzahl der geöffneten Dateien pro Prozess erhöhen. Was machst du ?
* Du möchtest wissen welche Module gerade im Kernel integriert sind. Welche Anweisung gibst du in den Computer ein ?
* Um den Kernel zu konfigurieren hast du mehrere Möglichkeiten. Welche gehört nicht dazu ? make config, make configure, make menuconfig, make xconfig
* Du hast selbst zum ersten mal ein Kernel konfiguriert und kompiliert. Beim Neustart geht es nun nicht mehr weiter und es kommt immer wieder zum Absturz. Was machst du beim nächsten mal anders ?


