# studentrepository

This is my implementation of structure "quadtree" for college.

A quadtree is a tree data structure in which each internal node has exactly four children. Quadtrees are the two-dimensional analog of octrees and are most often used to partition a two-dimensional space by recursively subdividing it into four quadrants or regions. The data associated with a leaf cell varies by application, but the leaf cell represents a "unit of interesting spatial information".

All forms of quadtrees share some common features:

1) They decompose space into adaptable cells
2) Each cell (or bucket) has a maximum capacity. When maximum capacity is reached, the bucket splits
3) The tree directory follows the spatial decomposition of the quadtree.
