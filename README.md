# Blackjack Game

## Overview
This is a simple implementation of the classic Blackjack card game using HTML, CSS, and JavaScript. The game allows the player to draw cards, calculate their sum, and win or lose based on the Blackjack rules.

## Features
- Displays the player's current balance.
- Player can start a game with an initial bet.
- Player can draw a new card to improve their hand.
- Win condition if the sum of cards is exactly 21 (Blackjack).
- Loss condition if the sum exceeds 21.
- Player earns or loses chips based on the game outcome.
- Interactive UI with a table background and button effects.

## Technologies Used
- **HTML**: Structure of the game interface.
- **CSS**: Styling and layout design.
- **JavaScript**: Game logic and interactions.

## How to Play
1. Click the "START GAME" button to begin a new round.
2. Two random cards are drawn automatically.
3. The sum of your cards is displayed.
4. If the sum is below 21, you can click "NEW CARD" to draw another card.
5. If the sum is exactly 21, you win and receive additional chips.
6. If the sum exceeds 21, you lose the round.

## Game Rules
- Face cards (J, Q, K) are worth 10 points.
- Aces (A) can be worth 1 or 11 points, whichever is more beneficial.
- If the total sum is 21, the player wins instantly (Blackjack).
- If the total sum exceeds 21, the player loses.
- The player starts with a balance of 200 chips and loses 50 chips per game.
- Winning a game awards 100 chips.

## File Structure
```
/blackjack-game
|-- index.html      # Main game interface
|-- index.css       # Styling for the game
|-- index.js        # Game logic and interactivity
|-- images/         # Background and card images
```

## Deployment
The game is deployed and can be played at: [Blackjack Game](https://vipyan.github.io/BlackJack/)

## Future Improvements
- Implementing dealer AI for a more competitive experience.
- Adding more betting options.
- Enhancing the UI with animations and sound effects.

## License
This project is open-source and available for modification and distribution.

## Author
Created by **Vipin**