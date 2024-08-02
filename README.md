# PRODIGY_SD_02
This repository contains the code and documentation for Task 2 of my Software Development Internship at Prodigy InfoTech.
# Summary about the Task
In my recent task, I developed a number guessing game using Python's `tkinter` library. This task involved creating a simple yet interactive game where the program generates a random number between 1 and 100, and the player has to guess the correct number. I designed the game to be user-friendly, with a graphical user interface that guides the player through the guessing process.

The game starts by generating a random number within the specified range. The player is then prompted to enter their guess in a text field. When they submit their guess, the program checks it against the target number. If the guess is too low, a message informs the player, and the lower bound of the guessing range is adjusted upwards. Similarly, if the guess is too high, the upper bound is adjusted downwards. This dynamic range adjustment helps the player narrow down their guesses effectively.

To ensure the game is intuitive, I implemented input validation to handle cases where the player's guess might be outside the allowed range or not a valid number. If the player guesses the correct number, the game displays a congratulatory message and resets, allowing the player to start a new round.

The graphical interface is designed with clarity and usability in mind. I used labels to display instructions, the current guessing range, and feedback messages, while a submit button processes the player's input. I chose specific colors and fonts to enhance the visual appeal and make the game more engaging. This task helped me practice and improve my skills in Python programming, particularly with the `tkinter` library, and reinforced my understanding of handling user input and updating the UI dynamically.
