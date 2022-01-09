# Hash Tables

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Hash Table Usage*
- Hold unique values
- Dictionary
- Library

*Hash Code Examples*
***
Consider these examples running Seattle neighborhood names as Strings through two different hash functions.

Notice that although "Pioneer Square" and "Alki Beach" have different sum hashes they ultimately resolve to the same bucket index. Their hashes modulo buckets.length (to turn them into legitimate array indexes) are equal and they ultimately collide.

Calculating hashes and indexes by summing the ascii values of each character:
```
SUM HASHED: Pioneer Square = 1379
SUM HASHED: Alki Beach = 884
SUM HASHED: U District = 955

BUCKET SIZE=99
SUM INDEX: 1379 % 99 = 92
SUM INDEX:  884 % 99 = 92
SUM INDEX:  995 % 99 = 64
```

Calculating hashes and indexes by multiplying the ascii values of each character:
```
MULT HASHED: Pioneer Square = 599126016
MULT HASHED: Alki Beach = 1062823936
MULT HASHED: U District = 578867200

BUCKET SIZE=99
MULT INDEX:  599126016 % 99 = 93
MULT INDEX: 1062823936 % 99 = 31
MULT INDEX:  578867200 % 99 = 43
```

*Internal Methods*  
***
`Add()`  
When adding a new key/value pair to a hashtable:

<ol>
  <li>Send the key to the GetHash method.</li>
  <li>Once you determine the index of where it should be placed, go to that index.</li>
  <li>Check if something exists at that index already, if it doesn’t, add it with the key/value pair.</li>
  <li>If something does exist, add the new key/value pair to the data structure within that bucket.</li>
</ol>

`Find()`  
The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

`Contains()`  
The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

`GetHash()`  
The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

*Terms*
- Hash Table: 'a data structure that implements an associative array abstract data type, a structure that can map keys to values.'

*Resources*
- [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- [What is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
- [Basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/) 
- [Hash table wiki](https://en.wikipedia.org/wiki/Hash_table)
