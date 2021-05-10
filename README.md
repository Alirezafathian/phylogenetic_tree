Neighbor Joining Method for Creating Phylogenetic Trees
==============================
![head](https://github.com/Alirezafathian/phylogenetic_tree/blob/master/fig/head.png) 

Scripts for building phylogenetic trees from a given distance matrix with neighbor joining method.

In <a href="https://github.com/Alirezafathian/phylogenetic_tree/blob/master/references/phylogenetic_tree.pdf">/references/phylogenetic_tree.pdf</a> you can find information about phylogenetic trees and neighbor joining method and see some examples of computing phylogenetic trees.

### Requirements
numpy,
math,
matplotlib


### Example

#### Input:

Distance Matrix
 
       [ 0,  A,  B,  C,  D,  E,  F]
       [ A,  0,  0,  0,  0,  0,  0]
       [ B,  5,  0,  0,  0,  0,  0]
       [ C,  4,  7,  0,  0,  0,  0]
       [ D,  7, 10,  7,  0,  0,  0]
       [ E,  6,  9,  6,  5,  0,  0]
       [ F,  8, 11,  8,  9,  8,  0]


### Output:

1. Newick Format:

	[  [[['E',2], ['D',3]], [ ['C',2], [['B',4], ['A',1]]]], ['F',5]  ]

2. Phylogenetic Tree:

![tree](https://github.com/Alirezafathian/phylogenetic_tree/blob/master/fig/sample_res.png)
 
	
