# MasterMind-for-Words

User notes:

Welcome to the "Master Mind for Words" game!

In this game, a player picks a word and the opponent tries to find the selected word 
in a process of guessing and receving feedback from the player. The opponent guesses 
a word and the player announces two scores per guess: The number of letters that have 
appeared in the selected word (regardless of if they are in their correct respective 
"place" in the word), plus the number letters that have appeared in their correct 
respective place.

For example, if the selected word is ENGLISH and the guessesd word is GERMANY, the 
scores would be 3 (for the letters G, E, and N from the guessed word that appear in the 
selected word) plus 0 because none of those letters have appeared in the correct 
respective place. As another example, if the selected word is MOTHER and the guessed 
word is FATHER, the scores would read 4 (for the letters T, H, E, and R from the guessed 
word that appear in the selected word) plus another 4 because all of those letters have 
appeared in the correct respective place.

The game continues until the opponent either finds the selected word correctly, or 
withdraws from continuing the contest. To withdraw from continuing the game, insert "Q" 
as the user input when prompted.

For simplicity, this game has assumed that the words selected and guessed DO NOT have a 
repeated letter. So, be mindful of that in order for the game to work properly, you 
should avoid repeated letters in your inputs.


Development notes:

The following are current issues and ways in which this can be improved.
Please help me if you can!

1. Not all exceptions -- especially for input validation -- are handled.
2. For an unknown bug in Microsoft Excel, the input forms' sizes shrink everytime you
   run the program.
3. I was trying to capture keystrokes while the system is computing its next guess,
   so the user would have the option of pressing "Q" or "ESC" to end the computation,
   but I had no success. That would be a good feature to be added.
4. Loading a dictionary of words (with no repeated letters) can be helpful, so the
   computer would pick its word for the users to guess from a meaningful pool of
   words. I have downloadded a text-file of all dictionary words, but just didn't put
   the effort in selecting the words with no repeated letters and importing them to
   an excel sheet.
5. The game currently does not allow the user to fix a prior score if it was wrongfully
   entered by a user to assess a computer guess. This feature can increase interactivity.
6. The scoreboard does not record any scores in the two-player mode.
7. The players do not have an option to input their names anywehere in the system for a 
   more personal message interchange experience.
