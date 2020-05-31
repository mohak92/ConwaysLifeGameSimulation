# Conway's Life Game Simulation

## Overview
Cellular Automation
* A discrete model studied in complexity science.
* Regular grid of cells, each cell is in one of finite number of states.
* For Conway's game we have 2 states: Dead or Alive.
* The algorithm will generate newer generations.

## Algorithm
* On every Iteration the neighbors of the cell determine the next state of given cell.
* Use Moore neighborhood to determine neighbors.

## Game Rules
* Underpopulation: any live cell with less than 2 live neighbors dies
* Overcrowding: any live cell with more than 3 live neighbors dies
* Any live cell with exactly 2 or 3 live neighbors lives on to the next generation
* A dead cell with exactly 3 live neighbors becomes a live cell

## Built with
* Java
* Swing for GUI
