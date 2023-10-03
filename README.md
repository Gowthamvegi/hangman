#**Hangman Game Project**

#Description:
##Hangman is a classic word guessing game where one player thinks of a word, and the other player tries to guess it one letter at a time. 
The game continues until the player correctly guesses the word or runs out of attempts.

Approach:

Word Selection:
Choose a collection of words to be used as the game's word bank. You can store them in a list or import them from an external file.

Random Word Selection:
Implement a function to select a random word from the word bank. The selected word will be the one the player needs to guess.

Game Loop:
Create a loop that will run the game until it's either won or lost. You can use a while loop for this purpose.

Display Hidden Word:
Display the current state of the word with underscores representing unguessed letters and revealed letters for correct guesses.

User Input:
Take user input for guessing a letter. Ensure input validation to handle non-alphabet characters and repeated guesses.

Check Guess:
Check if the guessed letter is in the selected word. Update the display accordingly.

Incorrect Guess Tracking:
Keep track of incorrect guesses and display them to the player.

Winning Condition:
Check if the player has successfully guessed the entire word. If yes, end the game with a win message.
Losing Condition:

Implement a limit on the number of incorrect guesses allowed. If the player exceeds this limit, end the game with a loss message.

Play Again Option:
After each game, ask the player if they want to play again. If yes, start a new game. If no, exit the program.
