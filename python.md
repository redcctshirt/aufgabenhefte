# Python - Aufgabenheft

## Zielsetzung

* Ziel dieses Themas ist es, dich mit "Python" vertraut zu machen.


## Hilfsmittel

* [python.org](https://www.python.org/)
* [Schlangengerangel für Kinder](http://python-verband.org/informieren/news/schlangengerangel-fuer-kinder)
* [Wikipedia - Python](https://de.wikipedia.org/wiki/Python_%28Programmiersprache%29)
* Befehle unter Linux: man kommando, info kommando


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

    > > > print “u“ in “Junior-Pingos“
    > > > print “Junior-“ + “Pingos“
    > > > print 3 * “Junior\n“
    > > > print JP = “Junior-Pingos“
    > > > print JP[0]
    > > > print JP[-5]
    > > > print “B“+ JP[8:12]
    > > > print len(JP)


* Schreibe auf was es mit dem folgenden Befehl auf sich hat. Liste weitere Codes zur String-Formatierung auf. Welche Bedeutung haben sie ?

    > > > print “%d kl%xine %s“ % (10, 14, ’Junior-Pingos’)


* Erläutere was Listen sind und warum sie eingesetzt werden. Wie wird eine Variable mit dem Datentyp Liste definiert ? Schreibe ein Beispiel zur leeren Liste, eine Liste mit 3 unterschiedlichen Werten und eine verschachtelte Liste mit jeweils 2 Werten.
* Mache dich mit den Operationen für Listen vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

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


* Erkläre warum bei der Sortierung ’Junior-Pingos’ vor ’grosse’ gelandet ist. J kommt im Alphabet doch eigentlich nach g.
* Definiere den Datentyp Dictionary. Nenne die Unterschiede zwischen Listen und Dictionaries. Erkläre wann es vorteilhaft ist Listen einzusetzen und wann es besser ist Dictionaries in Betracht zu ziehen.
* Wie wird eine Variable mit dem Datentyp Dictionary definiert ? Schreibe ein Beispiel zur leeren Dictionary, eine Dictionary mit 2 Elementen und eine verschachtelte Dictionary mit jeweils 2 Elementen.
* Mache dich mit den Operationen für Dictionaries vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

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


* Definiere den Datentyp Tupel. Erkläre warum es noch zusätzlich den Datentyp Tupel gibt obwohl es schon Listen gibt.
* Wie wird eine Variable mit dem Datentyp Tupel definiert ? Schreibe ein Beispiel zur leeren Tupel, eine Tupel mit 3 unterschiedlichen Werten und eine verschachtelte Tupel mit jeweils 2 Werten.
* Mache dich mit den Operationen für Tupels vertraut. Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

    > > > JPtupel = (0, 5, 10, 15)
    > > > print JPtupel[1:3]
    > > > len(JPtupel)
    > > > print JPtupel + (20, 25)
    > > > print JPtupel * 2
    > > > print 5 in JPtupel
    > > > max(JPtupel)
    > > > min(JPtupel)


* Definiere den Datentyp Dateien. Mache dich mit den Dateioperationen vertraut. Erstelle eine Liste mit allen Modi die beim Dateiöffnen verwendet werden können.
* Starte den interaktiven Interpreter indem du python eingibst. Gib folgende Ausdrücke ein und erläutere was passiert.

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


## Mögliche Testfragen


