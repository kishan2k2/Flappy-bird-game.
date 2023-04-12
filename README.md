# Flappy-bird-game.
Globally random, sys, and pygame is imported.
FPS, screen width, height, and dictionaries are declared.
Firstly the special variable is called.
The game is initialized.
FPS is set.
The caption is also set.
All the dictionaries of photos sound are filled.
Welcome screen and then the main game is called.
Welcome screen.
The initial position of the x and y coordinate is set. For the bird and message.
If the key pressed is quit or escape then the game is finished.
Or else it is repeated. And if none is pressed then screen is blitted with the images.
mainGame()
This the main portion of the code.
Variables are defined score, x and y position, two pipes are generated.
The position of X and Y coordinates are set in the dictionary of upper and lower pipes.
Velocity of X coordinate and Y coordinates are set.
Flapped variable is set to false.
Check if the player want to quit the game.
If not set playerFlapped to true.
Do the crash test using the x and y coordinate of bird, and the coordinate of lower and upper pipe.
The score is incremented using the mid position of pipe if it 4 px right to the pipe then the score is incremented.
If the player hasn’t flapped and Y vel is less than maxvel then increment the Y velocity.
Increase the vel/position of pipes lower and upper.
Introduce a new pipe when the pipe is near to 0- 5 px to the screen.
If the pipe has crossed the screen we pop upper and lower pipe.
isCollide
Checks the collision but taking consideration of the borders of the images.
getRandomPipe()
Used to spawn and kill the pipes.
