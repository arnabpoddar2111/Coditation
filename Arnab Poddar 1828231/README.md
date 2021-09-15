# Coditation-Arnab Poddar




#### Better viewed in Desktop site..


## At each step in time (tick), the following transitions occur:
1. Any live cell with fewer than two live neighbors dies, as if by loneliness.
2. Any live cell with more than three live neighbors dies, as if by overcrowding.
3. Any live cell with two or three live neighbors lives, unchanged, to the next generation.
4. Any dead cell with exactly three live neighbors comes to life.
The initial pattern constitutes the 'seed' (randomly placed 500 cells) of the system. The first generation is
created by applying the above rules simultaneously to every cell in the seed — births and deaths happen
simultaneously, and the discrete moment at which this happens is called a tick. (In other words, each
generation is a pure function of the one before.

### Any live cell with two or three live neighbours survives.
### Any dead cell with three live neighbours becomes a live cell.
### All other live cells die in the next generation. Similarly, all other dead cells stay dead.



Write a program in the language(s) of your choice with following guidelines:
1. Accept a user input of new cells (max 100 at every step/tick) to be placed; each cell should have a
unique name which is to be accepted by the user. This input can be accepted through a CLI or
HTML element or any other form of user interface
2. Acceptance of the user input represents a tick and program is expected to calculate the state of
every cell
3. The program should output the state of the cells and changes - representation (UI/CLI et al.) of
the state of the cells can be decided by the developer
4. The program should provide a way to search by the name of the cell and show the current state of
the cell
5. The program should end on termination through appropriate OS specific signals