An implementation of the Red-Black Self Balancing Binary Search Tree.

An explanation of this data structure is given on [Wikipedia](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree):

>In computer science, a red–black tree is a kind of self-balancing binary search tree. 
>Each node stores an extra bit representing "color" ("red" or "black"), used to ensure that the tree remains balanced during insertions and deletions.

>When the tree is modified, the new tree is rearranged and "repainted" to restore the coloring properties that constrain how unbalanced the tree can 
>become in the worst case. The properties are designed such that this rearranging and recoloring can be performed efficiently.

>The re-balancing is not perfect, but guarantees searching in O(log n) time, where n is the number of nodes of the tree. The insertion and deletion 
>operations, along with the tree rearrangement and recoloring, are also performed in O(log n) time.

This particular implementation is incredibly verbose, not to mention has flaws. It is intended to serve as resume source value, and not as
a legitimate tool. I may remake it later so that it is also the latter.
