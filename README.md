
# Uno Game Simulation in Java

**Project Overview**

This is a text-based simulation of the Uno card game, written in Java. The game follows the basic rules of Uno and includes additional features to enhance the gameplay experience.

Players will play with a deck of 108 cards, including numbered cards and special action cards (Skip, Reverse, Draw Two, Wild, and Wild Draw Four). The game supports up to four players and is controlled through a Command-Line Interface (CLI).

**Features**

* Playable by 2 to 4 players.
* Matching cards by color or number.
* Special cards: Skip, Reverse, Draw Two, Wild, and Wild Draw Four.
* Support for turn skipping and direction change.
* Enforced "Uno" rule, including penalties for failing to shout "Uno."
* Option to draw cards or skip a turn.
* Error handling for illegal moves.
* Game can be restarted or quit after a winner is declared.
* Supports edge cases like invalid card plays and turn flow disruptions.

**Technologies Used**

* **Java:** Core language used to implement the game logic.
* **Java Collections:** For managing the deck, hands, and players' cards.
* **CLI:** Command-Line Interface for interacting with the game.

**Game Rules**

* Each player starts with 7 cards.
* Players take turns in a clockwise direction and must match the top card in the discard pile by either color or number.
* Special cards have unique actions:
    * **Skip:** Skips the next player's turn.
    * **Reverse:** Reverses the direction of turns.
    * **Draw Two:** The next player draws two cards.
    * **Wild:** The player chooses a new color to play.
    * **Wild Draw Four:** The next player draws four cards, and the current player chooses a color to continue the game.
* Players must say "Uno" when they have only one card left. If they fail to do so and another player catches them, they receive a penalty (drawing two cards).
* The game ends when a player runs out of cards.

**Getting Started**

1. **Prerequisites:**
    * Java Development Kit (JDK) installed.
    * A basic understanding of Java programming.

2. **Installation:**
    1. Clone the repository:
        ```bash
        git clone https://github.com/Dhruv505-camp/Uno-Game.git
        ```
    2. Compile and run the project:
        ```bash
        cd uno-game
        javac UnoGame.java
        java UnoGame
        ```

**How to Play**

1. The game will prompt you to enter the number of players (2-4).
2. Each player will be dealt 7 cards.
3. The top card of the deck is placed face up in the discard pile.
4. Players take turns playing a card from their hand that matches the top card in the discard pile by either color or number.
5. If a player cannot play a card, they must draw a card from the deck and their turn ends.
6. Special cards have their respective effects, as described in the game rules.
7. The first player to run out of cards wins the game.
8. After 15 rounds it will be draw.
   

**Contributing**

We welcome contributions to this project! Feel free to fork the repository, make improvements, and submit pull   
 requests.

**License**

This project is licensed under the sheridan college License.   

