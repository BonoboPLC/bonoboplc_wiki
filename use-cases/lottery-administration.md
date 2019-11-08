---
title: Lottery Administration FAQ
description: 
published: 1
date: 2019-11-08T11:14:15.000Z
tags: 
---


# How can I see all the changes made to a Player account?
A players account can be affected in many ways.

A player can make changes to their own account by updating their address, settings, password or responsible gaming settings.

A player or admin can make similar changes to the account such as updating their address, verifying a player or placing restrictions on the account.

The system might also make changes to a players permission, player class or segment based on an action taken by the player.

All three types of actions are tracked and available for review by taking the following steps:

1. Navigate to **Players** from the left hand navigation menu
2. Search for the player you are looking for
3. Click on the username to view the details of that player
4. You will now be in the players detail view where you can see all system information about a particular player
5. Scroll down to the last set of tabs
6. There you will find the History, Player Audits and Agent Transaction tabs
7. Each is described below

## Player History tab

The Player History tab enables you to see every action that a Staff member has performed on a players’ account. 
For example if a Staff member has verified an account or disabled a players access or permissions.

To view this tab, navigate to the players profile page and scroll all the way to the bottom. 

The History tab displays all Staff actions including, but not limited to changes to Player Verification settings, Contact details, responsible gaming limits, account credits, CDD Email requests and password resets. 

This feature is key for managing a players’ account and any respective changes that were made to the account by admin Staff.

Please note that this differs from any actions which are either taken by the Player or by the Platform in response to a Player action/event. These types of actions are logged in the Player Audit Tab and not the History tab. 


## Player Audits

The Player Audits tab enables you to see every action that is taken either by the Player or automatically by the Platform, in response to a Player action/event.  

To view this tab, navigate to the players profile page and scroll all the way to the bottom. 

The Player Audit tab tracks all Player actions with respect to their account, including any changes to Responsible Gaming Limits, address and email updates. 

This feature is key for managing a players’ account and understanding when and how the player registered and/or changed their account details.

## Player Agent Transactions

The Agent Transactions tab enables you to see every interaction that the Player has had with any of your Agents. This includes registration, ticket sales, account deposits, checking of any tickets, payouts and any data collection which might have occurred.

To view this tab, navigate to the players profile page and scroll all the way to the bottom. 

This feature is key for managing a players’ account and understanding how and when the player interacted with your Sales Agents and exactly what occurred in the process.


# How can I see the changes made to a Raffle Template?

You can view granular details about the changes made to a Raffle Template by clicking on the “History” link shown on the top right corner of each Raffle game. 

The History tab includes any all changes that were made to a game including but not limited to:

•	Buy-in and Rakes
•	Tickets & Prizes
•	Payout Distribution
•	Schedule
•	Description & Rules

This feature is key for identifying any changes made to any Raffle Template by your Staff.

1. Navigate to **Games** -> Raffles from the left hand navigation menu
2. Look for the Raffle Game you want to check on
3. Click on the "History" link shown on the top right corner


# How can I check the activity of Staff?
You can view granular details about a Staff’s activity by going to the staffs’ profile page and navigating to the Actions tab.

Here you will be able to see a detailed, chronological record of all the Staff’s activity on your platform.
This includes anytime they view, edit, create or modify a player, agent, staff or game.

This feature is key for monitoring staff actions to ensure accountability and integrity of the systems operations and key configuration settings.

1. Navigate to **Staff** from the left hand navigation menu
2. Search for the Staff member you wish to check on
3. Click on the Staff members' username
4. Navigate to the bottom of the page and click on "Actions"

## How can I check changes made to a staff members account?

You can view granular details about the changes made to a Staff account in the History tab. 

This includes any changes made to Staffs profile, permission and access levels.

This feature is key for identifying any changes made to the users account.


# How can I check that games are paying out properly?

The system contains a mechanism to continusly check each games payout to ensure that all prizes are paid out and that the [Return to Player (RTP)](/administration/games/lottorace#return-to-player) of the game is as configured.

To perform this check, please follow the easy steps below:

1. Navigate to **Reports --> RTP ** from the left hand navigation menu
2. Any games which do not have RTP equal to configured RTP will show up on this list
3. This includes any freeroll games as shown below as the game pays out more than it takes in. Conversely, the RTP report would also flag games which are not paying out as much they take in via buy-ins.

![Report Payouts](/uploads/report-payouts.png "Report Payouts")

# How can I check that outcomes are random and evenly distributed?

The system contains a mechanism to continusly check each that the outcomes produced by the RNG are evenly distributed and random.

This mechanism works in the following way:

For each game, we sample and examine the results for 3 play indexes; The 1st, 2nd and 3rd plays purchased into each game instance.
If the results are true random, then so should the distribution of winners, meaning that over a sufficient sample of games, the 1st, 2nd and 3rd plays in the game will each win an equal number of times. 

For example if the game was run over 1,000 times, then we should see the same number of wins, on average, occurring in the 1st, 2nd and 3rd play in the game.

The higher the number of times that game has run, the higher the sample size and the higher degree of confidence with which we can assess the results.

To view the "Fairness" report, please follow the easy steps below:

1. Navigate to **Reports --> Fairness ** from the left hand navigation menu
2. All active games in the system will be listed here as shown below.
3. If the number of "Games counted" is high, then Play index 1, 2 and 3, should be very close to the average. We measure this difference by the deviation each position has from the average. 
4. If the game is paying out fairly, then the deviation amongst the indexes will be very low
5. Be careful to ensure that  game has been counted sufficient times before judging the deviation and results

![Fairness Standard Deviation](/uploads/fairness-standard-deviation.png "Fairness Standard Deviation")

# How can I verify system components?
The system contains a mechanism which allows any user to verify and authenticate the validity of the software packages currently running on the server.

This is done by comparing the SHA256 signature of apps running on the server to the signature of verified apps uploaded by and created by our team.

To perform this check, please follow the easy steps below:

1. Navigate to My Company -> Applications
2. The verification checks will start running on load
3. Signature of the apps currently running on the server will be compared against official releases
4. An email indicating the results will be sent
5. If the signatures match on all applications and on all nodes in the cluster the application can continue
6. If any of the signatures fail to match, then the platform server will be shutdown, restricting all access to system components
![App Verification](/uploads/app-verification.png "App Verification")

