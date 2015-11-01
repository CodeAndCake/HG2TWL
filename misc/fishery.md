# Fishery

Each player manages a fishery operating in the same region.

The goal is to have the most **money** by the end of 10 **years** (rounds).

<!-- This is a simulation of a capitalist fishing industry -->

![](http://www.molleindustria.org/blog/wp-content/uploads/2013/07/fishing_game_small1.png)

### Setup

* Each player starts with a fishing rod **technology card** (cost 0).
* Place **24 fish pieces** in the centre of the table. That will be the **pool**.
* Place all the money aside. That will be the **bank**. If necessary elect a player who will take care of the money handling.
* Put a **year marker** (a money token) in the first space underneath the price chart.
* Determine a starting player. This person will keep the **wheel card** in front of her as a reminder.
* Place the technology cards aside and **face up**, stacked by type (6 stacks of 4 cards):

	Name | Cost (money) | Catch (fish) | Condition
	---- | ------------ | ------------ | ---------
	Rod      | 0        | 1            | if pool > 15 
	Boat (S) | 3        | 2            | if pool > 15 
	Boat (M) | 5        | 3            | if pool > 15 
	Trawler  | 5        | 1            |  
	Ship     | 8        | 2            |  
	Radar    | 10       | 3            |  

### Gameplay

Every year is comprised by 8 **phases**:

1. **Expedition**

	All players, at the same time, play one technology card among the ones they acquired.
2. **Priority**

	Players can invest extra money to take priority in the harvest phase. They can do so by bidding freely. The highest bidder gets the steering wheel card and gives the money to the bank.

	Bidding is not necessary, it may be useful in time of *scarcity* later in the game.
3. **Harvest**

	Starting from the player with the steering wheel and proceeding clockwise, players catch the number of fish corresponding to the technology card they played - if there's fish left.

	If the condition `more than 15 fish in the pool` on a card is not met at the beginning of a player's turn, she will not catch any fish.
4. **Market price**

	Determine the price of fish for the year by looking at the price chart line corresponding to the total number of fish caught by all players.
	
	HARVEST | PRICE
	------- | -----
	more than 10 | 1
	7 - 10       | 2
	less than 7  | 3
	Fish caught by all players this year | Per fish
	
5. **Income**

	Each player gets an amount of money equal to the market price multiplied by the number of fish she caught this year. Caught fish is set apart.
6. **Investment**

	Starting from the player with the steering wheel and proceeding clockwise, players can decide to acquire technology cards by paying the cost reported on the top right corner.

	Technology cards are never discarded and return in players' hands. At every expedition phase they decide which one to use without declaring their intentions.
7. **Regeneration**

	For each 3 remaining fish, add 1 fish to the pool up to a maximum of 30.

	Example: if there are 7 fish left, add 2.
8. **End year**

	Move the year marker to the next space to keep track of the rounds.

	If the marker in on the last year the game ends and the winner is the player with most money.

	Otherwise the player with the **steering wheel** passes it to the player on her left and a new year starts.

### End game

The game can end before the 10th turn if all fish is harvested or after 3 consecutive turns with scarce harvest. 

In this cases *everybody loses*.