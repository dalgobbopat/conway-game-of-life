# conway-game-of-life

# Deployed Website
https://pats-conway-game-of-life.vercel.app/

# Objectives
- Student should be able to create a unique, high-quality project that can be added to a professional portfolio
- Student should be able to describe the rules of Conway’s “Game of Life”
- Student should be able to explain what cellular automata are and describe how they are useful in real life
- Student should be able to correctly analyze the ‘Turing Completeness’ of Conway’s “Game of Life”
- Student should be able to implement a visualization of Conway’s “Game of Life” using technologies related to their specific track.
- Student should be able to utilize "double buffering" to implement the game

# Features
- Create a few sample cell configurations that users can load and run
- Add an option that creates a random cell configuration that users can run
- Provide functionality to manually step through the simulation one generation at a time, as opposed to animating automatically
- Allow users to change the dimension of the grid being displayed
- Grid to display cells.
- Cell objects or components that, at a minimum, should have:
- Properties
   current state: (alive, dead), (black, white)
- Clickable/Tappable:
   can be clicked to allow user to setup initial cell configuration
   should NOT be clickable while simulation is running
- Behaviors
   Toggle state functionality: switch between alive & dead either because user manually toggled cell before starting simulation or simulation is running and    rules of life caused cell to change state
- An appropriate data structure to hold a grid of cells that is at least 25x25. Go as big as you want.
   Text to display current generation # being displayed
- Utilize a timeout function to build the next generation of cells & update the display at the chosen time interval
- Button(s) that start & stop the animation
- Button to clear the grid
