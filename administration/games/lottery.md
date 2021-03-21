---
title: Lottery Games
description: Create a custom Lottery 
published: 1
date: 2021-03-21T09:10:28.279Z
tags: 
editor: markdown
dateCreated: 2019-11-07T14:20:28.807Z
---

# Lottery Games




## Traditional vs. Instant Lotto

There are 2 different types of Lotteries you can have.

A traditional scheduled Draw which accepts many entries and runs at a specific time,  or an Instant Lottery which starts as soon as a single player enters the game.


| Traditional Lotto  |   Instant Lotto | 
| ------ | ------ | 
| ![Weekly Lotto](/uploads/weekly-lotto.png "Weekly Lotto"){:height="100px" width="100px"} | ![Instant Lotto](/uploads/instant-lotto.png "Instant Lotto"){:height="100px" width="100px"} |



## Pick Range & Bonus Balls

You have complete flexbility over the number combinations in your game.

You can have up to 6 numbers between 1 and 70 for your primary range.

You can also have up to 2 numbers between 1 and 70 for your Bonus balls.


![Pick Size](/uploads/pick-size.png "Pick Size")


> **Usage Note:** if you are using custom [pick size + Buy-in]  combinations, then your custom [Payout Table](/administration/games/lottery#payout-table) must be manually configured by us before first use. Please contact us to do so.
> {.is-info}

## Ticket Price

The Ticket Price paid by the player consists of the Buy-in and the Rake.

You can easily set the Buy-in and Rake when creating your game.

![Change Buy In](/uploads/change-buy-in.png "Change Buy In")


### Buy-in

The Buy-in is the portion of the Ticket Price that is reserved to pay for prizes and is added to the Game Trust account.


> **Usage Note:** if you are using custom [pick size + Buy-in]  combinations, then your custom  [Payout Table](/administration/games/lottery#payout-table) must be manually configured by us before first use. Please contact us to do so.
{.is-success}


### Rake Fee

The Rake Fee is the portion of the Ticket Price that is set aside as commissions and is added to the Game Commissions account.

> **Usage Note:** If there isn't enough funds in the Game Trust account the deficit will be taken from the Commissions account to pay player prizes. In this case the Commissions account can go into the negative.
{.is-success}

## Payout Table

You can create custom payout tables for each number range/ticket price combination.

For example you can have Payout table A a 6/49 game with a $2 buy-in and Payout Table B for a 6/49 game with a $1 buy-in.

Sample payout table for a 6/49 + 2/11 Bonus pick game are shown below.

| Sample Payout Table | | 
| ------ | ------ | ------ | 
| Match 6 + 2 Powerballs | Win $1M |
| Match 6 + 1 Powerball | Win $500k |
| Match 6 | Win $100k |
| Match 5 | Win $5,000 |
| Match 4 | Win $1,000 |
| Match 3 | Win $100 |
| Match 2 | Win $2|


### Guaranteed Pays

The amount shown in the payout table are guaranteed to be paid out to the ticket holder in the event of a win. 

This is irrespective of how many tickets are actually sold and if there are adequte funds to cover the prizes.

Please take care to have sufficient funds to pay prizes, no matter how unlikely the odds.


## Prize Rollover

Enabling Prize Rollover on a game allows the Jackpot  to continue increasing with each entry by an amount equal to the Buy-in.

If this is not enabled, any monies left in the Game Trust account after prizes are paid are reclaimed and moved to the Commissions Earned account.


> **Usage Note:** Note that the Jackpot will only increment beyond the Jackpot show in the payout table if the actual net proceeds are greater.
{.is-success}

If there 

> **Usage Note:** Enable Prize Roll over if you want the jackpots to indefinitely increase until someone has won it.
{.is-success}


## Accounting Workflow

The following is a description of the movement of funds within the player and system accounts for Lottery games.

The following System Accounts are used in the process:

**Player Trust account**
The account which hold the players/tickets balance

**Game Trust account**
The account which holds the prize pool funds

**Commissions Earned account**
The account which holds the earned commissions from all games



The process starts when Player pays the total Cost of the ticket which consists of the Buy-in and the Rake.

The Buy-in  is transferred to the Game Trust account upon sale. This amount should be caliberated to cover the prizes as defined in your payout table. (Not to worry if it doesn't)

The Rake is transferred to the Commissions Earned account.

At the end of the game, the prizes are paid from the Game Trust account to the Player's Trust Account

>  If there isn't enough funds in the Game Trust account 
{.is-warning}

Then money is transferred back from the Commissions Earned account to the Game Trust account to cover the deficit.

> If there are excess funds in the Game Trust account
{.is-info}

**If Prize Roll over is enabled**, then the funds are left in the Game Trust account and allowed to build.
This lets you have an ever increasing Jackpot until it's won.

**If Prize Roll over is disabled,** then any excess funds are recovered back in to the Commissions Earned account.


## Random Number Generator

All Lottery games use our Random Number Generator which is indepently tested and certified by a third party.

You can alternatively setup feeds to use your own RNG, manual draws or other sources.








