
This project implements a maze generation algorithm based on Kruskal’s algorithm, entirely written in ARM assembly language.
The implementation operates directly on memory structures representing the maze cells and the horizontal and vertical walls, demonstrating low-level algorithm design on ARM architectures.
The code is developed for the LPC1768 microcontroller (ARM Cortex-M3) and was written, built, and tested using the Keil µVision IDE.


Kruskal Subroutine Parameters
1- Base address of maze
2- Base address of horizontal_walls
3- Base address of vertical_walls
4- Number of rows (NUM_ROW)
5- Number of columns (NUM_COL)
6- Increment value y
7- Initial offset x


