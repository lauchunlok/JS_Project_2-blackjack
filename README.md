# JS_Project_2-blackjack

## Thought Process

### Variable Needed:

1. cards: store the cards player have
2. sum: calculate the sum of the cards
3. hasBlackJack: boolean variable indicating whether blackjack is won
4. isAlive: boolean variable indicating whether player is alive (<=21 points)

### Element Needed:
1. messageEl: display message to ask if a new card is needed / if player have got a Blackjack / if player is out of the game
2. sumEl: display the sum of cards
3. cardsEl: display the cards player have
4. playerEl: display the info for the player (e.g. name, chips etc.)

### Function Needed:
1. startGame(): draw two cards to start the game, turn isAlive to true, call renderGame()
2. renderGame(): function that render everything - 1) cards, 2) sum, 3)status, 4) message
3. newCard(): get random card getRandomCard(), update 1) cards and 2) sum, call renderGame()
4. getRandomCard()
