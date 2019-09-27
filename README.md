# card_game
War is a two player card game in which a standard deck of 52 cards is split into two equal
decks, one for each player. The Game of War has the following rules:

1. Cards are ranked, lowest-to-highest, in the following order:
2, 3, 4, 5, 6, 7, 8, 9, 10, jack, queen, king, ace.
2. At the start of a round, *each player draws 1 card* from their deck and places it face-up in
front of them.
3. The player that revealed the higher card wins that round.
4. If the players’ cards are tied in value, this results in War.
5. During War, some of the rules change:
  * The given round does not end until War ends
  * Players continue to draw and compare cards, but *each player attempts to draw 2 cards*
  * Although two cards are drawn by each player, only the final card drawn by each
player is used for comparison (all other drawn cards are ‘waste’ cards)
  * War ends when the compared cards are no longer tied in value.
  * In the event that a player runs completely out of cards (in both the draw and
discard pile), they stop drawing and continue to compare using their most
recently drawn card (i.e., the last card in their deck)
6. Round winners are awarded all drawn cards (both their own and their opponent’s) and
add them to their discard pile.
7. If at any point a player’s draw pile runs out of cards they reshuffle their deck

wargame.py has the code to run the game.
Test_wargame.py was used to test wargame.py as the name suggests.
