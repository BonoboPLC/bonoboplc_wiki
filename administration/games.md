---
title: Games
description: A quick summary of Games
published: 1
date: 2020-03-07T18:40:04.226Z
tags: 
---

# Available Game Types

The following game types are currently available on the Bonobo game library.

You can use pre-configured games, or modify them to create your unique and custom game.

Ask us if you need any help with implementing your game ideas.

Click on each game type to find out more. 

|  | | |
| ------ | ------ | ------ | 
|[![lottorace-home-page.png](/lottorace-home-page.png "Lottorace Games"){:height="200px" width="200px"}](/administration/games/lottorace "Managing your Lottery & Raffle Games") | [![lotterya-home-page.png](/lotterya-home-page.png "Lottery Games"){:height="200px" width="200px"}](/administration/games/lottery  "Lottery Games") | [![raffles-a-home-page.png](/raffles-a-home-page.png){:height="200px" width="200px"}](/games/raffles "Raffles ")|


# Common Game Management Info

The topics contained below apply to all game types and should be read by all game managers.

- Using Pre-loaded Game Templates
- How to create a Game
- How to Start & Stop games
- How to set Schedule for your games
- Customizing your game branding and logo

## Game Templates vs. Game Instances

A Game Template refers to the collection of configurations and branding elements that make up a unique Game.

Each Game Template is assigned a unique Game Template ID (also called Game Definition ID) and can be modified and edited. 

When a game is Started, a new Instance of the game is created based on the current configurations specified in the Game Template.

This game is assigned a unique Game Instance ID and is available for players.

> The players will only see references to the Game Instance ID and never to the Game Template ID
{.is-warning}




## Pre-loaded Game Templates
Depending on your installation type, we preload a number of pre-configured Game Templates for you.

You can use these pre-configured games, or clone a copy to use as a starting point for your own custom game.


| |||
| ------ | ------ | ------ | 
| ![50 50 Small](/uploads/50-50-small.png "50 50 Small"){:height="100px" width="100px"} | ![The Daily](/uploads/the-daily.png "The Daily"){:height="100px" width="100px"} | ![Winner Take All Plus](/uploads/winner-take-all-plus.png "Winner Take All Plus"){:height="100px" width="100px"} |
| ![1 In 5 Winsplus](/uploads/1-in-5-winsplus.png "1 In 5 Winsplus"){:height="100px" width="100px"}  | ![1 In 3 Winsplus](/uploads/1-in-3-winsplus.png "1 In 3 Winsplus"){:height="100px" width="100px"} |  ![1 In 2 Wins Plus](/uploads/1-in-2-wins-plus.png "1 In 2 Wins Plus"){:height="100px" width="100px"}  |    
| ![Top 5 Win](/uploads/top-5-win.png "Top 5 Win"){:height="100px" width="100px"}  |  ![Weekly Lotto](/uploads/weekly-lotto.png "Weekly Lotto"){:height="100px" width="100px"}   | ![The Hourly Plus](/uploads/the-hourly-plus.png "The Hourly Plus"){:height="100px" width="100px"}


> Raffles do not have templates and are created through the raffle builder.
{.is-warning}


 ## Creating Game Templates

To create any type of Game Templates, navigate to that game type (Raffle/LottoRace/Lottery) and look for the Create button on the top right corner.

 ![Create Lottery](/uploads/create-lottery.png "Create Lottery")
 

 ## Editing Games
 In order to edit any of the games configuration, make sure the game is stopped.
 
 Then click "Change" on each configuration group.
 
 ![Edit Game](/uploads/edit-game.png "Edit Game")
 
 

> **Usage note:**  The Game Template must be stopped first, before editing any of the games configuration values, with the exception game branding and schedule which can be edited live.
{.is-success}

## Starting & Stopping Games

To manage games, navigate to Games -> LottoRace from the left hand navigation.

![Manage Games](/uploads/manage-games.png "Manage Games")

### Starting Games

Press the Green Start Button to make the game Live on the site.

The game container should immediately appear on both the Play and Stream sites.

![Start Stop 2](/uploads/start-stop-2.png "Start Stop 2")

Registration will be available immediately for Instant Games and based on Registration Delay for Tournaments.

Once the game has been started, new Game Instances will be created as each Game Instance is filled up and runs.


> **Usage note:** If there are any missing configurations, you will see "Incomplete Configuration" instead and get prompts to fix them.
{.is-success}

### Stopping Games

**To stop a game **

1. Set the game to Closed and wait for any open instances to finish
2. Press Stop
3. Confirm that you want to stop the game

![Stopping Games](/uploads/stopping-games.png "Stopping Games")

Pressing Stop will kill any open instances, cancel and refund all bets to player accounts, and prevent any new Game Instances from being created.

Only press Stop when there are no Game Instances  open for registration.

> **Usage note:**  Before stopping a game, set the game to Closed first and wait for open instances to complete
{.is-success}

### Setting a game status to Closed 

This setting is used to gracefully shut down a Game. It prevents any new Game Instances from being created.

In the normal flow, when one Game Instance gets filled up or starts on a schedule, a new one is automatically created for other players to register in. 
Like an hourly game or an instant game that just filled up.

If a game is set to closed, the current open Game Instance will be the last one and no new Game Instances will be created thereafter.  

> **Usage note:** Set the game to closed if you are planning to turn off the game, or as part of gracefully shutting the system down for maintenance and upgrades. 
{.is-success}


 

## Managing Schedule

You can set and update your game schedules at any time, even if the game is already open for registration.

![Scheduler Basic](/uploads/scheduler-basic.png "Scheduler Basic")

> **Usage Note:** If you are updating a schedule for a Game Template, which already has an open Game Instance then you must "Reload" the game for the changes to take place.
{.is-success}



### Start Time

The time at which the first game will start.

### End Time

No new games will be created after this date. Used only when the tournament is repeated.

For example, starts on Jan 1, and repeat every week until May 1st. 

### Repeat Setting

You can easily set how often the game will be repeated. 

For example, Every 5 minutes or every 3 weeks.

### Availablity Hours

You can use this setting to control when the game is available during the day to suite your traffic levels.

For example, Available only between the hours of 4PM to 8PM.


### Registration Start Delay

This value gives you flexibility to display and promote a game, while not permitting registration. 

I.e. New Years game which you want to promote, but not allow players to register yet.

available at  T = Registration Delay minus Start Time

If you want the registration to be available immediately, set registration delay to a very low number 1500 (milliseconds).

If you want to display a game for promotion, but not enable registration for 1 day before the Draw takes place, set the registration delay to 86400000.
Registration will not be available until 


### Registration End

This value enables us to disable new Ticket purchases  a few seconds before the start of the Tournament on the player web site. Its basically a timer on the last entry that can be purchased.

This is necessary so that the system can process and settle all pending transaction and close out game ledgers before the start of the Tournament.

The registration Delay should at least be one second (1000 milliseconds) for most games but should be set to 3 seconds with games with over 20,000 entries or more.

### Max Runs

The maximum number of Game Instances that can be created by this game template.


## Setting Game Logo/Branding

You can customize up to 5 elements to reflect your games branding and image.

These include a Logo, Page and playout backgrounds and color.  

> **Usage Note:** If you are updating any assets for a Game Template which already has an open Game Instance, you must "Reload" the game for the changes to take place on the live instance.
{.is-success}


### Game Logo

Game logos should take into the various placements and sizes in which they will be shown.

Keep logos simple and clear, and without a lot of details which will be lost when the image size is decreased in certain locations.



| Sample Logos |||
| ------ | ------ | ------ | 
| ![50 50 Small](/uploads/50-50-small.png "50 50 Small"){:height="100px" width="100px"} | ![The Daily](/uploads/the-daily.png "The Daily"){:height="100px" width="100px"} | ![Winner Take All Plus](/uploads/winner-take-all-plus.png "Winner Take All Plus"){:height="100px" width="100px"} |


**Usage:**  Shown on  Main Lobby, Game Lobby, Tickets, My Games, Completed Games
**Format:** Transparent PNG is best
**Size:** 300px x 300px
**File Size:** Less than 50kb is recommended


### Lobby Background 

Usage:  Used as page background in Game Lobby and game playout pages.

![Lobby Background](/uploads/lobby-background.png "Lobby Background")

**Usage:**  Used as background image on Game Lobby
**Format:** PNG, JPG
**Size:** 2400px x 1200px
**File Size:** Less than 200kb is recommended

### Game Tiles

Game tiles are used to display games, grouped by Tournaments/Instant Games in the main lobby.

![Tournament Tiles](/uploads/tournament-tiles.png "Tournament Tiles")

You can customize the look and feel of each tile by changing the Tile background and tile color.


### Tile Background & Color

The tile background, shown as the checkered pattern, is placed behind all elements and fills the entire tile.

The tile color, set to red in this example, can be customized to match your logo and tile.

![Tile Bg](/uploads/tile-bg.png "Tile Bg")

**Usage:**  Used as background image of the Game Tiles shown on the main lobby
**Format:** PNG, JPG
**Size:** 350px x 350px 
**File Size:** Less than 200kb is recommended





