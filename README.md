# Anagrams

This project is a command-line based Anagram Game where the player is presented with a word and must enter a valid anagram of that word. The game checks whether the user's input uses the exact same letters (with the same frequency) as the original word and then checks that the word in in a list of the expected anagrams. If so, the user wins and the number of attempts is recorded. Otherwise, the user continues guessing until the correct anagram is entered.

How it's made:
__________________________________
First, I created a list of anagrams that I wanted the game to pull from, and inputted them into python as sample anagrams and final anagrams. Then I created the method to track the number of guesses, and the method to generate an anagram. The anagram generator pulls an anagram from the sample list and presents it to the user, the user is then allows to guess, and the program checks if the word is in final anagrams. if the answer is in final anagrams, the player wins, and if not, they are prompted to continue guessing. This function also checks, if they entered the same word. After htey guess the word, the program prints out their number of guesses. 

Tech used: python

How to run:
____________________________________

1. Ensure you have Python installed on your system.

2. Save the script to a file, e.g., anagram_game.py.

3. Run the script in the terminal with:

   - python anagram_game.py
        1. When prompted, enter an anagram of the displayed word. Repeat until correct.
        2. The game will display how many tries it took you to guess the correct anagram.
