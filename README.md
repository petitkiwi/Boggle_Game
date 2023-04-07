# Boggle_Game
*16/12/2020*

The famous letters and words game, but in C#, and named Boogle!

### Rules
The game begins by shuffling a board (square) of 16 six-sided dice. Each die has a different letter on each of its faces. The dice are rolled on the board 4 at a time, with only the top face visible. You will translate the roll of the dice into a random drawing of one of the 6 sides of a die for all the dice. After this operation, a countdown of N minutes is launched, establishing the game's duration. Each player plays one after the other for a period of 1 minute. Each player looks for words that can be formed from adjacent letters on the board. By adjacent, it is meant horizontally, vertically, or diagonally. The words must be at least 3 letters long, singular or plural, conjugated or not, but may not use the same die more than once for the same word. Players enter all the words they have found on the keyboard. A score per player is updated for each word found and validated. The calculation of points is done in the following way: A word is accepted only once during the game per player.

### Ressources
I provided a graphical interface to play the game, and two .txt files with the dictionnay dataset and the die letters.
