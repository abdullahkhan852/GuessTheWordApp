# GuessTheWordApp
**Guess the Word App**

This Guess the Word App is a simple web application built using HTML , CSS and AngularJS. It challenges players to guess a secret word by inputting individual letters. The game provides feedback on correct and incorrect guesses and keeps track of the remaining guesses.


**Features**

Randomly selects a word from a predefined list of words.
Displays the number of remaining guesses.
Keeps track of correct and incorrect letter guesses.
Updates the display of the secret word with correct guesses.
Ends the game when the player either guesses the word correctly or runs out of guesses.
Allows for a new game to start automatically after winning or losing.

**Project Structure**


**package.json**: This file contains project metadata and dependencies information. It's used for managing project dependencies and scripts.
{
  "name": "Guess Word App",
  "description": "First Angular App",
  "version": "0.0.0",
  "dependencies": {
    "bower": "^1.8.0"
  }
}


**bower.json**: This file specifies project dependencies for the Bower package manager, including AngularJS.
{
  "name": "Guess Word App",
  "description": "First Angular App",
  "version": "0.0.0",
  "dependencies": {
    "angular": "~1.4.0"
  }
}

**How to Play**


Open the web page.
Start guessing letters by typing them into the input field.
The game will inform you if the letter is correct or not.
Keep guessing until you either win by correctly guessing the word or lose by running out of guesses.
A new game will automatically start after each win or loss.
Dependencies
AngularJS: This game utilizes AngularJS for data binding and game logic.
Usage
Clone this repository.

Open the index.html file in a web browser to play the game.

**Customization**


You can customize the list of words by modifying the words array in the JavaScript code (app.js). Simply replace the existing words with your own.
var words=["Altassian","Remember","Mountain","Pokemon"];


**Author**


**Abdulla Farookh Khan**

Feel free to contribute to the project, report issues, or make improvements.
