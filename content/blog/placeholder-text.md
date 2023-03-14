+++
author = "Andres Garcia"
title = "What is a set?"
date = "2023-03-13"
description = "What are sets? Short description about sets. "
tags = [
    "basics",
    "math",
    "ml",
]
+++

### TL;DR 
- A set is an unordered collection of distinct objects
- Two sets are equal if they have exactly the same elements
- The size of a set is called cardinality; there exists finite and infinite sets
- A is a subset of B, if every element of A is also an element of B

>I am a set with no elements,
>Yet I am not empty.
>What am I?  
> Answer: A set.

## What is a set?
A set is a unordered collection of distinct objects.   
Objects in a set are also called members or elements.
```
N = {1,2,3,4,5} is a set of decimal digits 
``` 

Elements in a set can also be characterized by stating the property or properties they must have to be members of this set.  
```
N = {0, 2, 4, 6, 8} 
N = {x | x is an even integer and x <= 0 < 10}
``` 

Sets can contain seeminly unrelated elements.  
```
A = {l2, color, T, Orange}
``` 

## Cadinality of a set
Cardinality is the size of a set.  
A set contains its elements.  

Notation:  
    ∈ - belongs  
    ∉ - does not belong 

```
A ∈ {A, B, C}, A belings to the set
1 ∉ {0, 2, 3}, 1 does not belong to the set
```

If a set has a fininte number of elements, *n*, we say that a set has a cardinality of n.  
In other words, only finite sets can have a cardinality.  

Notation:  
    |S| - cadinality

```
S = {1, 2}  
|S| = 2, the cardinality of S is 2
```

Sets can contain other sets.  
Sets can be empty. The cardinality of an empty set is 0. 

Notation:  
    {} - empty set
```
|{}| = 0, the cardinality of the empty set is 0
```

***Important:***  because sets can contain other sets the cardinality of {{}} is 1. {{}} is a set containing 1 element which is an empty set.

## Equality
Sets are considered equal if they have exactly the same members. Order does not matter.
```
A = {1, 2, 3}
B = {3, 2, 1}
A = B, set A is equal to set B
```

## Subsets
A set A is called a subset of B if every elemet of A is also in B.  
B is the superset of A.  

Notation:  
    ⊆ - subset
	⊈ - not a subset
```
A = {1, 2} 
B = {2, 5}   
C = {1, 2, 3 ,4}  

A ⊆ C, A is a subset of B  
B ⊈ C, B is not a seubset of C
```  

***Note:*** an empty set is a subset of any set, including the empty set itself. Any set is a subset of itself. Also, an empty set is a proper subset of any set except for itself.
`{}⊆{}`, but `{}⊄{}`.

### What is a proper subset?
A is a proper subset of B if and only if every element of A is also an element of B, and there exist at least one element of B that is not in A.  

Notation:  
    ⊂ - proper subset  

```
A = {A, B}  
B = {A, B, C}  

A ⊂ B, proper subset
B ⊆ B, it is not a proper subset. 
```  

{{< css.inline >}}
<style>
.canon { background: white; width: 100%; height: auto; }
</style>
{{< /css.inline >}}
