Thirty-One

This project implements the card game Thirty-One, a classic card game where the goal is to achieve the highest hand value possible, up to 31 points. This repository contains an interactive version of the game, developed using HTML, CSS, and JavaScript, with a visual interface and game logic implemented for the browser.

Game Description

The objective of the game is to have a hand as close as possible to 31 points. Each player starts with three cards and, during their turn, can choose to exchange one card from their hand with one from the deck.

    Number cards (2-10) have their face value.
    Face cards (J, Q, K) are worth 10 points.
    The Ace is worth 11 points.

The game includes two players: the user and the CPU.

Features

    Deal cards: At the start of the game, 3 cards are dealt to each player.
    Card exchange: The user can exchange one of their cards with a new one from the deck.
    CPU card change: Whenever the user changes a card, the CPU also swaps a card if it benefits them.
    Scoring: Each player's score is calculated based on the best combination of cards (summing cards of the same suit or the highest single card value).
    
    Game end: The game ends when one of the players reaches a total of 5 points.

Technologies

This project is built using:

    HTML5: For the structure of the content.
    CSS3: For the visual design and game interface.
    JavaScript: For the game logic, including card management, scores, and user interactions.

Installation and Usage

    Clone the repository:

    bash

    git clone https://github.com/Alejandro-Albiol/Thirty-One.git

    Open the project: Open the index.html file in a web browser to start playing.

How to Play

    Click the "Draw Cards" button to deal the first set of cards.
    Click on the cards to swap them with a new one from the deck.
    Click the "End Turn" button to end your turn and update the scores.
    The game will end when one of the players reaches 5 points.

Code Structure

    index.html: Main file that contains the game structure.
    style.css: Style sheet for the visual design of the game.
    script.js: JavaScript file that implements the game logic, including card generation, scoring, and user events.

Contributions

Contributions, bug reports, and suggestions are welcome! Feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.