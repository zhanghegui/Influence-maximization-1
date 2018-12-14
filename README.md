# Influence-maximization
The project is trying to find the most influential group of nodes in a huge social network.（SUSTech AI lab3）
（1）In the ISE problem, I use both LT and IC models. The IC compares the randomly generated values of
the nodes with the values of the edges, and is
activated if it is less than the edge. The LT model
adds the adjacent edges of the node's activated parent
nodes, and if the weight value is greater than the
valve randomly generated by the node, the modified
node is activated. Both algorithms use breadth-first
search

（2）In the IMP question, I will calculate the greedy
algorithm based on the marginal benefit, and then
compare it with the greedy algorithm using the
CELF++ optimized algorithm