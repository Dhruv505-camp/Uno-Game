Uno Game Simulation in Java
Project Overview
This is a text-based simulation of the Uno card game, written in Java. The game follows the basic rules of Uno and includes additional features to enhance the gameplay experience. Players will play with a deck of 108 cards, including numbered cards and special action cards (Skip, Reverse, Draw Two, Wild, and Wild Draw Four). The game supports up to four players and is controlled through a Command-Line Interface (CLI).

Features
Playable by 2 to 4 players.
Matching cards by color or number.
Special cards: Skip, Reverse, Draw Two, Wild, and Wild Draw Four.
Support for turn skipping and direction change.
Enforced "Uno" rule, including penalties for failing to shout "Uno."
Option to draw cards or skip a turn.
Error handling for illegal moves.
Game can be restarted or quit after a winner is declared.
Supports edge cases like invalid card plays and turn flow disruptions.
Technologies Used
Java: Core language used to implement the game logic.
Java Collections: For managing the deck, hands, and players' cards.
CLI: Command-Line Interface for interacting with the game.
Game Rules
Each player starts with 7 cards.
Players take turns in a clockwise direction and must match the top card in the discard pile by either color or number.
Special cards have unique actions:
Skip: Skips the next player's turn.
Reverse: Reverses the direction of turns.
Draw Two: The next player draws two cards.
Wild: The player chooses a new color to play.
Wild Draw Four: The next player draws four cards, and the current player chooses a color to continue the game.
Players must say "Uno" when they have only one card left. If they fail to do so and another player catches them, they receive a penalty (drawing two cards).
The game ends when a player runs out of cards.
