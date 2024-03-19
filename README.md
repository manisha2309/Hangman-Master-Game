<big>Title---->Hangman-Master-Game</big> <br>
This is a team project on a guessing game where one player guess the letters by suggesting some where the letter is selected by the system.
The word is represented by a row of dashes, with each dash representing a letter in the word. The guessing player suggests letters one at a time, and if the letter is in the word, the system reveals its correct positions. If the letter is not in the word, the guessing player receives a strike. The game continues until the guessing player correctly guesses the word or accumulates too many strikes, resulting in a loss. It's a fun and challenging game that tests vocabulary and deductive skills.

<br>TEAM MEMBERS <br>
1. Jigyasa --Manager <br>
2. Manisha --Developer <br>
3. Manshika --Tester <br>

Instructions: <br>

- Setup: One player ( i.e.the "system") decides a word and keeps it secret. They draw a series of dashes, each representing a letter in the word.<br>

- Guessing: The other player (the "guesser") starts guessing letters. If the guessed letter is in the word, the word chooser writes it in all the correct positions. If the guessed letter is not in the word, the word chooser adds a body part to the hangman scaffold (e.g., head, body, arms, legs).<br>

- Objective: The guesser's objective is to guess the word before the hangman is fully drawn. If they can guess all the letters in the word before the hangman is complete, they win. If the hangman is fully drawn before they guess the word, they lose.<br>

- Rules: Usually, the word chooser provides a category or a hint to give the guesser an idea of what the word might be.<br>
The guesser typically has a limited number of incorrect guesses before the hangman is fully drawn (e.g., 6 incorrect guesses).


Version1:<br>
In Version 1 of our game, we encountered the following problems:-<br>
The player might find the game very basic, as it's not very interactive and visually appealing, which could be improved using a Graphical User Interface (GUI) using Tkinter. By adding the GUI version, it enhances the Hangman game by providing a more user-friendly interface, better feedback mechanisms, and improved interaction with the game. This version of the game lacks variety in word selection, making it predictable and reducing replay value over time. Furthermore, the player does not get instant feedback through printed messages in the console after every guess, which also makes it less user-friendly.

Version2:<br>
In Version 2 of our game, we encountered the following problems:-<br>
After applying GUI using tkinter in this version the game interface is simple, with a text entry for guesses and basic message boxes for feedback. Some players might prefer a more visually engaging interface with graphics or animations to enhance the gaming experience.The game has a set number of attempts (6 in this case). Some players might find this limit challenging, while others might feel it is too restrictive. If the player guesses the word correctly, they will receive a "Congratulations" message. Some players might find this limit challenging, while others might feel it is too restrictive. Additionally, this version lacks varying difficulty levels, leading to players encountering repeated words during gameplay. Furthermore, there is a notable absence of a Scoreboard feature, which could enhance competitiveness and player engagement.

Version3:<br>
In Version 3 of our game we faced the following problems:-<br>
Firstly, players expressed concern over the limited word choices available, which could lead to boredom over time. Additionally, the simplistic and unappealing graphics without colors failed to captivate players visually, further contributing to potential disinterest.Another significant drawback was the absence of a difficulty level selection feature. This omission deprived players of the opportunity to face the game's challenge to their preferences, potentially hindering their overall enjoyment and motivation to continue playing.Furthermore, players faced the lack of a clear scoring system, as they were unable to gauge their progress or compare their performance with themselves. This absence of feedback undermined the game's ability to provide a sense of accomplishment and progression, which are crucial elements in sustaining player interest and involvement.

Version4:<br>
In Version 4 of our game, we have implemented several enhancements to elevate the player experience:-<br>
We revamped the graphical user interface using tkinter to create a more interactive and visually appealing experience. Additionally, we introduced more graphics and colors to enhance the visual engagement and make the game more captivating. By adding a wider array of word choices, we aim to keep players engaged for longer durations, offering a more diverse and challenging gameplay experience. The inclusion of multiple difficulty levels adds depth to the game, catering to players of different skill levels and ensuring a more engaging gameplay. We refined the hangman formation process after incorrect attempts by the player, enhancing the overall gaming experience. To improve user experience, we increased the text size to prevent any interface issues and ensure seamless gameplay for all players.
