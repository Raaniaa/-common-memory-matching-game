# -common-memory-matching-game
A common memory matching game played by young children is to start with a deck of cards that contains identical pairs For example, given six
cards in the deck, two might be labeled “1,” two might be labeled “2,” and
two might be labeled “3.” The cards are shuffled and placed face down on
the table. The player then selects two cards that are face down, turns them
face up, and if they match they are left face up. If the two cards do not
match, they are returned to their original position face down. The game
continues in this fashion until all cards are face up.
Write a program that plays the memory matching game. Use 16 cards that
are laid out in a 4 X 4 square and are labeled with pairs of numbers from
1 to 8. Your program should allow the player to specify the cards that she
would like to select through a coordinate system.
For example, suppose the cards are in the following layout:
1 2 3 4
----------------------------
1 | 8 * * *
2 | * * * *
3 | * 8 * *
4 | * * * *
All of the cards are face down except for the pair 8, which has been
located at coordinates (1, 1) and (2, 3). To hide the cards that have been
temporarily placed face up, output a large number of newlines to force
the old board off the screen.
(Hint: Use a two-dimensional array for the arrangement of cards and
another two-dimensional array that indicates if a card is face up or
face down. Write a function that “shuffles” the cards in the array by
repeatedly selecting two cards at random and swapping them.
