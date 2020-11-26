---
title: LottoRace Admin Guide
description: 
published: 1
date: 2020-11-26T17:32:45.836Z
tags: 
editor: markdown
dateCreated: 2019-11-07T14:20:30.303Z
---

LottoRace is a player vs. player  multi-draw Raffle game that offers Guaranteed winners in every game.

LottoRace games can be played in Tournament, or Instant Game format with any number of entries (100K+).

All LottoRace games offer guaranteed wins; The draws continue until the entire prize pool is paid out to players.

Revenue is earned by charging a small Rake Fee on each entry.

You can use pre-configured games, or create your own unique games by tweaking any one of the many configuration paramaters available to you.

# LottoRace Rules

## How to Play LottoRace:

Each Line can be entered into the game by selecting the numbers and paying the fee(s). When the game starts, each Line will be competing for a share of the available prize pool in the game.

## How to Win in LottoRace:

The objective is to match all the chosen numbers in a Line with the numbers drawn in each successive Draw. All matches are carried forward to the next Draw and do not need to be matched again. 

Once a bet has matched all of its numbers, it will receive the next available prize.

The draws continue until all prizes are paid out.

**Sharing Prizes**

If 2+ lines win on the same Draw, then all prizes are split equally between the winning lines.

Refer to the payout table for the estimated prize distribution for each rank in the game.
Return To Player (RTP) for each game can be calculated as RTP = X/(X+Y) where X is the buy-in and Y is the fee for each bet.

# Games
Here are some of the pre-configured games that are included in your Games Library.

| |||
| ------ | ------ | ------ | 
| ![50 50 Small](/uploads/50-50-small.png "50 50 Small"){:height="100px" width="100px"} | ![The Daily](/uploads/the-daily.png "The Daily"){:height="100px" width="100px"} | ![Winner Take All Plus](/uploads/winner-take-all-plus.png "Winner Take All Plus"){:height="100px" width="100px"} |
| ![1 In 5 Winsplus](/uploads/1-in-5-winsplus.png "1 In 5 Winsplus"){:height="100px" width="100px"}  | ![1 In 3 Winsplus](/uploads/1-in-3-winsplus.png "1 In 3 Winsplus"){:height="100px" width="100px"} |  ![1 In 2 Wins Plus](/uploads/1-in-2-wins-plus.png "1 In 2 Wins Plus"){:height="100px" width="100px"}  |    
| ![Top 5 Win](/uploads/top-5-win.png "Top 5 Win"){:height="100px" width="100px"}  |  ![1 In 4 Wins](/uploads/1-in-4-wins.png "1 In 4 Wins"){:height="100px" width="100px"}   | ![The Hourly Plus](/uploads/the-hourly-plus.png "The Hourly Plus"){:height="100px" width="100px"}

## Tournaments vs. Instant Games

LottoRace games can be configured as either InstaPlay instant Games, or Tournaments.


**Tournaments start at a specific date and time**  and can have any number of entries.

**InstaPlay instant Games Starts as soon as the game is full.**


![Tourney Insta](/uploads/tourney-insta.png "Tourney Insta")

## Common Settings

Although there are nearly [50 different configuration parameters](/administration/games/lottorace#advanced-settings) at your disposal, in most cases you only need to change a few key elements to create a unique game.

### [Buy-in & Rake](/administration/games/lottorace#set-buy-in)

This determines how much of the Entry Fee is charged as Rake Fees, and how much goes into the prize pool to be won by players.

It is an important factor which determines profitability for you, and the attractiveness of the prize pool for the player.

### [Odds of Winning & Payout distribution](/administration/games/lottorace#set-odds-of-winning)

Odds can be set in a number of ways for Tournaments and Instant Games.

> Tournament Odds
{.is-info}

1) Fixed Number of Winners:  1, 3, 5, 10, etc..
2) As a Percentage of Plays: 1 in 5

> Instant Game Odds
{.is-info}

Instant Games can have odds as follows:

3) 1, 3, 5, 10, 30, 50, 100 Winners:

This can determines if the game is risky (1 in a million wins)  with large payouts ($1 for a chance at $1M), or less risky with average payouts.  
You can offer Winner Take All game for the risk loving, offering one prize for a field of 100,  or a 1 in 5 Wins game for the risk averse, where there are 20 prizes for a field of 100. 

> **Usage Note:** The odds can also factor into how many lines a player should be able to purchase. 
For example if the odds are 1 in 5, you should allow the player to purchase at least 5 lines so that on average there is at least one positive experience for the player. 
{.is-success}



### [Pick Size & Range](/administration/games/lottorace#pick-size)

Easily create any type of game like a 5/35 where the player picks 5 numbers between 1 and 35.

The pick size impacts the speed of the game and the overall gaming experience of players.

For example if you have a large range and few entries, like pick 6 between 1-49, then it will take many draws before all the prizes are paid out and it could be a long and somewhat boring game.

If you have a small range, like pick 5 between 1-10 combined with a  large number of entries, then the game will finish in very few draws and there will be many shared prizes.

> **Usage Note:** If a  [Progressive Jackpot](/administration/games/lottorace#progressive-jackpot) is added to the game, then the Jackpots odds will implicitly mirror the Pick Size and Range.
{.is-success}

> **Usage Note:** You can also specify  [Bonus Pick](/administration/games/lottorace#bonus-pick) ranges to increase the odds for Jackpots or Lottery games alike.
{.is-success}

### [Min/Max Plays Per Game](/administration/games/lottorace#min-max-entries-per-game) 

The Min and Max play limits enable you to create games of various sizes.  I.e. a 12 player instant game or a 180 player instant game. A tournament with at least 100 participants, or a tournament with no minimum.

Aside from the obvious impact on size, this settng can impact tournaments Prize Pools and wait time between games for instant games.

#### Tournaments
The minimum ticket limit can be used in conjunction with a guaranteed prize pool in order to ensure that the minimum number of tickets are sold to cover the Guarantee.
If the minimum number of entries is not sold, the game can either be set to automatically rescheduled or be cancelled and all bets refunded.


#### Size of Instant Games

In any Instant Game, all the entries must be sold before the game can start. Therefore,  the bigger the game is, the longer players have to wait before all the lines are sold.

These limits can impact the overall experience for players and should therefore take into account traffic volumes and player expectations.

> **Usage Note:** Less is more. Having less games focuses the traffic into fewer games which leads to higher prize pools for tournaments and quicker starts for Instant Games. 
{.is-success}

> **Usage Note:** We recommend having Instant Games with 2, 6, 9, 12, 20, 50, 180, 360 Entries, based on traffic volume.
{.is-success}

> **Usage Note:** Have fewer tournaments, and schedule them for peak times.
{.is-success}


## **Advanced Settings**

Here are the rest of the available configuration parameters.

You do not need to adjust the default configurations and should only do so with care.

### Game Related Configuration

| Game Configuration |||
| ------ | ------ | ------ | 
| [Odds of winning](/administration/games/lottorace#set-odds-of-winning) | [Buy-in](/administration/games/lottorace#set-buy-in) | [Rake Fee](/administration/games/lottorace#set-rake-fee) |
| [Pick Size](/administration/games/lottorace#pick-size) | [Bonus Pick](/administration/games/lottorace#bonus-pick) |  [Tournament vs. Instant](/administration/games/lottorace#tournaments-vs-instant-games) | 
|   | [Payout Formula](/administration/games/lottorace#payout-formula) |  [Estimated  Prize Pool](/administration/games/lottorace#estimated-prize-pool) | 
| [Guaranteed Prize Pool](/administration/games/lottorace#guaranteed-prize-pool) | [Multi-Currency](/administration/games/lottorace#set-currency) | [Seed Prize Pool](/administration/games/lottorace#prize-pool-seed) | 
| [Min/Max Plays Per Player](/administration/games/lottorace#min-max-entries-per-player) | [Min/Max Plays](/administration/games/lottorace#min-max-entries-per-game) | Subscription | 
| Prize Roll Over | Failover Handling | Shared Games |   
| [Schedule](/administration/games#setting-game-schedules) | [Repeat Count](/administration/games#repeat-count) | [Available Hours](/administration/games#available-hours) |
|  | [Registration Delay](/administration/games#registration-delay) | [Closeout Period](/administration/games#closeout-period) | 
| Multilingual | HTML Description | Rules text |
| [Ball & Draw Speed](/administration/games/lottorace#ball-draw-speed) | [Narrator Voice](/administration/games/lottorace#game-narrator) | [Live Sorting](/administration/games/lottorace#client-sort-order)  |
| [Game Logo](/administration/games#game-logo) | [Game Background](/administration/games#game-background) | [Playout Background](/administration/games#playout-background) | 
| [Tile Image](/administration/games#tile-image)  | [Tile Color](/administration/games#tile-color) ||



### Progressive Jackpot Settings

| Progressive Jackpot |||
| ------ | ------ | ------ | 
| [Initial Balance](/administration/games/lottorace#initial-balance) | [Matches Required](/administration/games/lottorace#required-matches) | [Eligible Draws](/administration/games/lottorace#eligible-draws) | 
| [Progressive Fee](/administration/games/lottorace#progressive-fee) |  [Reserve Fee](/administration/games/lottorace#reserve-fee) | [Reserve Multiplier](/administration/games/lottorace#reserve-multiplier) |  



### Loyalty Points & Rewards

| Loyalty Points & Rewards |||
| ------ | ------ | ------ | 
| [Loyalty Currency](/administration/games/lottorace#loyalty-currency) | [Earned Per Entry](/administration/games/lottorace#points-per-entry) | [LuckyBall Reward](/administration/games/lottorace#lucky-ball-reward)
| [Number of Lucky Balls](/administration/games/lottorace#number-of-lucky-balls) | [Multi-Win Reward](/administration/games/lottorace#multi-win-reward)|  [Bonobo Reward](/administration/games/lottorace#bonobo-reward) | 
| [Perfect Game Reward](/administration/games/lottorace#perfect-game-reward) |   [Active Status](/administration/games/lottorace#active-status) ||



# Revenue Model 
## How to Earn Fees (Rake)

Revenue is earned by charging a Fee on every entry.




### Rake Fee

The **Rake Fee**  is earned by the Operator (less any **Progressive Jackpot** contribution if applicable).


The Rake Fee is set along with the Buy-in, when creating the game.

The Player is able to see the breakdown on the confirmation page which displays the Buy-in, Rake Fee and Jackpot Contribution as shown below.

![Fee Breakdown](/uploads/fee-breakdown.png "Fee Breakdown")

> **Usage Note:** Any Jackpot Contribution and Jackpot Reserve fees are taken out from the Rake Fee.  For example if the Rake Fee is set to $0.50 and Jackpot Contribution and Reserve are $0.05 and $0.02 respectively, then the actual Net Rake per entry is $0.43.   
{.is-warning}



## Return to Player

The **Return to Player (RTP)** is an important measure of how much is actually paid back to the players in prizes in an average game.

The RTP of each LottoRace game can be calculated as  ***Buy-in/(Buy-in + Rake)***

For example a game where the Buy-in is $10 and the Rake is $1 has an RTP of  10/(10+1) = 90.9% 


> **Use Case:** Highlighting the higher than average RTP  of LottoRace games. 
{.is-success}

> **Usage note:** An average LottoRace player buys 20-30 entries spread over 10-15 games in a session, most of them in InstaPlay games. If the Rake is 10%, then on average, the player will lose one Entry fee, every 10 entries. Due to this high turn over its important that the Rake is not so high such that the players entire bankroll is taken as fees in few games. To extend the players entertainment value we recommend a Net Rake of no more than 10%.
{.is-success}


# Buy-in, Prizes & Odds

### Entry Fee


The **Entry Fee** paid by the player for each LottoRace entry consists of a **Buy-in** and **Rake Fee**.

The total Entry Fee (Buy-in + Rake) is displayed on all top level pages to provide clarity with respect to total cost for the player.

![Entry Fee](/uploads/entry-fee.png "Entry Fee")

> **Use Case:**  Shown on top level navigation for each game 
{.is-success}

## Setting Buy-in & Rake



### Set Currency

The Primary currency of the game, in which all prizes and payouts are denominated in.

The primary Buy-in currency must be the same as this Currency.



### Set Buy-in
 
The **Buy-in**  is contributed entirely to the Prize Pool and is guaranteed to be won in the game.

The Buy-in is critical when determining the target Prize Pool of the game which determines its overall attractiveness.

![Buy In Rake](/uploads/buy-in-rake.png "Buy In Rake")

> **Use Case:** If the Buy-in is set to $10 and your maximum entries are 1000, then your Prize Pool will be a maximum of $10,000
{.is-success}

### Set Rake Fee

The **Rake Fee**  is earned by the Operator (less any **Progressive Jackpot** contribution if applicable).


### Secondary Currency

The secondary currency of the game which can be used for Buy-ins.

> **Use Case:**  Loyalty Currency:  "Enter with $2 or 200 Loyalty Points."
{.is-success}
## Payouts & Prizes

There are two components to configuring payouts for a LottoRace game.  

The first is the **number of winners**, and the second is how that **payout is distributed** amongst those winners.

The distribution of prizes is already pre-set for a wide of range of combinations in prize distribution tables.

These pre-set Prize distribution tables are then used to calculate the allocation of prizes for each rank based on the number of winners.

These allocation tables can be customized upon request. 

Prize allocation example: 

|  | 3 Winners | 4 Winners |
| ------ | ------ | ------ | 
| 1st Place | 50% | 40% |
| 2nd Place |  35% |  25% |
| 3rd Place |  15% |  20% |
| 4th  Place |  N/A |  15% |


### LottoRace Tournaments

The number of winners/prizes in a LottoRace Tournament payouts can either be fixed, or defined as a percentage of the total entries in the game.

This helps you configure a prize table, when the number of entries is unknown and can vary, as a tournament can.


#### As a percentage

For example, you can set the number of winners to 1 in 20 , which means that 1 in 20 plays in the game will win a prize, regardless of the number of entries.

Pre-set Prize distribution tables are used to calculate the allocation of prizes to each generated rank.
Instant Game prize allocation tables can be customized upon request.

![Tournament Winners](/uploads/tournament-winners.png "Tournament Winners")

> **Usage Note:** If a Tournament pays 1 in 20 and has 2,500 entries, then the prize allocation table corresponding to 125 winners will be used.
{.is-success}


#### Fixed Winners

Alternatively you can set a fixed number of winners, i.e. 5 winners, regardless of the number of entries.

Meaning that if a 1,000 entries were in the game, there is only 5 prizes, which will continue to grow as more players join.

> **Usage Note:** If a Tournament pays 5 and has 2,500 entries, then the prize allocation table corresponding to 5 winners will be used.
{.is-success}

![Fixed Winners](/uploads/fixed-winners.png "Fixed Winners")

### LottoRace Instant Games

The number of winners/prizes in a LottoRace Instant game is explicitly set and should take into account the total number of entries available in the game.

For example, if you have a 20 line game and want to offer 1 in 5 odds, then you should set the number of winners to 4.

You can choose from any number of winners in an Instant Game ranging from just 1 winner up to 60 winners.


![Instant Winners](/uploads/instant-winners.png "Instant Winners")

> **Usage Note:** If a Instant Game pays 10 plays and there is 360 entries, then the prize allocation table corresponding to 10 winners will be used.
{.is-success}

### Guaranteed Prize Pool

This setting is used to guarantee a minimum value for the prize pool.

If the sum of all the Buy-ins do not equal or exceed this value before the start of the game, the prize pool will be supplemented by the difference.

If the sum of all the Buy-ins exceed this value before the start of the game, no additional supplements are made to the prize pool.

> **Use Case:**  The Guaranteed prize pool is displayed to players from the moment that the game is turned on . If the actual prize pool exceeds the guaranteed prize pool then the prize pool which is displayed to players will increment up by the value of the Buy-in for each entry thereafter.
{.is-success}

> **Usage Note:**  If the Guaranteed prize pool is $1000 and only $900 in buy-ins have been contributed, then an additional $100 is contributed from Guaranteed Games Expense account to the prize pool of the game.
{.is-success}

### Estimated Prize Pool

This is your estimated prize pool based on the number of entries you expect to have in each game.

This is the displayed prize pool as soon as the game is turned on. It helps you show a non-zero prize pool in order to make the game attractive to the first few entrants.

Once the actual prize pool exceeds the Estimated Prize Pool or the Estimated no. of Players is reached, then the actual prize pool will be displayed and the text "Estimated Prize Pool" will change to "Guaranteed Prize Pool"

### Prize Pool Seed

This enables you to seed the prize pool by starting it a specific amount. 

This amount is guaranteed to be added to the prize pool regardless of number of entries and is done so as soon as the game is turned on. 

This is different from setting a  Guaranteed Prize pool which only adds the difference between the Guaranteed amount and the actual prize pool once registration is closed.

### Estimated Players

The estimated number of players in the game.  See Estimated Prize Pool for usage.


# Basic Configuration

### Pick Size 


Defines the number range and the pick size for each game. 

For example a 5/20 Game is defined as Pick 5 numbers between 1 and 20.
Games can have a pick range up to 6 numbers between 1 and 60.

![Pick Size](/uploads/pick-size.png "Pick Size")

### Bonus Pick 

Defines the secondary number range and pick size for each game.

For example; pick 2 between 1 and 12 for the bonus range.

> **Usage Note:** You can create a game like Euromillions by  setting a 5/50 Pick Size and 2/12 Bonus Pick
{.is-success}

### Min/Max Entries Per Game

> Minimum Entries
{.is-info}

The minimum number of entries that a Tournament must have in order to start.  This value should take into account the number of prizes available or the Guaranteed prizes.

> Maximum Entries
{.is-info}

The total number of entries avaialble for sale in game.
In **Instant Games** the max and min are the same since Instant Games always start when all the available entries are sold.

> **Usage Note:** You have a tournament where there is a fixed number of prizes, i.e. 5;  then the minimum number of entries must be at least 5. 
{.is-success}





### Min/Max Entries Per Player

The minimum and maximum number of entires/tickets which can be sold to a single player.


### Allow Subscriptions

If enabled, registered players can repeat their picks in future games.

> **Usage Note:** A player can choose their lucky numbers, and then pre-pay for the next 5 draws.
{.is-success}

> **Usage Note:** Subscriptions cannot be sold to anonymous bearer tickets, they can only be sold to Registered players.
{.is-warning}

# Progressive Jackpot

Progressive Jackpots are an add-on to a standard LottoRace game.

By adding a Progressive Jackpot to Lottorace games you can give players a second chance to win, in every game!

**Here is how it works:**

The Progressive Jackpot accumulates through small contributions made from each entries Rake Fee.

The Jackpot can be won by matching all or some of the numbers in a single draw. 

You can configure this feature to offer easy Jackpots which are hit often, or hard Jackpots which are seldom hit but offer large prizes.

By combining Jackpots and the standard LottoRace game, players can enjoy good odds and guaranteed wins on the LottoRace portion, whilst at the same time being able to go for the large Jackpot prize.



## Jackpot Settings

The following settings must be configured when adding a Progressive Jackpot to a game.

### Initial Balance

This is the initial balance of the Jackpot and will be funded by debiting the Jackpot Reserve account and crediting the Progressive Jackpot.



### Jackpot Balance

Balance of the Jackpot at this moment in time. 

### Jackpot Reserve

Jackpot Reserve is the account which funds the Initial Balance of the Jackpot when its first started or after it has been won.

When the game is turned on for the first time, expect the Jackpot Reseve Account to go into the negative by the same amount as the Jackpot Initial Balance.

As each entry is placed, an amount equal to the** Jackpot Reserve Fee** is taken from the Rake Fee and credited to the Reserve Account. 

This process gradually replenishes the **Jackpot Reserve Account** so that the initial balance can once again be funded when the Jackpot is won.

The amount collected in the Reserve account can be controlled and managed by the** Reserve Multiplier** setting.


### Required Matches 

The number of balls that must be matched in ONE single draw in order to win the Prize.

6/6 means match all 6 numbers in one draw to win the Jackpot.


> **Use Case:**  You can make the jackpot easier or harder to hit by adjusting this setting. For example match only 3 out of 6 to win the Jackpot is much easier than matching all 6 to win.
{.is-success}



### Eligible Draws

 The number of draws in which the Jackpot can be won. For example if set to 2, the bet must match the required number of matches in the first 2 draws to be eligible to win


### Progressive Fee 


The amount which is taken from the Rake portion of each entry fee and contributed to the Progressive Jackpot.


### Reserve Fee

The amount which is taken from the Rake portion of each entry fee and contributed to the Progressive Jackpot Reserve.


### Reserve Multiplier

The Reserve Mutliplier places a cap on how much is collected for the Jackpot Reserve account. 
It takes into account how much has already accumulated in the Reserve Account with respect to the **Initial Balance** setting..

For example

> **Use Case:**  Setting the Reserve Multiplier to 3 would enforce the collection of the Reserve Fee up to the point where the Reserve Balance is 3x the Initial Balance. This ensures that there is always enough money to fund the Jackpot after it has been won.
{.is-success}



## Odds & Math

Configuring the Jackpot requires understanding of odds with respect to the Pick Size.

For example, in a 5/20 game the odds of matching all 5 numbers on the 1st draw are 1 in 15,504

Therefore, you should expect 15,504 entries, on average, before the Jackpot is won.

Before you can set the Initial Balance of the Jackpot, you must decide how much from entries Rake will go to the Reserve and Jackpot accounts respectively.

The Initial Balance and Reserve Fee, should be configured so that   IB = Reserve Fee X Odds

For example, if in a 5/20 game, you decide to contribute 5 cents from each entry to the Reserve, then your Initial Balance should be  set to  ($0.05 x 15,504) = **$775.20**

This is easy to understand because on average, you can only set aside and reserve $775 to fund the Jackpot, before the Jackpot is actually won, and must be funded again with the Initial Balance.


# Advanced Settings Only

### Ball & Draw Speed

This setting allows you to control the number of seconds between each ball drawing and consequently the games' pace and speed.

The recommended value for Tournaments  are 3000 ms and 7000 ms for ball and draw delay respectively.

The recommended value for Instant games  are 2250 ms and 5000 ms for ball and draw delay respectively.


> **Use Case:** For an ultra faced paced game combine very fast Ball and Draw Delays (1500/5000) with very small number ranges (Pick 3/10) to create a quick, instant satisfaction game. 
{.is-success}


### Game Narrator

The game narrator which calls out the numbers as they appear.

Male and Female version with an English accent are currently available.

*Custom narrators can be added upon request.*


### Client Sort Order

The order in which the game is displayed on the client

### Fail Strategy 

# Loyalty Points & Rewards
## Loyalty Points

Players can earn Loyalty Points for each entry they purchase. 

### Active Status 

You can enable or disable Loyalty points for each Game Template.

### Loyalty Currency 

This is the currency for your loyalty points.

This could be a real currency, or your own custom currency - i.e. Frequent Player Points.

> **Use Case:**  You can configure games to accept Frequent Player Points for entry. For example enter with $2 or 200 FPP points.
{.is-success}




### Points Per Entry 

The amount of Loyalty points earned for each entry purchased.

> **Use Case:**  For example if this is set to 10 and the loyalty currency is FPP, then the player will earn 10 FPP for each entry they purchase.
{.is-success}

##  In Game Rewards 

A collection of interactive bonuses available during the game playout.

The player must be watching the game live, and collecting the bonuses as they are unlocked.

### Lucky Ball Bonus

Some numbers are randomly designated as lucky balls. If a player has selected this number as one of their picks, they get the bonus.

Visually, drawn lucky balls are Red.

When a match is made, the player needs to collect the bonus. The "Collect" button will disappear within 10 seconds or when the draw is over, whichever comes first. 

The player must act fast to collect them as they occur.

### Number of Lucky Balls 

 You need to set the number of balls which are "lucky balls".
 
 You should consider the total size of your Pick Range when configuring this value and be carefull not to have a disproportionately high number of Lucky Balls.
 
 
> **Use Case:**  If you have 10 Lucky balls, with a Pick Range of 30, then 1 in 3 balls will be Lucky Balls and allow players to collect a Lucky Ball Bonus.
{.is-success}


### Multi-Win Bonus
 
Mutli-Win Bonus is awarded when the player wins on Multiple entries.

This is designed to encourage players to have multiple entries in each game.


### Bonobo Bonus

Bonobo Bonus is awarded when the player gets a Bonobo.

A Bonobo is defined as winning 1st place, without any ties; meaning a single winner winning first place.

### Perfect Game Reward 

A Perfect Game bonus is awarded when the player wins the entire prize pool. 
This can happen if there are few prizes to be won, i.e. 3, and the player plays 3 entries which win 1st, 2nd and 3rd. 

> **Usage Note:**  Cannot be in a winner take all game as there is only one prize
{.is-info}


