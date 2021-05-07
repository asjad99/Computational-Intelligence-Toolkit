


---------------
### Object-Oriented programming in Java


---------------
### Prolog


---------------

### The functional paradigm (using LISP)

lisp-practice-tasks

1. Define a function (even <list>) which returns the subset (a list) of even numbers contained in a given numeric, possibly nested list. The result must maintain the order of the even numbers as they appeared in the original list. Example: (even ‘(1 2 (3 4) -4)) returns (2 4 -4).
2. Write a function (OccurencesInTree <n> <tree>) which counts the number of occurrences of the value <n> in a numeric tree. Use a breadth first approach when traversing the tree.
Example: (OccurencesInTree 3 ‘(((1)(2))(5)(3)((8)3)) returns 2.
3. Define a function (SumIfNot <list1> <list2>) which returns the sum of all elements in list2 that do not appear in list1. Both lists may be nested lists. Example: (SumIfNot ‘(1 8 (2)) ‘(1 (3 (5)) 7 9)) returns 24.



For learning more see: http://www.paulgraham.com/rootsoflisp.html

----------------------
#### Map Reduce 

Resilient Distributed Datasets (RDD) are the primary abstraction in Spark – a fault-tolerant collection of elements that can be operated on in parallel
two types of operations on RDDs: 
transformations and actions
Examples of transformations include map,filter, group by and join operations
transformations are lazy (not computed immediately) 
Actions include count,collect, save etc.
 The transformed RDD gets recomputed when an action is run on it (default) •
 however, an RDD can be persisted into storage in memory or disk
![image](https://user-images.githubusercontent.com/3470924/117436155-016d3980-af72-11eb-876d-06d45e03ae90.png)


----------------------
### Concurrent Programming




-----------------------------

### RESOURCES: 

[Paradigms of Artificial Intelligence Programming](https://github.com/norvig/paip-lisp)
SCIP
[Six programming paradigms that will change how you think about coding](https://www.ybrikman.com/writing/2014/04/09/six-programming-paradigms-that-will/)
[The paradigms of programming](https://blog.acolyer.org/2018/01/29/the-paradigms-of-programming/)
