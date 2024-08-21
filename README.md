# Informed and uninformed search
 
This project focuses on exploring a hypothetical CODVID outbreak in Texas, and how to mitigate it.

Two .csv files, representing the coordinates of cities in Texas (Nodes), and the distances between those cities (Edges), to create a Node edge graph of Texan cities, using networkx as out library of choice for that.
the graphs are then shown using matplotlib.

Imagining that the covid outbreak started from "Three Rivers", we implement an uninformed search algorithm for the virus to start spreading into every citiy in Texas. in this case, we use Breadth-First Search.

In the final stage of the project, we explore using an informed search algorithm, in this case A*, to find the optimal route to deliver vaccines between San Antonio and College Station.
