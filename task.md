## Diamond sweeper

The goal of this exercise is to build a game.

**The rules of the game are as follows:**
1. The game board has 8x8 squares (initially, all represented by question marks).
2. There are 8 diamonds hidden on the board, each diamond behind one of the squares.
3. When the user clicks on a square, If the square was hiding a diamond, the diamond appears. Otherwise, the square is opened, and blank.
4. The game ends when all diamonds are found. The user's score is the number of squares still left unturned.

**Advanced(Hints):**

1. Part II of this problem adds the ability to add hints to empty squares.
2. When the user clicks on a square, If the square was not a diamond, then an arrow appears, pointing towards the nearest diamond.
Any arrows that were previously show become hidden.

**Higher level breakdown for the app:**
1. Create a html page as 8x8 grid layout (64 squares).
2. Generate 8 random numbers from the range between 0 to 63, and place the diamond in those places as a background image.
2. Add event listener to each squares.
3. Once the user clicks on a square, do the necessary action and remove the event listener.
