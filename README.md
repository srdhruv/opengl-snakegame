# opengl-snakegame
A simple 2d snake game made using opengl in c++
## Demo
![sample1](media/sample1.gif)


## Keyboard Controls
* P - To resume/start or pause the game
* R - To restart the game
* W - To move up
* A - To go left
* S - To go down
* D - To go right
* M - To change difficulty
* H - For help
* +/- - To change map size
* Esc or Q - To Exit

## Compilation and Execution
To Compile
```
g++ snakeGame.cpp -lglut -lGL -lGLEW -lGLU -o game
```
To run
```
./game
```

## Dependencies
For Ubuntu
```
 sudo apt install binutils-gold  g++ mesa-common-dev build-essential libglew1.5-dev libglm-dev
 ```
 ```
 sudo apt install mesa-utils
 ```
 ```
 sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev
```

