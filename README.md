Neighbor Joining Method for Creating Phylogenetic Trees
==============================

Scripts for building phylogenetic trees from a given distance matrix with neighbor joining method.

In /phylogenetic_tree/references/phylogenetic_tree.pdf you can find information about phylogenetic trees and neighbor joining method and see some examples of computing phylogenetic trees.


Example:

Distance Matrix:
| 0 | A | B | C | D | E | F 
---|--- | --- | --- | --- |--- |--- 
 A | 0 | 0 | 0 | 0 | 0 | 0 
---|--- | --- | --- | --- |--- |--- 
 B | 5 | 0 | 0 | 0 | 0 | 0 


array([[ 0,  0,  0,  0,  0,  0],
       [ 5,  0,  0,  0,  0,  0],
       [ 4,  7,  0,  0,  0,  0],
       [ 7, 10,  7,  0,  0,  0],
       [ 6,  9,  6,  5,  0,  0],
       [ 8, 11,  8,  9,  8,  0]])

Newick Format:
[[[['E', 2.0], ['D', 3.0]], [['C', 2.0], [['B', 4.0], ['A', 1.0]]]], ['F', 5]]

Phylogenetic Tree:
	
