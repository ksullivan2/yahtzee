# YAHTZEE

*The classic dice game.*

## Game Rules
**Rolling the Dice**
  * Your goal is to create a good "hand," similar to poker hands.
  * After each roll, you can "freeze" any number of dice to save their values and roll only the remaining dice.
  * You have 3 rolls to create the best possible hand.
  
**Scoring hands**
  * After each hand, you can choose which category of your Scorecard to count the points toward. 
  * You can only use each category once, so choose wisely!
  * You can choose categories even if they're worth 0 points that hand.
  * At the end of the game, if you have at least 63 points in the top half (Aces - Sixes), you are awarded 35 bonus points.

**Hands**
  1. Aces = 1 pt for each ace in your hand
  2. Twos = 2 pts for each two in your hand
  3. Threes = 3 pts for each three in your hand
  4. Fours = 4 pts for each four in your hand
  5. Fives = 5 pts for each five in your hand
  6. Sixes = 6 pts for each six in your hand
  7. Three of a Kind = *sum of dice in hand* if at least 3 dice match
  8. Four of a Kind = *sum of dice in hand* if at least 4 dice match
  9. Full House = 25 pts if 3 dice match and the other 2 match each other
  10. Small Straight = 30 pts if there are at least four consecutive dice
  11. Large Straight = 40 pts if there are five consecutive dice
  12. Change = *sum of dice in hand*
  13. Yahtzee = 50 pts if all five dice match
  14. Yahtzee Bonus = 100 pts for each Yahtzee after the first one


v 1.0
---------

**To Run:**
  1. Install [Kivy](https://kivy.org/#download)
  2. Clone repo into a folder called `yahtzee` (or whatever you'd like)
  3. EITHER:
    * Run `kivy __main__.py`
    * (from the parent folder) run `kivy yahtzee` (or your folder name)

**Known Issues/Missing Features**
  * I didn't quite know how to do animation callbacks when I wrote this, so the timing is off.
  * If you lock all 5 dice, it would be nice to activate the scorecard instead of needing to pretend to finish out your rolls.
  * Yahtzee Bonus category becomes active sometimes when it shouldn't.
  * No concept of MVC. 


*Disclaimer: I do not own the rights to the game of Yahtzee nor the name. This project was developed purely for learning purposes and is not for commercial use in any way, shape, or form. Game icons are from http://game-icons.net/*
