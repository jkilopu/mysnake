# mysnake

Simple console version of the game "snake" for Linux ONLY, with scoreboard.

## Gameplay

Use *w, a, s, d* to change to direction of the snake, it will move automatically. 

By eating food, your snake will grow, and you will score ten points.

When your snake hit the wall or its body. the game is over.

Try different user names, you can see your real-time ranking on the scoreboard.

Help your snake grow longer and longer, your score will be recorded in *scoreboard.txt*.

## Requirements

* C/C++ compiler
* ncurses library
* cmake
* make

## Installation

``` bash
git clone https://github.com/jkilopu/Linux-Programming.git
cd ./Linux-Programming/mysnake
mkdir build
cd build
cmake .. # You may need to specify a build system generator with "-G" option
make
cd ..
./build/bin/mysnake
```
