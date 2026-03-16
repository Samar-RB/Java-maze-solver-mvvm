# Maze Solver Project – Java

## Overview

In this project, I implemented a **maze solver** in Java. The goal is to navigate a character through a maze from an entrance to an exit using valid moves (up, down, left, right), avoiding walls.  

The maze is represented as a **2D array of integers**:

- `1` → wall (blocked cell)  
- `0` → open path (free cell)  

Example representation:

```java
int[][] maze = {
    {0,0,1,0,1,0,0,0,1},
    {1,0,1,0,1,0,1,0,0},
    {1,0,0,0,0,0,0,1,1},
    {1,0,1,1,0,1,0,1,1},
    {0,0,1,1,0,1,0,1,1},
    {1,1,0,0,0,1,0,0,0}
};
