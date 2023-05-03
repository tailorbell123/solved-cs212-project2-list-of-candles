Download Link: https://assignmentchef.com/product/solved-cs212-project2-list-of-candles
<br>



Create a class called <em>CandleNode</em> which has fields for the <em>data</em> (a Candle) and <em>next</em> (CandleNode) instance variables. Include a one-argument constructor which takes a Candle as a parameter. (For hints, see the PowerPoint on “Static vs. Dynamic Structures”.)

public CandleNode (Candle c) {  . . }

The instance variables should have protected access. There will not be any get and set methods for the two instance variables.

Create an abstract linked list class called <em>CandleList. </em> This should be a linked list with head node as described in lecture. Modify it so that the data type in the nodes is <em>Candle</em>. The no-argument constructor should create an empty list with <em>first</em> and <em>last</em> pointing to an empty head node, and <em>length</em> equal to zero. Include an append method in this class.

Create two more linked list classes that extend the abstract class <em>CandleList</em>: One called

<em>UnsortedCandleList</em> and one called <em>SortedCandleList</em>, each with appropriate no-argument constructors. Each of these classes should have a method called <em>add(Candle) </em>that will add a new node to the list. In the case of the UnsortedCandleList it will add it to the end of the list by calling the append method in the super class. In the case of the SortedCandleList it will insert the node in the proper position to keep the list sorted.

Instantiate two linked lists, and for every Candle read from the file, add it to the unsorted and sorted lists using the <em>add</em> method. You will end up with the first list having the Candles from the input file in the order they were read, and in the second list the Candles will be in sorted order. Display the unsorted and sorted Candles in the GUI just as in project 1.


