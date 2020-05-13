# Robot Navigation.
Objective of this project is to  navigate a robot through a maze to reach the center of the maze.
This robot navigation system was tested using [Micromouse Simulator](https://github.com/mackorone/mms). 
Depth-first Search algorithm is being applied to implement the path planning algorithm.
<p align="center">
  <![](output.gif)>
</p>


## Dependencies.
```
1. Ubuntu 16.04
2. Doxygen 1.18.18
3. CodeLite 14.0
4. micromousesimulator
5. QT

```

## To Run the Code.
```
Clone this repository

cd to /Final-Project-Group5/Simulator
Enter mms/bin/mms to start the simulator

Set Directory to the path of src
	ex: /Final-Project-Group5/FP/src

Set "Build Command" to:
	g++ -std=c++11 API/api.cpp Maze/maze.cpp Algorithm/algorithm.cpp LandBasedRobot/landbasedrobot.cpp LandBasedTracked/landbasedtracked.cpp LandBasedWheeled/landbasedwheeled.cpp ../main.cpp

Set "Run Command" to:
	./a.out

Build the project and run it

```
## Doxy Output 
```
run the index.html file in Documentation/html/ folder

```
## Video Output
```
To visualize the Robot naviagtion play Output.mkv

```


