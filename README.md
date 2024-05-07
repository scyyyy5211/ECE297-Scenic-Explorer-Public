# Overview
This is a project for ECE297 at the University of Toronto. In a team of three, we developed a tourism-focused map with a navigation system using C++ for the core algorithms and CSS for the user interface (UI). Our work involved tackling four milestones that guided us through building an intuitive and feature-rich solution.

# Milestones
### M1: Geographic API Extension
- Integrated and extended the libstreetsdatabase API for querying geographic data.
- Leveraged StreetsDatabaseAPI for accessing structured street and intersection information.
- Used OSMDatabaseAPI for lower-level OpenStreetMap data.

### M2: Map Visualization with EZGL
- Incorporated the EZGL graphics library to visualize the map.
- Developed functions for finding map elements and displaying detailed information.

### M3: Pathfinding Algorithms
- Implemented algorithms to find optimal travel routes between two points using graphs.
- Leveraged techniques applicable across various domains like GIS, circuit design, and networking.

### M4: Traveling Courier Problem
- Solving the traveling courier problem, where we need to find the optimal route for a courier picking up and dropping off packages in a city, a variation of the Traveling Salesman Problem (TSP).

# UI Features
- Main Page:
[screenshot]

- Auto-completion search bar and one-click search buttons: 
[screenshot]

- Clickable points of interest:
[screenshot]

- Information display in a status bar.
[screenshot]

- Dark mode
[screenshot]

- spoken output for accessibility.
[screenshot]

- Pathfinding with input from either clicks or the search bar, providing detailed directions.
[screenshot]

- Help page for navigation.
[screenshot]

# Algorithms
### Pathfinding:
- Implemented Dijkstra's and A* algorithms for efficient navigation between points. Program finds the fastest path under 0.5 seconds. 

### Traveling Courier Problem:
- Multi-destination Dijkstra to precompute all the needed paths between the intersections. 
- Ant Colony Optimization (ACO) and greedy heuristics to find a route.
- 2-opt optimization and simulated annealing to improve a existing route.
