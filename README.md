# Google-maps-style-route-planning-algorithm.
implementation of a "Google-maps" style route planning algorithm.
In this project I will use A* search to implement a "Google-maps" style route planning algorithm.
The Map objects have two properties you will want to use to implement A* search: intersections and roads


#### student_code.py file contains the code for implementing A* search
#### helpers.py contains the code for graph network representation.
#### test.py --> test all the edge cases for the code.
#### ipnyb file contains the line by line execution of all code with explantion.

### Intersections
The intersections are represented as a dictionary.

### Below represents adjacency the matrix which conatains the linkage of roads to each node
map_40.roads:
[[36, 34, 31, 28, 17],
 [35, 31, 27, 26, 25, 20, 18, 17, 15, 6],
 [39, 36, 21, 19, 9, 7, 4],
 [35, 20, 15, 11, 6],
 [39, 36, 21, 19, 9, 7, 2],
 [32, 16, 14],................]
 
 ### Below represents the coordinates of individual nodes
 map_40.intersections :  
 {0: [0.7801603911549438, 0.49474860768712914],
 1: [0.5249831588690298, 0.14953665513987202],
 2: [0.8085335344099086, 0.7696330846542071],
 3: [0.2599134798656856, 0.14485659826020547],
 4: [0.7353838928272886, 0.8089961609345658],
 5: [0.09088671576431506, 0.7222846879290787],.......}
