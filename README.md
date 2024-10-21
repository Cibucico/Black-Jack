# Blackjack Project

Welcome to the **Blackjack Project**, a simple implementation of the popular card game Blackjack. This project allows you to play against a computer dealer and aims to provide a fun experience while learning basic Python programming concepts.

## Rules

- The deck is unlimited in size.
- There are no jokers.
- The Jack, Queen, and King all count as 10.
- The Ace can count as either 11 or 1.
- A Blackjack is a hand consisting of an Ace and a 10-value card (counted as 0).

## Requirements

- Python 3.x
- An ASCII art library for the game logo

## How to Play

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Sibusiso-Skhosana/blackjack.git
    ```
2. Navigate to the project folder:
    ```bash
    cd blackjack
    ```
3. Run the program using Python:
    ```bash
    python blackjack.py
    ```

4. Follow the on-screen prompts to play the game against the computer dealer.

### Example Gameplay

```
Welcome to the Band Name Generator!
Which city did you grow up in?
London
What is the name of your pet?
Fluffy
Your Band name could be London Fluffy
```

## Code Overview

Here's a summary of the key functions used in the project:

- **`deal_card()`**: Returns a random card from the deck.
- **`calculate_score(cards)`**: Takes a list of cards and returns the score, considering Aces as 1 or 11 as needed.
- **`compare(user_score, computer_score)`**: Compares the scores of the user and the computer to determine the winner.
- **`play_game()`**: Contains the main logic of the game, including dealing cards, calculating scores, and managing player inputs.


## Contributions

Feel free to fork this repository, submit issues, or create pull requests to improve this project. All contributions are welcome!

---

**Creator**

- **Sibusiso Skhosana**

