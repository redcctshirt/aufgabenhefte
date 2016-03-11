# Python - Aufgabenheft

## Zielsetzung

* Ziel dieses Themas ist es, dich mit "Python" vertraut zu machen.


## Hilfsmittel

* [python.org](https://www.python.org/)
* [Schlangengerangel für Kinder](http://python-verband.org/informieren/news/schlangengerangel-fuer-kinder)
* [Wikipedia - Python](https://de.wikipedia.org/wiki/Python_%28Programmiersprache%29)
* [wikibooks - Python unter Linux](https://de.wikibooks.org/wiki/Python_unter_Linux:_ALLES)


## Voraussetzungen

* Linux-Distribution
* Python


## Aufgaben

### Erste Schritte

* Mache dich mit dem Begriff Programmierung vertraut.
* Erstelle eine Übersicht mit Informationsquellen (Internetseiten etc.) für Python.

### Vertiefung

* Informiere dich über die Geschichte von Python. Schreibe dir die wichtigsten Fakten dazu auf.
* Nenne in kurzen Stichpunkten die Eigenschaften von Python.
* Zähle weitere bekannte Skriptsprachen außer Python auf.
* Notiere dir die Vor- und Nachteile einer Skriptsprache. In welchen Fällen wird eher eine Skriptsprache und welchen eher eine Compilersprache genutzt ?
* Nenne die drei Bereiche in die man ein Programm unterteilen kann.
* Forsche im Internet nach und finde Programme die in Python geschrieben wurden. Liste einige auf und nenne deren Aufgaben. Erkläre in welchem Bereich Python-Programme am meisten vertreten sind und wo sie ganz fehlen ?
* Liste den Ablauf einer Installation von Python auf. Erläutere kurz jeden Schritt.
* Welche Möglichkeiten stehen dir zur Verfügung um ein Python-Programm auszuführen ? Schreibe jeweils ein Beispiel.
* Erstelle eine Tabelle mit den wichtigsten Umgebungsvariablen von Python.

Umgebungsvariable | Beschreibung
------------------|-------------
                  |
                  |


* Ermittle alle Optionen des Python-Interpreters. Was bewirken die einzelnen Optionen ? Welche Version von Python nutzt du ?
* Wofür wird die Anweisung print in Python gebraucht ? Schreibe ein Python-Skript mit der Ausgabe Hallo Welt.
* Entwerfe ein paar Richtlinien, auf die du, wenn du in Zukunft ein paar umfangreichere Programme schreibst, ein Auge wirfst. Sie sollen dir und anderen helfen die Übersicht zu behalten.
* Erläutere kurz die Syntaxregeln von Python. (siehe: Kontrollfluß, Blöcke, Anweisungen, Kommentar, Leerraum)
* Nenne die Namensregeln von Python. Überzeuge dich von ihrer Gültigkeit indem du sie ausprobierst.
* Erkläre was eine Variable ist. Warum werden Variablen und nicht jeweils feste Werte eingesetzt ? Erläutere wie Variablen definiert und wie ihnen Werte zugewiesen werden. Schreibe ein paar Beispiele und probiere sie aus.
* Liste die Datentypen von Python auf. Beschreibe die Datentypen und gib jeweils zwei Beispiele.
* Ermittle wie numerische Werte aussehen können. Notiere jeweils zwei Beispiele.
* Erstelle eine Übersicht zu den Ausdrucksoperatoren von Python. (Operator, Bedeutung, Beispiel)
* Erstelle eine Tabelle mit allen numerischen Operationen.

Operation | Bedeutung | Beispiel
----------|-----------|---------
          |           |         
          |           |         


* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.
    ```
    > > > print 2 - 3 + 6
    > > > print 12 * 2 / 4
    > > > print 3 % 12
    > > > print -1 + 8 / 4
    > > > print 4 | 1
    > > > print 5 & 1
    > > > print 8 >> 2
    > > > print 8 << 2
    > > > print 2 ** 3
    > > > print int(2.33) * float(2)
    > > > print (2 >> 1) + (3 - 1) * int(4.45)
    ```

* Erläutere wann folgende Formen von String-Konstanten zum Einsatz kommen.
    ```
    “Junior-Pingo’s“
    ’Junior-Pingo“s’
    “““Junior-Pingos“““
    “Junior-Pingo“ “-“ “Pingos“
    r’Junior\n-Pingos’
    u’Junior-Pingos’
    ```


* Nenne die Escape-Codes die man in Strings einbauen kann und was sie bewirken.
* Erstelle eine Übersicht mit den Operationen die bei Strings angewandt werden können. (Operation, Beschreibung, Beispiel)
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.
    ```
    > > > print “u“ in “Junior-Pingos“
    > > > print “Junior-“ + “Pingos“
    > > > print 3 * “Junior\n“
    > > > print JP = “Junior-Pingos“
    > > > print JP[0]
    > > > print JP[-5]
    > > > print “B“+ JP[8:12]
    > > > print len(JP)
    ```


* Schreibe auf was es mit dem folgenden Befehl auf sich hat. Liste weitere Codes zur String-Formatierung auf. Welche Bedeutung haben sie ?
    ```
    > > > print “%d kl%xine %s“ % (10, 14, ’Junior-Pingos’)
    ```


* Erläutere was Listen sind und warum sie eingesetzt werden. Wie wird eine Variable mit dem Datentyp Liste definiert ? Schreibe ein Beispiel zur leeren Liste, eine Liste mit 3 unterschiedlichen Werten und eine verschachtelte Liste mit jeweils 2 Werten.
* Mache dich mit den Operationen für Listen vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.
    ```
    > > > JPlist = [10, “kleine“, “Junior-Pingos“]
    > > > print JPlist[1]
    > > > print JPlist[0:]
    > > > print len(JPlist)
    > > > print JPlist + JPlist
    > > > print JPlist * 3
    > > > print “kleine“ in JPlist
    > > > del JPlist[1]
    > > > JPlist[1] = “grosse“
    > > > JPlist.append(“Junior-Pingos“)
    > > > JPlist.reverse()
    > > > JPlist.index(10)
    > > > JPlist.insert(1, “kleine“)
    > > > JPlist.count(10)
    > > > JPlist.remove(“grosse“)
    > > > JPlist.sort()
    > > > print range(1,4)
    ```


* Erkläre warum bei der Sortierung ’Junior-Pingos’ vor ’grosse’ gelandet ist. J kommt im Alphabet doch eigentlich nach g.
* Definiere den Datentyp Dictionary. Nenne die Unterschiede zwischen Listen und Dictionaries. Erkläre wann es vorteilhaft ist Listen einzusetzen und wann es besser ist Dictionaries in Betracht zu ziehen.
* Wie wird eine Variable mit dem Datentyp Dictionary definiert ? Schreibe ein Beispiel zur leeren Dictionary, eine Dictionary mit 2 Elementen und eine verschachtelte Dictionary mit jeweils 2 Elementen.
* Mache dich mit den Operationen für Dictionaries vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.
    ```
    > > > JPdict = {junior’: 10, ’instructor’: 5}
    > > > print JPdict[’junior’]
    > > > JPdict.has_key(’junior’)
    > > > JPdict.keys()
    > > > JPdict.values()
    > > > JPdict.items()
    > > > JPdict.copy()
    > > > JPdict.get(’unbekannt’,20)
    > > > JPdict.setdefault(’unbekannt’,20)
    > > > del JPdict[’unbekannt’]
    > > > len(JPdict)
    > > > JPdict[’alle’] = 15
    > > > JPdict.clear()
    ```


* Definiere den Datentyp Tupel. Erkläre warum es noch zusätzlich den Datentyp Tupel gibt obwohl es schon Listen gibt.
* Wie wird eine Variable mit dem Datentyp Tupel definiert ? Schreibe ein Beispiel zur leeren Tupel, eine Tupel mit 3 unterschiedlichen Werten und eine verschachtelte Tupel mit jeweils 2 Werten.
* Mache dich mit den Operationen für Tupels vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.
    ```
    > > > JPtupel = (0, 5, 10, 15)
    > > > print JPtupel[1:3]
    > > > len(JPtupel)
    > > > print JPtupel + (20, 25)
    > > > print JPtupel * 2
    > > > print 5 in JPtupel
    > > > max(JPtupel)
    > > > min(JPtupel)
    ```


* Definiere den Datentyp Dateien. Mache dich mit den Dateioperationen vertraut. Erstelle eine Liste mit allen Modi die beim Dateiöffnen verwendet werden können.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > JPdatei = open(’JP’, ’w’)
    > > > JPdatei.write(’Hallo in der Welt der Python-Programmierung’)
    > > > JPdatei.close()
    > > > JPdatei = open(’JP’,’r’)
    > > > JPdatei.read() 
    > > > JPdatei.tell()
    > > > JPdatei.seek(0)
    > > > JPdatei.read(5)
    > > > JPdatei.fileno()
    > > > JPdatei.closed
    > > > JPdatei.mode
    > > > JPdatei.name
    > > > JPdatei.close()
    ```


* Mache dich mit der if-Anweisung vertraut. Wie können die Wahrheitstests aussehen und wann kommt die if-Anweisung zum Einsatz ?
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > Obst = {’Apfel’: 10, ’Birne’: 8, ’Pflaume’: 5}
    > > > if ’Apfel’ in Obst: print ’Es sind ’, Obst[’Apfel’], ’ Äpfel’
    ...
    > > > if Obst[’Apfel’] > 10: print ’Es sind mehr als 10 Äpfel’
    . . . elif Obst[’Apfel’] == 10: print ’Es sind genau 10 Äpfel’
    . . . else: print ’Es sind weniger als 10 Äpfel’
    ```


* Mache dich mit den for- und while-Schleifen vertraut. Erkläre den Unterschied und nenne Situationen in denen sie eingesetzt werden.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > a=0
    > > > while a < 5:
    . . . a=a+1
    . . . for i in range(6)
    . . .     print i*a
    . . .
    ```


* Schreibe die Anweisung für eine unendliche Schleife. Kann man eine unendliche Schleife gebrauchen ? Wenn ja warum.
* Erkläre wozu die Anweisungen break, continue und pass vorhanden sind.
* Schreibe eine Dictionary mit 5 Produkten (Name als key) und deren Preise aus dem Supermarkt. Gib zu jedem Produkt den MWST-Betrag aus.
* Errechne die Summe aller Preise und gib sie am Ende aus. Schreibe dazu ein Skript. (so kurz wie möglich)
* Beschreibe was eine Funktion ist und wann Funktionen eingesetzt werden.
* Erkläre was die Schlüsselwörter return und global in den Funktionen bewirken.
* Fülle folgende Tabelle aus. (Funktionsargumenten)

Syntax                   | Bedeutung | Funktionsaufruf - Beispiel
-------------------------|-----------|---------------------------
def funktion(name)       |           | funktion('paul')
def funktion(name=value) |           | 
def funktion(*name)      |           |
def funktion(**name)     |           |


* Schreibe eine Funktion die beliebig viele Argumente haben kann. Die Argumente sind numerische Werte und werden alle addiert. Das Ergebnis wird ausgegeben.
* Erweitere diese Funktion und ermittle zusätzlich jeweils den größten, den kleinsten und den Durchschnitts-Wert. Gib die Werte am Ende aus.
* Schreibe deine Funktion um und lass vom ersten Argument die Ausgabe bestimmen. Ist das erste Argument das Wort ’sum’ wird summiert, beim Wort ’max’ wird der größte Wert ermittelt, beim Wort ’min’ wird der minimale Wert ausgegeben und beim Wort ’dw’ wird der Durchschnittswert ausgegeben. Standard ist ’sum’. Beispiel Aufruf: funktion(’max’, 2,3,8,4,6) Ausgabe: 8
* Mache dich mit den eingebauten Funktionen bei Python vertraut. Probiere die Funktionen aus und erläutere jeweils die Aufgabe. Schreibe zu jeder Funktion ein Beispiel und was dabei raus kommt.
abs, chr, cmp, float, hex, int, len, long, list, max, min, oct, ord, pow, range, round, str, tuple, unichr, unicode, input
* Erkläre was ein Modul ist und wozu es gebraucht wird.
* Mache dich mit den Anweisungen import, from und reload vertraut. Welche zwei Möglichkeiten hast du ein Modul zu laden ? Wie startest du jeweils eine Funktion aus dem Modul ?
* Schreibe in deinen Lieblingseditor ein Python-Skript. Lade das Modul string. Wandle alle Buchstaben der Zeichenkette ’Junior-Pingos’ in Großbuchstaben und in Kleinbuchstaben um. (lower(str), upper(str))
* Mache dich mit den Anweisungen try, except, raise und finally vertraut. Beschreibe die Funktionen der Anweisungen.
* Schreibe folgendes Skript in deinem Lieblingseditor. Probiere das Skript mit folgenden Eingabe-Werten aus und erläutere was passiert. (1,2,0)

    ```
    #!/usr/bin/python
    a = input(’Gib eine Zahl (0 bis 10) ein ! : ’)
    try: print ’10 / ’, a, ’ = ’, 10/a
    except: print ’10 ist nicht durch 0 teilbar’
    ```


* Erstelle eine Übersicht zu den Funktionen und Variablen vom Modul sys. Erkläre das Verhalten der Funktionen und schreibe jeweils ein Beispiel.
* Schreibe folgendes Skript in deinem Lieblingseditor. Erläutere was in den einzelnen Zeilen passiert.

    ```
    #!/usr/bin/python
    import sys
    dict = {’-v’: ’Version 1.0’, ’-n’: ’10’}
    print dict[sys.argv[1]]
    ```


* Schreibe ein Skript namens sysinfo.py in deinem Lieblingseditor. Folgende Optionen sollten Auskunft geben. Es soll möglich sein auch mehrere Optionen gleichzeitig anzugeben.    
-c Anzeige des Python-Interpreter Copyright    
-m max. positive Integer-Wert    
-p Import-Suchpfad für Module    
-f Plattform auf dem Python läuft    
-v Python-Interpreter-Version    
* Erstelle eine Übersicht zu den Funktionen und Variablen vom Modul string. Erkläre das Verhalten der Funktionen und schreibe jeweils ein Beispiel.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > import string
    > > > string.find(’10 kleine Junior-Pingos’,’Ju’)
    > > > string.replace(’10 kleine Junior-Pingos’,’kleine’,’grosse’)
    > > > string.center(’Junior-Pingos’,6)
    > > > string.join([’10’,’20’,’ab’],’*’)
    ```


* Schreibe ein Skript namens findstr.py in deinem Lieblingseditor. Die Option -f gibt eine Textdatei an und die Option -s gibt die gesuchte Zeichenkette an. Die Zeichenkette wird in der Datei gesucht, sobald sie gefunden wird wird die Zeilennummer und der Zeileninhalt ausgegeben. Die Zeichenkette in der Zeile wird markiert indem jeder Buchstabe in ein Großbuchstabe umgewandelt wird.
* Erstelle eine Übersicht zu den Funktionen und Variablen der Module os und os.path. Erkläre das Verhalten der Funktionen und schreibe jeweils ein Beispiel.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > import os
    > > > os.system(’ls -l’)
    > > > os.environ
    > > > os.getcwd()
    > > > os.getuid()
    ```


* Schreibe ein Skript namens ls.py in deinem Lieblingseditor. Mit ls.py soll der Inhalt des aktuellen Verzeichnisses angezeigt werden. Die Verzeichnisse werden mit einem d vor dem Verzeichnissnamen gekennzeichnet. Außerdem wird die Größe der Dateien angezeigt. Die Dateiausgabe erfolgt sortiert. Als erstes wird die größte Datei angezeigt und als letztes die kleinste Datei.
* Erstelle eine Übersicht zu den Funktionen und Variablen vom Modul math. Erkläre das Verhalten der Funktionen und schreibe jeweils ein Beispiel.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    ```
    > > > import math
    > > > math.pi
    > > > math.floor(10.10)
    > > > math.sqrt(9)
    > > > math.sin(1)
    ```


* Um eine Lösung für eine Matheaufgabe zu finden sind manchmal viele Schritte nötig. Schreibe zwei Skripts mit Beispielen indem Matheaufgaben automatisiert werden so das man nur noch Eingaben machen muß und am Ende kommt die Lösung raus.
* Erstelle eine Übersicht zu den Funktionen und Variablen vom Modul time. Erkläre das Verhalten der Funktionen und schreibe jeweils ein Beispiel.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgene Ausdrücke ein und erläutere was passiert.

    ```
    > > > import time
    > > > time.clock()
    > > > time.time()
    > > > time.tzname
    > > > time.altzone
    ```


* Schreibe ein Skript namens uhr.py in deinem Lieblingseditor. Es soll jeweils im Sekundentakt die Uhrzeit an ein und derselben Stelle angezeigt werden. Abgebrochen wird mit Strg+C.
* Welche weiteren Module gibt es und in welchen Fällen werden sie eingesetzt ?

Tipps:

Solltest du die Möglichkeit haben (eigener Webserver, Webspace-Anbieter mit Python im Internet) dynamische Webseiten mit Python zu gestalten, schau dir das Modul cgi genauer an. Versuche ein Counter und ein Minigästebuch zu schreiben. Wenn du Python bis hierhin ganz gut verstanden hast, ist es soweit sich langsam an OOP heranzutasten. Eine Stärke von Python ist die Unterstützung der objektorientierten Programmierung.


## Mögliche Testfragen

* Was ist Python eigentlich ?
* Wer ist der Erfinder von Python ?
* An welchem Dateiende sind Python-Programme zu erkennen ?
* Wie heißt der Interpreter mit dem ein Python-Programm gestartet wird ?
* Was bewirkt die Option -V des Interpreters ?
* Was für Werte findest du in der Umgebungsvariable PYTHONPATH ?
* Welche der folgenden Aussagen stimmt nicht ?
  * Python ist kostenlos und portable.
  * Python ist nicht kombinierbar.
  * Python ist einfach anzuwenden und kann man schnell lernen.
  * Python ist objektorientiert.
* Was kommt beim folgendem Skript zur Ausgabe ?

    ```
    #!/usr/bin/python
    print “Hallo“ “Welt“
    ```


* Was kommt als Ergebnis bei diesen Anweisungen raus ?

    ```
    #!/usr/bin/python
    a = (1,2,5,7)
    #b=1
    print b + len(a) + a[-1]
    ```


* Was für eine Datentyp hat die Variable a ?
   
    ```
    a = {}
    ```


* Was erscheint bei folgender Anweisung ?

    ```
    print 3 % 2
    ```


* Du möchtest das der Escape-Code bei der Ausgabe nicht gewertet wird. Was machst du ?

    ```
    print ’Junior-Pingos\n 10’
    ```


* Durch welche Buchstaben ersetzt du jeweils _ damit die Aussage stimmt `

    ```
    print ’Hexwert von %_ ist %_ ’ % (16,16)
    ```


* Was kommt bei den folgenden Anweisungen raus ?
    
    ```
    liste = [0,2,4,6]
    print liste.reverse()
    ```


* Mit welcher Operation kannst du ein Objekt an das Ende einer Liste anfügen ?
* Mit welcher Operation listest du alle Werte einer Dictionary auf ?
* Was wird bei diesem Skript auf dem Bildschirm erscheinen ?

    ```
    dict = {’Junior’:10, ’Instructor’: 5}
    if dict.has_key(’junior’): print ’Ja’
    else: print ’Nein’
    ```


* Was passiert bei diesen Anweisungen am Ende ?

    ```
    t = (1,2,3,4)
    t[4] = 5
    ```


* Du möchtest den Inhalt der Datei index.html einlesen und ausgeben. Wie siehst die erste Anweisung bei dieser Aufgabe aus ?
* Du möchtest die aktuelle Position in deiner geöffneten Datei wissen. Was machst du ?
* Was kommt bei folgender Anweisung am Ende raus ?

    ```
    print int(float(4) + 0.5) >> 1
    ```


* Mit welchem Schlüsselwort wird eine Funktion definiert ?
* Du merkst das dein Programm immer eine NullDivision durchführt und dann abstürzt. Was kannst du dagegen machen ?
* Was kommt bei folgendem Skript am Ende raus ?

    ```
    for i in range(0,8,2): a += i
    print a
    ```


* Dein Freund hat folgendes Skript geschrieben und meint es funktioniert nicht. Er bittet dich um Hilfe. Was stimmt hier nicht ?

    ```
    import sys
    dict = {’-n’: 20,’-o’: ’result.txt’}
    print dict[argv[1]]
    ```

* Du möchtest die Suchpfade für die Module anschauen. Welches Modul und welche Anweisung nutzt du ?
* Dein String sieht folgendermaßen aus: ’   JuNioR-PinGoS    ’. Dich stören die Leerzeichen an beiden Enden und du möchtest das alles in Kleinbuchstaben geschrieben wird. Was unternimmst du ?
* Du möchtest in deinem Skript den Zugriffsmodus und den Eigentümer einer Datei ändern. Welches Modul importierst du und welche Funktionen nutzt du ?
* Du schreibst gerade ein Skript das Log-Dateien erstellt. Du möchtest bei jedem Eintrag die aktuelle Zeit angeben. Was machst du ?



