# Project Title

Implementation of Hashtables

## Description

In computing, a hash table, also known as hash map, is a data structure that implements an associative array or dictionary. It is an abstract data type that maps keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.

### Dependencies

* import random
* import string

### Installing

* Place Hashtables.ipynb file and names.txt in the same directory.

### Executing program

* Run the cell which contains all the functions. 
* Run the cell which extracts a random name from 1000 names.
* Then run the cell which contains the linear search. This will search for the name and return a (name, age) tuple. Check the time taken. It should be around 1.7s
* Run the cell which creates and populates the hashtable according to the hashfunction.
* Run the cell which contains htable_search. This will search for the name and return a (name, age) tuple. Check the time taken. It should be around 137ms. Which is drastically less than linear search.

## Authors

* Neil Chitre (https://github.com/NeilChitre2311)
* Madhav Ponnudurai
* Manish Vuppugandla 

## Version History

* 0.1
    * Initial Release
