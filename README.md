# studentrepository
This is my implementation of structure "quadtree"(Size 128x128).

A quadtree is a tree data structure in which each internal node has exactly four children. Quadtrees are the two-dimensional analog of octrees and are most often used to partition a two-dimensional space by recursively subdividing it into four quadrants or regions. The data associated with a leaf cell varies by application, but the leaf cell represents a "unit of interesting spatial information".

All forms of quadtrees share some common features:

1) They decompose space into adaptable cells
2) Each cell (or bucket) has a maximum capacity. When maximum capacity is reached, the bucket splits
3) The tree directory follows the spatial decomposition of the quadtree.

For deletion enter "delete x y 0"; x, y - coordinates point you want to delete
For addition enter "insert x y z"; x, y - coordinates point you want to add, z - value
For getting nearest some point enter "getnearest x y z"; x, y - coordinates point you want get near by, z - radius
For getting some point enter "get x y 0"; x, y - coordinates point you want to get

To exit enter "exit 0 0"
