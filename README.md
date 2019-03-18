# craft-code
I use this to thing some question about the algorithms for the match
# I use this to think some ruals to get the right answer about the network

1. find every non-direction map and get the minst tree of it

2.1 if the number of maps is 1, then run all the car across the minst tree, return
2.2 the number of maps is more than 1:
  find every direction map and find whether there are circles in it
  find all the circles, if there is a circle and two point in the circle has the same map, then del the edge
  if the circle is a must, then we kill one edge and run the remained, then run the remained car
  


2. add the edge of direction to the map, one of the most import thing,(may be the only one) is that 
the drection edges have no circle. if it has circles, we must think of someway to deal with it.

kill the edges that make the circle achieve. 
