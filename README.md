Neighbor Joining Method for Creating Phylogenetic Trees
==============================

Scripts for building phylogenetic trees from a given distance matrix with neighbor joining method.

In /phylogenetic_tree/references/phylogenetic_tree.pdf you can find information about phylogenetic trees and neighbor joining method and see some examples of computing phylogenetic trees.


Example:

Distance Matrix:
 
       [ 0,  0,  0,  0,  0,  0]
       [ 5,  0,  0,  0,  0,  0]
       [ 4,  7,  0,  0,  0,  0]
       [ 7, 10,  7,  0,  0,  0]
       [ 6,  9,  6,  5,  0,  0]
       [ 8, 11,  8,  9,  8,  0]

Newick Format:
[  [  [['E',2], ['D',3]], [ ['C',2], [['B',4], ['A',1]] ]  ], ['F',5]  ]

Phylogenetic Tree:

![alt text](https://github.com/Alirezafathian/phylogenetic_tree/blob/master/fig/sample_res.png)
 
	
