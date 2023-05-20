### Toolkit and Areas: 

- Artificial Intelligence: Principles and Techniques
- [Machine Learning](https://github.com/asjad99/Machine-Learning-GYM)
- Machine Learning with Graphs
- Probabilistic Graphical Models
- Decision Making Under Uncertainty
- Advanced Topics in Sequential Decision Making	
- [RL and Sequential Decision Making](https://github.com/asjad99/Reinforcement-Learning)
- [AGI and Accelerating Scientific Discovery](https://github.com/asjad99/AGI)
- [Programming Paradigms for AI](https://github.com/asjad99/programming-paradigms-)
- 	Natural Language Processing with Deep Learning(fast.ai)
- Deep Multi-Task and Meta Learning
- Probabilistic Programming and Models of Cognition
- AI and Healthcare

-----

### Artificial Intelligence: Principles and Techniques

We cover, 30,000 view of the whole field. Dynamic Programming, NNs. etc. 

AI can be viewed as a spectrum, covering low-level intelligence(e.g instantenous image classification) And high level intelligence (human thinking hard about the next chess move. It also covers specialized algorithms related to search problems, markov decision processes, adversarial games, constraint satisfaction problems, bayseian, high-level logic (all the rage in the 70s with SAT Solver).  


### Projects: 

- [GoG](https://github.com/asjad99/rosetta_stone) - A gametree search and SAT based decision making framework to acheive strategic resilience
- [Path-Finder](https://github.com/asjad99/Prolog) - Path finder prolog 
- [LISP_Basics](https://github.com/asjad99/programming-paradigms-/blob/main/practice_programs.lisp) - Lisp practice programs for learning basics 
- [Rock-Paper-Scissors](https://github.com/asjad99/Rock-Paper-Scissors-) - Hand detection gesture system written in LabView   
- [Robo-Soccor](https://github.com/asjad99/Robot-Soccer-) - Lego based Autonomous Robot Capable of playing soccer using a spray painted Squash ball.


### Machine Learning 

see Machine learning repo. for details

### Machine Learning and Graphs





Add More Intros here: 

https://ai.stanford.edu/stanford-ai-courses/





---------------


#### Programming Paradigms for AI

The first paradigm is a logic programming engine based on unification and
depth-first search. The second paradigm is imperative: the assert and retract operations which allow a program to add and remove program clauses. Prolog dates
from 1972, which makes it an old language. Recent developments in modeling languages based on advanced search algorithms advance both the logic programming
and imperative programming sides. Modern Prolog implementations have added
some of these advances, e.g., support for constraint programming and a module
system


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

Concurrency should not be confused with parallelism. Concurrency is a language
concept and parallelism is a hardware concept. Two parts are parallel if they execute
simultaneously on multiple processors. Concurrency and parallelism are orthogonal: it is
possible to run concurrent programs on a single processor (using preemptive scheduling
and time slices) and to run sequential programs on multiple processors (by parallelizing
the calculations).


-----------------------------

### RESOURCES: 
- [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
- [Paradigms of Artificial Intelligence Programming](https://github.com/norvig/paip-lisp)
- [SCIP](https://mitpress.mit.edu/sites/default/files/sicp/index.html)
- [Six programming paradigms that will change how you think about coding](https://www.ybrikman.com/writing/2014/04/09/six-programming-paradigms-that-will/)
- [The paradigms of programming](https://blog.acolyer.org/2018/01/29/the-paradigms-of-programming/)
- https://github.com/kbodurri

###  People: 

- https://homes.cs.washington.edu/~mernst/research/

 
 <img width="880" alt="Screen Shot 2021-05-07 at 10 38 22 pm" src="https://user-images.githubusercontent.com/3470924/117450732-f8d22e80-af84-11eb-9775-ac5017c0b4e0.png">

