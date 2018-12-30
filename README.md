# Black_Jack_Game
Black Jack game written in Python 3.7 using Jupyter Notebook

Link to quick launch this program:
https://mybinder.org/v2/gh/cllaudia/black-jack-game/master?filepath=BlackJackGame.ipynb

Game created during Python Udemy Course: https://www.udemy.com/complete-python-bootcamp/

Game Play
To play a hand of Blackjack the following steps must be followed:

    Create a deck of 52 cards
    Shuffle the deck
    Ask the Player for their bet
    Make sure that the Player's bet does not exceed their available chips
    Deal two cards to the Dealer and two cards to the Player
    Show only one of the Dealer's cards, the other remains hidden
    Show both of the Player's cards
    Ask the Player if they wish to Hit, and take another card
    If the Player's hand doesn't Bust (go over 21), ask if they'd like to Hit again.
    If a Player Stands, play the Dealer's hand. The dealer will always Hit until the Dealer's value meets or exceeds 17
    Determine the winner and adjust the Player's chips accordingly
    Ask the Player if they'd like to play again

After these steps had been implemented the game was expanded by adding double down, cards split and insurance option.
Player can double down his bet after he has received second card.
If player doesn't decide to double down his bet and he has received two cards with the same rank, he can split his cards into two separate hands with two same bets. If splitted cards rank is 'Ace", player receive only one further card.
If the player doesn't use options above and after two cards has been handed to dealer and player, if the shown dealer's card rank is 'Ace', player can insure against that the dealer got BlackJack. If dealer have BlackJack, player receive insurance paid 2:1.
