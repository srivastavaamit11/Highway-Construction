# Highway-Construction
In this project we have tried to implement a solution for the Road Construction By taking into consideration of the traffic  and utilities.We also used Bankers algorithm to remove the hinderance caused due to unavailability of the resources.

# ALGORITHMS USED
1. DIJKSTRA ALGORITHM FOR FINDING SHORTEST PATH FOR ROADS
2. PRIORITY SCHEDULING WITHOUT PREEMPTION
3. BANKERS ALGORITHM TO GENERATE A SAFE SEQUENCE

# EXPLANATION
1. First we take inputs for the number of roads
2. Then we will take inputs for the formation of map in form of graph for all the different roads
3. Then based on the graph we will apply dijakstra algorithm and find the shortest distance possible between the desired cities
4. This distance is saved as a parameter of size for the roads
5. Also the route of the shortest path will be displayed
6. Then we read the utility, traffic and deadline for all the roads
7. Based on these inputs we check for clashing between the priorities
8. If present the clashing is handled
9. Then the required sequence is generated
10. Based on the sequence we find the waiting and completion times for the roads
11. Now we check if the roads can be completed within their allocated time
12. If deadline is crossed then an error message “DEADLINE NEEDS TO BE COMPROMISED IS DISPLAYED”
13. If dead line is not passed the generated sequence is displayed and we move to the second part of project
14. Here we read the number of resources needed for each road,maximum resources needed for each road, amount of resources allotted for each road, and available resources
15. Based on which a safe sequence is generated
16. If sequence is not generated then an error message is displayed
