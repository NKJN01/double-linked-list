# double-linked-list
programming project

Only tested and designed for Windows, maybe works on other systems as well (not guarenteed)


Functionality:

In the first place you'll be asked how many elements your struct will have and you have to name them, this works with up to 15 entries.
There isn't a maxium of lists you can add according to the code but you might get trouble with the storrage if you add to much.
But that shouldn't happen in common use.
Your element can be any string with up to 50 characters.
The way the whole code works is based on a double linked list wich means that you not only have a list of structs but every element of the list includes a pointer to its previous and its next element allowing you add and delete elements at any point.Creating the first element at the start of the programm allows to set a fixed starting point not being touched or changed afterward so the list wont get lost during the use of the programm.
In addition to this as a base we added ways to print and save the whole list, search for elements and finally sort by a user- choosen criteria.
Due to the shortage of the time sorting the elements will only sort them after its first character but will work with numbers and strings.
The maximum amount of lists you can sort is set to 50 but can be changed easily in the sort function.

developed by David Frank, Niklas Jahn and Paul Klauber 
