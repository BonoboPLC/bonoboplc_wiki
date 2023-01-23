---
title: System Configuration
description: How to configure your lottery platform to meet your needs
published: 1
date: 2023-01-23T07:53:25.325Z
tags: configuration, system
editor: markdown
dateCreated: 2019-11-07T18:23:16.027Z
---

> **Please contact your Account Manager for access to this content.**
{.is-warning}


# System Configuration

## Account Management
### Account Details
### Monthly Statements
### Monthly Invoices
## Account Verification
### Verifying your License
### Uploading Documents

## Site Settings
### Support Email & Phone
### Terms & Conditions
### Privacy
## Player Rules
### Age Verification
### ID Verification
### Email Verification
### Two Factor Authentication
### Wagering Limits
### CDD Period & Limit Triggers
### Player Deposit Privileges
### Player Withdrawal Privileges
### Player Betting Privileges

## Agent Rules
### Address Verification
### ID Verification
### Email Verification
### Agent Sales Privileges
### Agent Payout Privileges
### Agent Account Deposit Privileges

## Event Automation
## Batch Jobs
## Web Hooks
## System Integration

## Payment Integration
## RNG Integration

#### Overview of Manual Results Entry 
This feature enables a Game Definition to use external RNGs or physical Draw Machines to 
generate the winning draws and the feed the Draws into a particular game instance. 
This feature should only be used in conjunction with a mechanism which is certified for 
Randomness and fairness. 
This feature utilizes a dual entry verification mechanism to ensure that the correct results are 
entered into the system. Two staff members must independently enter the draw results into 
the system. If the two results matches, then a 3rd staff member must review and approve the 
results. Upon approval and submission, the game will run and prizes will be paid out according 
to the rules of the game. 
NOTE: The only customer in the UK which uses this feature is the Scottish Children’s Lottery. 
They operate solely a direct debit subscription Lottery which runs twice a week. They migrated 
their Lottery platform to us in October 2022. In the migration, for technical/scheduling reasons 
they ended up with two twin games – Game A - for new customers and Game B for old 
customers which were imported. Game A utilizes the Bonobo certified RNG (the one you 
certified). For each draw, when the winning numbers are generated via the RNG for Game A, 
they are then manually fed into Game B so that they share the same result as they are 
effectively the same game, just split due to technical reasons. 

#### Features
1. Available for Lottery & Raffle Games 
1. Dual Entry Verification to maximize accuracy of Draw Result entries 
Two independent staff members must enter the results into the system, which is then reviewed 
and submitted by a 3rd staff. 
1. Version Tracking 
If the two draw results entered by the two Staff do not match, the mismatch is logged 
and a new version of the results is created and tracked by the system 
1. Activity Tracking 
All activity relating to the submission of results for a Game Instance is tracked 

#### Pre-Requisites
1. Manual Entry feature must be enabled 
1. Manual Entry Permissions must be granted to the Staff account 
![manual_entry_perm.png](/uploads/manual_entry_perm.png)
1. At least two Staff accounts with Role “Submitter” must be active 
1. At least one Staff account with Role “Approver” must be active 
1. Game Definition must have Manual RNG enabled 

#### How to enable Manual Results Entry for a Game Definition
1. Pre-Requisites 
a. Staff account must have Admin and Game Management Permissions 
b. Game Must be of Lottery or Raffle 
2. Step 1 - Edit Game (must be Stopped) 
a. Edit Configuration 
b. Set RNG to Manual RNG 
3. Step 2 - Edit Schedule to allow time between closing of ticket sales and draw time. 
a. Set Registration End Delay (in Milliseconds) to at least one hour or sufficient 
time as required by your process. 
b. I.e. Setting 3,600,000 Milliseconds (one hour) will result in the system closing 
registration and restricting ticket sales one hour prior to the scheduled draw 
time. 
4. Step 3 - Start Game 
5. Ticket Sales will be stopped X Milliseconds prior to the scheduled Draw time. 
6. The Game Instance will be listed in the “External RNG listing” section of the Games Menu and will be available for draw result submission following closing of registration 
Bonobo PLC | Requirements Gathering Document 
7. Upon registration closing (3b) , results can be submitted 

#### How to Submit Draw Results for a Game Instance 

1. Navigate to Games -> Search Instances (Ext. RNG) to view the live Games Instances which accept Draw Results by manual entry 
![submit_draw_1.png](/uploads/submit_draw_1.png)
2. Select the Instance to Manage:
![submit_draw_2.png](/uploads/submit_draw_2.png)
3. You are now in the Game Instance Manual Entry detail view 
From here you can 
a. View the state of the RNG 
b. Access Game Instance Detail 
c. View the Entry Activity 
d. Submit RNG Entries
![submit_draw_5.png](/uploads/submit_draw_5.png)
4. Click on “Submit RNG” button listed on the most recent Version number. 
Versions are created for each pair of results submitted by the two staff 
If there is a mismatch between the two submitted results a new version is created 
and ready for entry. 
Results can only be submitted once a pair of matching entries are entered by the 
two staff.
5. Enter the Draw Results 
a. Enter The Results 
![submit_draw_6a.png](/uploads/submit_draw_6a.png)
b. Confirm the Results
![submit_draw_6b.png](/uploads/submit_draw_6b.png)
6. REPEAT STEPS BY OTHER STAFF 
Step 2-6 must be repeated by another staff member. The results of the entry has to 
match. If the results do not match, both staff must be repeat steps 2-6 again, 
submitting to a new draw result version. 
7. The Staff which has “Approval Permission” can now Approve and Submit the 
results 
a. Navigate to the Game RNG result instance 
b. Click Approve & Submit
![submit_draw_8b.png](/uploads/submit_draw_8b.png)
c. Review the Results and submit
![submit_draw_8c.png](/uploads/submit_draw_8c.png)
d. Confirm Step 1
![submit_draw_8d.png](/uploads/submit_draw_8d.png)
e. Confirm Step 2
![submit_draw_8e.png](/uploads/submit_draw_8e.png)
8. Results are now Submitted and the game will play 
![submit_draw_9.png](/uploads/submit_draw_9.png)
## System Emails

## Custom Pages
### Creating Pages
### Editing Pages
### Assigning Pages to Menu

## Site Designer
### CSS
### Javascript
### REST API
## Applications

## Currency Settings
## Languages

