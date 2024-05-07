# Overview
this is a project for ece297 in uni of toronto. in a team of three, we built a map that focuses on tourism with a developed navigation system, using c++ and css for the ui. we have four milestones

m1: This milestone focuses on using and extending an application programming interface (API).
We have written a library called libstreetsdatabase that allows you to query geographic
information database files for cities. This API consists of two pieces, each provided by a
different header file. StreetsDatabaseAPI.h provides a higher level interface to structured street
and intersection data; you will mostly use functions from this header file. OSMDatabaseAPI.h
allows you to query lower level OpenStreetMap data on individual geographic points; you
will only need to use this API for two functions in this milestone.

m2: In this milestone you will use a graphics library called EZGL to visualize the
map, and you will add functions to find elements in the map and display detailed information
about them. While there are many graphics libraries, almost all use similar conventions, so
learning EZGL will also give you experience that is very useful in working with any graphics
library in the future.

m3: In this milestone you will extend your code to find good travel routes between two points
embedded in a graph. Algorithms to find paths in graphs are important in a very wide range
of areas, including GIS applications like yours, integrated circuit and printed circuit board
design, networking / internet packet routing, and even marketing through social media.

m4: In this milestone you will find a path through your map that has multiple stops, so that you
can find a good route for a courier company driver who has multiple deliveries to make, the travelling courier problem. This
is a variation on a classic optimization problem called the traveling salesman problem.

# UI features
main page
auto completion search bar
one click search buttons
click on points of interest
information display in status bar
dark mode
spoken output
path finding: with click input or search bar input, and detailed directions

# Algorithms
for path finding: Dijkstra and A*
for travelling courier problem: multi destination dijkstra, ant colony optimization, greedy algorithm, 2-opt, simulated annealing
