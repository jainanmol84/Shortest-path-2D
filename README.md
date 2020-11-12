# Shortest-path-2D

## Implementation ##

1. **Color coding** :
	1. *Open cells* - White
	2. *Blocked cells* - Black
	3. *Start and End cells* - Blue and Red
	4. *Explored cells* - Yellow
	5. *Shortest Path of Dijkstra* - Green

2. **Major components** :
	1. Main loop to render frames at 60 frames/second
	2. Dijkstra program

3. **Implementation** :
	1. Map as 2D array of cells
	2. Binary representation of cells as 0 and 1 for blocked and open cells
	3. Each cell has information of its parent and its state of exploration


4. **## Build For Linux user ##**
	1. **Clone the repository**:
		1. `git clone https://github.com/jainanmol84/Shotest-Path-2D`
		2. `cd Shortest-Path-2D` 
	2. **Install sfml**: `sudo apt-get install libsfml-dev`
	3. **Complile path.cpp** :
		1. `g++ path.cpp -std=c++11 -lsfml-window -lsfml-system -lsfml-graphics`
	4. **Run the exectuable** : `./a.out`

3. **Supported operations:**
	1.  You can left click on blocks to draw black walls on the grid.
	2.  Search using either Dijkstra by clicking the Green button.
