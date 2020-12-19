# Shortest-path-2D

https://user-images.githubusercontent.com/30202180/102689209-4c382000-4222-11eb-9122-77032243c79e.mp4


https://user-images.githubusercontent.com/30202180/102689211-4f331080-4222-11eb-9b9d-19587a40913a.mp4


1. **Color coding** :
	1. Unexplored cells ->White
	2. Blocked cells -> Black
	3. Start cell -> Blue
	4. End cell -> Red 
	5. Explored cells -> Pink
	6. Shortest Path by Dijkstra  -> Green
	7. Shortest Path by A-star  ->  Yellow
	8. Green button-> Dijkstra
	9. Red button-> A*
	10. Distance-1 : Dijkstra path length 
	11. Distance-2 : A* path length
	11. The horizontal and vertical movement cost -> 1
	12. Diagonal cost -> √2.


2. **Major components** :
	1. Main loop 
	2. Dijkstra program
	3. A*

3. **Implementation** :
	1. Map as 2D array of cells
	2. Binary representation of cells as 0 and 1 for blocked and open cells
	3. Each cell has information of its parent and its state of exploration


4. **## Build For Linux user ##**
	1. **Download the zip file then unzip at the location 'Home'**:
		1. `cd Shortest-Path-2D` 
	2. **Install sfml**: `sudo apt-get install libsfml-dev`
	3. **Complile path.cpp** :
		1. `g++ path.cpp -std=c++11 -lsfml-window -lsfml-system -lsfml-graphics`
	4. **Run the exectuable** : `./a.out`

3. **Supported operations:**
	1.  You can left click on blocks to draw black walls on the grid.
	2.  Search using either Dijkstra by clicking the Green button.
