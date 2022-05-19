# ConwayPygame
my take on Conway's Game Of Life, made with Python using Numpy and Pygame

Currently there are three templates to choose from, and one where you can make your own patterns.

(apologies for the terrible UI. I'm a programmer, not a graphics designer)

upon launch, 4 texts will appear. 3 referring to their patterns, and one for custom.

The custom one launches the grid space and lets you click individual cells to turn them on, or make them alive.
In the top left there is a start button, and wouldn't you know it, once it's pressed it starts the simulation.

the rules are typical. Alive cell needs 2-3 neighboring living cells to survive, dead cells come to life at 3 living neighboring cells.




TODO and changelog: 

The clicking is still very janky. There is also currently no option to turn off a cell in the customize window. *1

*1: as of 19/05/2022: toggling cells in custom mode significantly improved, can also now toggle living cells to make them dead.

