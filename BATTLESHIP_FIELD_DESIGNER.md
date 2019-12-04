# Exercise

In this exercise you will build a Battleship field designer, which will help us populate a battlefield of battle-ships. The designer will place submarines, destroyers, cruisers & aircraft carriers on the field, while ensuring that they do not collide or go off the board.

Remember that there isn't one specific way to implement this system; in other words, don't think of this exercise as a "right or wrong" question, but more of a way for us to get to know your way of thinking :)

### Requirement

You will implement the following functions:

* `placeSubmarine()`: places a submarine (1x1) on the board at a random location.
* `placeDestroyer()`: places a destroyer (2x1) on the board at a random location, either vertically or horizontally.
* `placeCruiser()`: places a cruiser (3x1) on the board at a random location, either vertically or horizontally.
* `placeCarrier()`: places an aircraft carrier (4x1) on the board at a random location, either vertically or horizontally.

All functions avoid placing vessels on top of, or adjacent to, other vessels.

### Runtime

Program should be a simple CLI that can be run. The program should print out the board with all vessels placed.

### Docs

Please make sure your code is documented, and you include instructions on how to run the program (those instructions can replace the instructions in the `README.md` file)

### Tools

You may choose any of the common programming languages (e.g. Python, JavaScript, Java, etc).
