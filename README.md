## lisp-practice-tasks

1. Define a function (even <list>) which returns the subset (a list) of even numbers contained in a given numeric, possibly nested list. The result must maintain the order of the even numbers as they appeared in the original list. Example: (even ‘(1 2 (3 4) -4)) returns (2 4 -4).
2. Write a function (OccurencesInTree <n> <tree>) which counts the number of occurrences of the value <n> in a numeric tree. Use a breadth first approach when traversing the tree.
Example: (OccurencesInTree 3 ‘(((1)(2))(5)(3)((8)3)) returns 2.
3. Define a function (SumIfNot <list1> <list2>) which returns the sum of all elements in list2 that do not appear in list1. Both lists may be nested lists. Example: (SumIfNot ‘(1 8 (2)) ‘(1 (3 (5)) 7 9)) returns 24.
