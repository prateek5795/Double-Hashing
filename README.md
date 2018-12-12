# Double-Hashing

Implementation of data structures and algorithms  
Fall 2018  
Short Project 7: Comparison of hashing implementations  

Authors - Team SP7 2
- Prateek Sarna (pxs180012)
- Bharath Rudra (bxr180008)

Files Included
- DHDriver_DistinctElements.java
- DHDriver_partone.java
- DoubleHashing.java
- Timer.java

Task  
- Part One
  - Implement Cuckoo Hashing and compare its performance with Java's HashMap/HashSet on millions of operations: add, contains, and remove. 

- Part Two
  - Generate an array of random integers, and calculate how many distinct numbers it has:  static<T> int distinctElements(T[ ] arr) { ... } Compare running times of HashSet and your hashing implementation, for large n.
  
Methods
- add(): adds an element to the hashtable and returns true if found, otherwise false
- remove(): removes the element x from the table and returns the element if deleted, otherwise null  
- contains(): checks if element x is present in the hash table and returns true, if present, otherwise false  
- find(): method that checks for an element x in the table and returns an index for that element  
- rehash(): method to perform rehash of elements to increase the size of the hashTable  
- hashCode2(): method to find the second hash using the hash function2  
- showHashTable(): method to  print the hashTable elements  
- hash(): This function ensures that hashCodes that differ only by constant multiples at each bit position have a bounded number of collisions
