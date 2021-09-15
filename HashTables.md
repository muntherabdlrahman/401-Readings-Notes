# Hash Tables
![img](https://i.imgur.com/2ON8Kt5.jpeg)

## Terminology

## Hash

***an algorithm takes a string and converts it into a value that could be used for security or some other purpose in a hashtable, it is used to determine the index of the array*** 

## Buckets
![img](https://media.geeksforgeeks.org/wp-content/cdn-uploads/implementing-own-hash-table.png)
***contained in each index of the array of the hashtable***

> **Each index is a bucket**
>**index could potentially contain multiple key/value pairs if a collision occurs**


## Collisions

### what happens when more than one key gets hashed to the same location of the hashtable? 

***Hashing is implemented in two steps***
1. An element is converted into an integer by using a hash function.
1.1.   This element can be used as an index to store the original element, which falls into the hash table.
2. The element is stored in the hash table where it can be quickly retrieved using hashed key.
img
```
hash = hashfunc(key)
index = hash % array_size
```

### What are Hash Tables? 

***a data structure that utilizes key value pairsevery Node or Bucket has both a key, and a value basic idea of a hashtable is the ability to store the key and quickly retrieve the value through a hash***

***hash is the ability to encode the key that will eventually map to a specific location in the data structure, we can directly retrieve the value O(1) time complexity for lookups Internal Methods***


### Add()

1. send the key to the GetHash method
2. determine the index of where it should be placed
3. go to that index
4. Check if something exists at that index already
5. if it doesn’t, add it with the key/value pair.
6. else add the new key/value pair to the data structure within that bucket

### Find()
1. takes in a key
2. gets the Hash
3. goes to the index location specified

### Contains()
1. accept a key
2. return a boolean if that key exists inside the hashtable

### GetHash()
1. GetHash will accept a key as a string
2. conduct the hash
3. return the index of the array where the key/value should be placed