miniature-nemesis
=================

Employment Test Series: Weighted Directed Acyclic Graph

1. Your program will create a weighted directed acyclic graph from a plain text file.

The text file will be in the following format:
vertex1 vertex2 edge_length

For example:
1 2 10
2 3 20
1 4 15
4 5 2
4 3 3

This file describes the image shown above. The first line describes an edge going from vertex 1 to vertex 2, with a length of 10.
The second line describes an edge going from vertex 2 to vertex 3, with a length of 20. Any edge not listed is assumed to not
exist. The vertex number is guaranteed to be less than 20.

Your program must read in the data file and find the longest and shortest paths starting from vertex 1.
In the above example, the longest path is 1 -> 2 -> 3, because the total edge length (10+20=30) is the greatest. The shortest
path is 1 -> 4 -> 5, because the total edge length (15+2=17) is the smallest. The end of the shortest path must end at an
endpoint (no outgoing edges).

Your program should print “30 17” as output, because those are the longest and shortest paths.