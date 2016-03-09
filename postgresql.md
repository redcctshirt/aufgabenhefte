# PostgreSQL - Aufgabenheft

## Zielsetzung

* Datenbank Managementsysteme helfen, komplexe Aufgaben einfach zu lösen. PostgreSQL gilt als eins der zuverlässigsten und fortschrittlichsten OpenSource DBMS. Ziel dieses Themas ist es, dich mit "PostgreSQL" vertraut zu machen.

## Hilfsmittel

* [PostgreSQL](http://www.postgresql.de/)
* [selflinux - PostgreSQL](http://www.selflinux.org/selflinux/html/postgresql.html)
* [ubuntuusers.de - PostgreSQL](https://wiki.ubuntuusers.de/PostgreSQL/)
* [Einführung in SQL](https://de.wikibooks.org/wiki/Einf%C3%BChrung_in_SQL)

## Voraussetzungen

* Linux-Distribution
* Installation von PostgreSQL

## Aufgaben

### Erste Schritte

* Finde heraus was eine Datenbank ist und mache dich mit allen wichtigen Begriffen vertraut. Notiere die Begriffe und dessen Definition.
* Liste die meist eingesetzten Datenbanksysteme auf.
* Lese die angegebene Dokumentation der SQL-Sprache gewissenhaft durch und probiere die SQL-Kommandos aus.
* Notiere dir welche Anweisungen von der Installation bis zum Laufen von PostgreSQL eingegeben werden müssen.
* Erkläre was die Regressionstests sind.


### Vertiefung

* Mache dich mit der angegebenen Dokumentation folgender Kommandos vertraut. initdb, psql, pg_ctl, postmaster, createdb, dropdb
* Liste alle psql-Metabefehle auf und beschreibe die Funktionen.
* Nenne Fehler die beim postmaster- oder psql-Start auftreten können.
* Nenne die Umgebungsvariablen die es bei PostgreSQL gibt.
* Erarbeite alle Einstellungsmöglichkeiten in der Konfigurationdatei postgresql.conf. Erkläre folgende Konfigurationsparameter und gib dessen Standardeinstellung an. TCPIP_SOCKET, SYSLOG, LOG_TIMESTAMP, DEADLOCK_TIMEOUT, MAX_FSM_RELATIONS, VACUUM_MEM
* Erstelle eine Übersicht zu dem Muster der Datei pg_hba.conf.
* Forsche nach was die folgenden Kommandos bewirken. pg_dump, pg_dumpall, pg_restore. 
* Was muss man bei einer Datensicherung beachten ?
* Nenne die 3 Formate in der Datensicherung. Notiere die Unterschiede die du erkennst.
* Probiere COPY und \ copy in einer Datenbankverbindung aus. Wie würde das Kommando aussehen, wenn du die Datei /etc/passwd in eine Tabelle kopieren möchtest ?
* Erstelle, lösche und ändere ein Datenbankbenutzerkonto. Wie sehen die Anweisungen dazu aus ? Mache dich mit den Kommandos createuser und createdrop vertraut.
* Nenne kurz die Eigenschaften der BSD Lizenz.
* Schreibe den vollen Namen und die Bedeutung folgender Abkürzungen auf. DDL, DML, DCL
* Erkläre warum VACUUM regelmäßig eingesetzt wird.
* Mache dich mit dem Kommando vacuumdb vertraut.
* Erstelle eine Liste mit allen SQL-Standard Datentypen und dessen Eigenschaften. Welche zusätzlichen Datentypen gibt es bei PostgreSQL noch ?
* Mache dich mit CREATE DATABASE und CREATE TABLE vertraut. Erstelle eine neue Datenbank und füge eine Tabelle für einen Verein z.B., mit folgenden Feldern hinzu. (Name, Vorname, Straße, Ort, PLZ, Telefon, E-Mail, Gebdatum). Welche Datentypen würdest du einsetzen und wie sieht die SQL-Anweisung zur Tabellenerstellung aus wenn für Ort und PLZ Vorgabewerte definiert werden ? (z.B. meist vorhandene Ort und PLZ)
* Nenne die Systemspalten die automatisch vom System bei einer Tabelle hinzugefügt werden.
* Finde heraus wie die SQL-Anweisungen INSERT, UPDATE und DELETE angewendet werden. Füge in deine neue Tabelle 10 Datensätze ein. (manchmal gleiche, manchmal unterschiedliche Werte)
* Mache dich mit dem SELECT-Kommando vertraut. Erstelle eine Übersicht mit allen Klauseln und dessen Funktion. Lasse 3 Datensätze ab dem Datensatz 4, mit nur den Spalten Name und Vorname anzeigen.
* Erkläre was eine Sicht ist und was sie für Vorteile hat. Erzeuge eine Sicht in der alle Vereinsmitglieder aus einem Ort zusammengefasst werden.
* Mache dich mit der SQL-Anweisung ALTER TABLE vertraut. Füge ein weiteres Feld in deine Tabelle ein das das Alter angibt.
* Stelle dir eine Übersicht mit allen arithmetischen Funktionen und Operatoren zusammen. Probiere alle Funktionen und Operatoren aus.
* Stelle ebenfalls eine Übersicht mit allen String-Funktionen und den Operatoren ||, ũnd LIKE. Lasse alle E-Mails eines bestimmen FreeMail Anbieters anzeigen.
* Um was anzugeben werden folgende Zeit-Funktionen eingesetzt ? age, current_date, current_timestamp, current_time, extract, to_char
* Ermittle mit einer Zeitfunktion das Alter der Vereinsmitglieder und trage es in das jeweilige Feld ein. Welche weiteren Systeminformationsfunktionen gibt es sonst noch ?
* Notiere dir alle Aggregate-Funktionen und dessen Einsatz. Ermittle in deiner Vereins-Tabelle das Durchschnittsalter, den Ältesten und den Jüngsten.
* Mache dich mit den SQL-Kommandos GRANT und REVOKE vertraut. Erzeuge neue Datenbankbenutzer und füge sie einer neuen Gruppe hinzu. Diese Gruppe darf nur SELECT in der Vereinstabelle benutzen. Wie sehen die entsprechenden Anweisungen dazu aus ?
* Erkläre kurz wie und wozu man eine Sequenz und ein Index erstellt.
* Beschreibe kurz wann ein Rule und ein Trigger eingesetzt wird.
* Nenne die Vorteile eines Schemas und den Einsatz eines Cursors.
* Notiere die möglichen Isolationsgrade einer Transaktion die existieren. Welche kommen in PostgreSQL zum Einsatz und welche Unterschiede gibt es ? Wie führst du eine Transaktion durch ?


## Mögliche Testfragen

* Unter welchen Lizenz steht PostgreSQL ?
* Was bedeutet die Abkürzung DML ?
* Welche Option musst du bei der Installation (./configure) angeben um das Verzeichnis für die Konfigurationsdateien zu bestimmen ?
* Mit welcher Anweisung startest du den PostgreSQL-Server neu ?
* Mit welchem psql-Metabefehl listest du alle vorhandenen Tabellen auf ?
* Was bedeutet folgender Fehler beim Start von postmaster ? FATAL: StreamServerPort: bind() failed: Address already in use Is another postmaster already running on port 5432 ? If not, wait a few seconds an retry.
* Du möchtest das jeder SQL-Befehl in die Log-Datei eingetragen wird. Was machst du ?
* Welche Softwarepakete sind zur Installation von PostgreSQL erforderlich ?
* Du merkst das nach vielen Veränderungen in der Datenbank, die Reaktionszeit sehr langsam geworden ist. Welche Möglichkeiten zur Verbesserung hast du ?
* Du möchtest einen Datenbankbenutzer löschen, welchen Befehl gibst du ein ?
* Was ist eine temporäre Tabelle ?
* Wann ist die Systemspalte oid in einer Tabelle nicht vorhanden ?
* Du möchtest alle Einträge der Spalte Betrag mit dem Wert 10 in Wert 12 umwandeln. Wie sieht die Anweisung dazu aus ?
* Du möchtest alle gleichen Einträge der Spalte Stadt gruppieren und herausfinden welcher Wert der Spalte Temp der jeweiligen Gruppe der größte ist. Wie machst du das ?
* Siehe dir die folgenden 2 Ausgaben an und überlege welche SQL-Anweisung zur Veränderung durchgeführt wurde.

Name   | Vorname | Spitzname | Gebdatum
-------|---------|-----------|-----------
Muster | Peter   | Sokrates  | 20.04.1967
Müller | Ines    | Platon    | 03.01.1972


Name   | Vorname | Nickname  | Gebdatum
-------|---------|-----------|-----------
Muster | Peter   | Sokrates  | 20.04.1967
Müller | Ines    | Platon    | 03.01.1972


* Welches Ergebnis kommt bei folgender Anweisung heraus ? SELECT 1 « 4;
* Du willst die Anzahl der Zeichen in einer Zeichenkette herausfinden. Was tippst du in den Computer ein ?
* Von welchem Befehl kommt folgende Ausgabe ? PostgreSQL 7.3devel on i586-pc-linux-gnu, compiled by GCC 2.96
* Du möchtest allen Benutzern den Befehl SELECT erlauben. Was machst du ?
* Welches der folgenden Funktionen ist eine Sequenzfunktion ? nextval, forwardval, next, lseg, npoints

