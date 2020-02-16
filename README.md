ENG:
# double-linked-list

programming project

Only tested and designed for Windows, maybe works on other systems as well (not guarenteed)


Functionality:

In the first place you'll be asked how many elements your struct will have and you have to name them, this works with up to 15 entries.
There isn't a maximum of elements you can add according to the code but you might get trouble with the storage if you add to much.
But that shouldn't happen in common use.
Your element can be any string with up to 50 characters.
The way the whole code works is based on a double linked list which means that you not only have a list of structs but every element of the list includes a pointer to its previous and its next element allowing you add and delete elements at any point.Creating the first element at the start of the programm allows to set a fixed starting point not being touched or changed afterwards so the list wont get lost during the use of the programm.
In addition to this as a base we added ways to print and save the whole list, search for elements and finally sort by a user- choosen criteria.
Due to the shortage of the time sorting the elements will only sort them after its first character but will work with numbers and strings.
The maximum amount of lists you can sort is set to 50 but can be changed easily in the sort function. Also we faced an issue with reopening the saved file which we weren't able to fix in the short amount of time we had left. Acoording to that we deleted the function to read the file and you wont be able to find it in the code.

Developed by David Frank, Niklas Jahn and Paul Klauber 

DE:
#doppelt-verkettete-Liste

Getestet auf und designet für Windows, für eine Funktionalität mit anderen Betriebssytemen können wir nicht garantieren.

Funktionen:

Beim ersten Start des Programms wird der Benutzer aufgefordert die Anzahl an Elementen im Struct anzugeben und zu benennen, die maximale Anzahl liegt bei 15. Es existiert keine maximale Anzahl an Structs, jedoch sind bei einer zu hohen Anzahl Speicherprobleme nicht auszuschließen.
Bei normaler Benutzung sollte dies jedoch nicht eintreten.
Die Basis des Codes bildet eine doppelt-verkettete-Liste, welche neben den Structs zusätzlich noch einen Zeiger auf das vorherige als auch auf das nachfolgende Listenelement hat und so ermöglicht an jedem beliebigen Punkt neue Elemente einzufügen oder Elemente zu löschen.
Das Erstellen des ersten Elements sorgt für die Erstellung eines fixierten Startpunktes, welcher keine Strings enthält und während des gesamten Programms nicht wieder angerührt wird, um einen Verlust der Verkettung der Liste zu verhindern.
Zusätzliche Funktionen des Programms sind ausgeben und speichern der Liste, die Suche nach bestimmten Elementen und eine Möglichkeit nach einem vom Nutzer gewählten Kriterium zu sortieren.
Aufgrund der Knappheit der Zeit für das Projekt, findet die Sortierung nur nach dem ersten Elements des String statt funktioniert jedoch sowohl mit Zahlen als auch mit Buchstaben. Das Maximum an Elementen zum sortieren beläuft sich momentan auf 50, dies kann jedoch jederzeit innerhalb des Codes geändert werden.
Den selben Umständen geschuldet war es uns nicht mehr möglich das Einlesen der gespeicherten Datei zu realisieren, da wir hier auf einen Fehler stießen den wir nicht mehr reparieren konnten. Entsprechend wurde die Funktion zum Auslesen aus dem Programmcode entfernt.

Entwickelt von David Frank, Niklas Jahn und Paul Klauber
