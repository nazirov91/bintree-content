# Set Operations
Frequently we need to combine sets to produce new sets. For instance, say we have a set of animals that live under the water and another set of animals that live on the ground. We could make a new set of animals that can live both, under water and on the ground. Or a set of animals that cannot live in water. 
There are a few ways of combining sets.

## 1. Intersections
Let's say that we have a set *A* = {1,2,3} and set *B* = {2,3,4}. **Intersection** of *A* and *B* is a new set - {2,3}. In other words, intersection is a set of objects that are present in multiple sets at the same time. In symbols, intersection is denoted by $\cap$.  
* {1,2,3} $\cap$ {2,3,4} = {2,3}

If two sets have no simultaneous objects, they are said to be **disjoint sets**.

Sometimes it is helpful to visualize sets to get the big picture. To do that we implement **Venn Diagrams**.
![Venn diagram - intersection](https://upload.wikimedia.org/wikipedia/commons/6/6d/Venn_A_intersect_B.svg)

In the picture above, blue-purple area represents the intersection of *A* and *B*.

## 2. Union

Union is similar to intersection. With a small difference. When we want to represent the **union of *A* and *B*, we take all the elements that appear in at least on of the sets.** It does not include the duplicates. It is denoted by the symbol $\cup$. 
 In fancy symbols, we define it as the following:
$$A \cup B \thickspace is \thickspace \{e| \space e \in A \lor e \in B \}$$

For instance.
* {1,2,3,4} $\cup$ {3,5,6,7} = {1,2,3,4,5,6,7}


![Venn diagram - Union](https://upload.wikimedia.org/wikipedia/commons/2/2f/Venn_A_union_B.png)


