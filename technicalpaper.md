# JAVASCRIPT

The most popular lightweight, compiled and interpreted programming language is JavaScript (JS). It is applicable to both client-side and server-side developments. JavaScript is also referred to as a web page scripting language.


**There are two ways to add JavaScript to your HTML file:**

1.Internal Javascript

2.External Javascript



## Data Types in Javascript

### 1.String

```
let Name  = "Gautam" ;

let profile = "Software Engneer" ;

```

### 2.Number


```
let length  = 5 ;

let height = 6.1;
```


### 3.Bigint

All integers in JavaScript are kept in a 64-bit floating-point representation.

JavaScript A new datatype called BigInt (2020) can be used to store integer values that are too large to fit into a regular JavaScript Number.

```
let num = BigInt("987654321123456789112233445566");
```

### 4.Boolean

```
let flag = true;

let status = false ;

```

### 5.Undefined

A variable in JavaScript has the value undefined if it doesn't have a value.


```
let balance ;

let email : undefined ;

```

### 6.Null

The null value  is intentional absence of any object value.

### 7.Symbol

Symbols are a brand-new primitive type that was added in ES6. Symbols serve as entirely distinct markers. The factory function Symbol(), which yields a Symbol, can be used to construct them just like their basic equivalents (Number, String, and Boolean).

```
const logo = symbol("YOUTUBE") ;

const icon = symbol("YAHOO") ;

const key = symbol("GOOGLE") ;

```

### 8.Object

The object data type can contain:

1. An object

 ```
const player = {name :"Gautam" , id : 07 , skill : "Sniper"} ;

 ```


2. An array

```
const names = {rohit,virat,sachin,Dinesh} ;

```

3. A date

```
const date = new Date("2023-02-14");

```



## Datastructures 

At a high level, data structures are methods for organising and storing data that make it simpler to access, alter, and navigate. The methods used to collect data, the methods we can use to access it, and the connections between data are all governed by data structures.


### **1.Array**

An array is the most fundamental type of data structure, storing information in memory for later use. Each array contains a predetermined number of cells, and each cell has a matching numerical index that is used to pick the data within it. 

Resource & Examples : [Array Examples](https://www.w3schools.com/js/js_arrays.asp)



### **2.Stack**

List-like data are stored in stacks, a type of data structure. They only permit adding and removing components using a LIFO pattern (last in, first out).

Resource & Examples : [Stack Examples](https://www.programiz.com/javascript/examples/stack)



### **3.Queues**

Stacks and queues both function very similarly, but the add and remove patterns of the elements in a queue are different. Only a FIFO (first in, first out) pattern is permitted in queues. 

Resource & Examples : [Queue Examples](https://www.programiz.com/javascript/examples/queue)


### **4.Linked List**

A type of data structure called a linked list is used to store values as a list of items. Each value in the list is referred to as a node, and each node is linked to the value that comes after it in the list (or null if the element is the last in the list) by a pointer.

Resource & Examples :[Linked List Examples](https://www.geeksforgeeks.org/implementation-linkedlist-javascript/)



### **5.HashMaps** 

Hash tables are a sophisticated data structure that can effectively store and retrieve specific information in large quantities. Key/value pairs, where the "key" is a searched string and the "value" is the data paired with that key, are the foundation of this data structure.

Resource & Examples : [HashMap/HashTable Examples](https://www.freecodecamp.org/news/javascript-hash-table-associative-array-hashing-in-js/)

### **6.Trees**

Another relation-based data structure that excels at displaying hierarchical structures is the tree. Similar to a linked list, nodes include both data elements and pointers indicating how they relate to other nearby nodes.

Resource & Examples :[Trees Examples](https://adrianmejia.com/data-structures-for-beginners-trees-binary-search-tree-tutorial/)


### **7.Graphs**

A relation-based data structure that is useful for storing relationships that resemble a web is a graph. Each node, or vertex, as they are known in graphs, has a name (such as A, B, or C), a value that is contained therein, and a list of connections (referred to as edges) it has with other vertices.

Resource & Examples : [Graphs Examples](https://www.geeksforgeeks.org/implementation-graph-javascript/)




# Refrences

 

 1) [Developer Mozilla](https://developer.mozilla.org)

2) [W3schools](https://www.w3schools.com)

3) [Educative.i0](https://www.educative.io/blog/javascript-data-structures)


4) [frrecodecamp](https://www.freecodecamp.org/news/data-structures-in-javascript-with-examples)




