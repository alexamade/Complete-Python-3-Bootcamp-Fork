Psuedo Game Rules: 


1. Begin game
2. create players
3. create deck (can be 52*4 i.e. a shoe)
3. Dealer begins to play the player - game loop 
	3.1 dealer deals 2 cards to each player including himself. One of the dealers two cards is printed to terminal (i..e face up)
	3.2 The players cards are face up. 
	3.3 Player chooses an option from section 4 
	3.4 Player end turn and has final number 
	3.5 the dealer then reveals his or her hidden hole card. the dealer must hit until he or she has at least 17. If the dealer busts the remaining 9non busted players win. )
		
4. Player Controls 
	4.1 Hit: Take another card.
	4.2 Stand: Take no more cards.
	4.3 Double down: Double the wager, take exactly one more card, and then stand.
	4.4 Split: Double the wager and have each card be the first card in a new hand. This option is available only when 	both cards have the same value. Sometimes two face cards will be considered acceptable for splitting, as each is 10 points.
	4.5 Surrender: Forfeit half the bet and give up the hand. Surrender was common during the early- and mid-20th century, but is no longer offered at most casinos.


Class Player 
	def 	__init__ (self)
	def 	__str__ (self)
	def 	remove_one
	def 	add_cards
	def 	hit 
	def 	stand
	
Class Dealer 
	__init__(self)
	__str__ (self)

Class 


Class Card
	def 	__init__ (self)
	def 	__str__ (self)


Class Deck 
	def 	shuffle(self)
	def 	deal_one(self)

____________________________________________________________________________________________________________________________

Blackjack hands are scored by their point total. The hand with the highest total wins as long as it doesn't exceed 21; a hand with a higher total than 21 is said to bust. Cards 2 through 10 are worth their face value, and face cards (jack, queen, king) are also worth 10. An ace's value is 11 unless this would cause the player to bust, in which case it is worth 1. A hand in which an ace's value is counted as 11 is called a soft hand, because it cannot be busted if the player draws another card.

The goal of each player is to beat the dealer by having the higher, unbusted hand. Note that if the player busts he loses, even if the dealer also busts (therefore Blackjack favors the dealer). If both the player and the dealer have the same point value, it is called a "push", and neither player nor dealer wins the hand. Each player has an independent game with the dealer, so it is possible for the dealer to lose to one player, but still beat the other players in the same round.

Example of a Blackjack game

Example of a Blackjack game
The minimum bet is printed on a sign on the table and varies from casino to casino, and even table to table. The most common minimum in the U.S. is $5 although these games can be difficult to find on the Strip in Las Vegas, especially on weekends. The Barbary Coast has $3 minimums on weekdays. After initial bets are placed, the dealer deals the cards, either from one or two hand-held decks of cards, known as a "pitch" game, or more commonly from a shoe containing four or more decks. The dealer gives two cards to each player, including himself. One of the dealer's two cards is face-up so all the players can see it, and the other is face down. (The face-down card is known as the "hole card". In European blackjack, the hole card is not actually dealt until the players all play their hands.) The cards are dealt face up from a shoe, or face down if it is a pitch game.

A two-card hand of 21 (an ace plus a ten-value card) is called a "blackjack" or a "natural", and is an automatic winner. A player with a natural is usually paid 3:2 on his bet. In 2003 some casinos started paying only 6:5 on blackjacks; although this reduced payout has generally been restricted to single-deck games where card counting would otherwise be a viable strategy, the move was decried by longtime blackjack players.
The play goes as follows:

If the dealer has blackjack and the player doesn't, the player automatically loses.
If the player has blackjack and the dealer doesn't, the player automatically wins.
If both the player and dealer have blackjack then it's a push.
If neither side has blackjack, then each player plays out his hand, one at a time.
When all the players have finished the dealer plays his hand.
The player's options for playing his or her hand are:

After all the players have finished making their decisions, the dealer then reveals his or her hidden hole card and plays the hand. House rules say that the dealer must hit until he or she has at least 17, regardless of what the players have. In most casinos a dealer must also hit a soft 17 (such as an ace and a 6). The felt of the table will indicate whether or not the house hits or stands on a soft 17.

If the dealer busts then all remaining players win. Bets are normally paid out at the odds of 1:1.

Some common rules variations include: