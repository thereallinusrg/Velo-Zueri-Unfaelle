How do we weight the edges?
-	edge with no/few accidents gets weight 1, edge with highest accidents gets 10
-	edge with low percentage of sever accidents gets weight 1, edge with high percentage of sever accidents gets weight 10
-	length of edge needs to be included as well – otherwise the safest route might end up being much longer than the shortest    and that’s not really of interest either in the end.. ideally you want to find a compromise between time and danger
-> all factors aggregated represent the true weight of an edge
-> as accidents are more frequent at certain hours of the day, time also needs to be included in the weighting – here I’m a little lost as how to implement the time

The weight can best be used as a length of the edge e.g., travels from A to B goes along 4 edges with weights 3,4,5 & 7, aggregating in a total weight/length of 19.


Most common approach to find weighted paths along a network is the Dijkstra’s Algorithm