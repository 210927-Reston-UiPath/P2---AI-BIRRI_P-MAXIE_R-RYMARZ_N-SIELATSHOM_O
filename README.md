# P2---AI-BIRRI_P-MAXIE_R-RYMARZ_N-SIELATSHOM_O
------------------------------------------------

**Project #2 - P2STOCK**

**Overview (To Be Updated)**
The Best Return

What: P2STOCK is an automation application that allows its’ user to buy and sell stock. With additional features.

How: P2STOCK searches and optimizes buying and selling options. Picking the result that will give its user the best return.

Importance: P2STOCK allows users to step away from their Stock Portfolio, letting the automation buy and sell stock without user input. This feature is especially useful to those who do not have the desired time or know-how to buy and sell stock. 

----

**Workflow Goal**: The goal for this automation is to reflect the following workflow.

(Workflow Condition: Can only Buy and Sell from time x to time y)

**Login**

Use Customer Database to input Customer information (User Name and Password)

**Stock On Hand**

View Stock List On Hand

**Lookup New Stock**

View Updated Stock List

**Compare Stock**

Comparison of Stock via Stock List (Condition: 5m)

**Buy or Sell**

Buy or Sell stock based on comparison

**Return to Stock On Hand**

Return to View Stock List On Hand

**User Stories**
---

User is able to View Stock Options

User is able to see application results at the end of the day

User is able to receive end of day report by email

User Buys and Sells Stock without being at their computer

MVPs
--------------

- [ ] Bot is able to Buy

- [ ] Bot is able to Sell

- [ ] Bot Scrapes Porfolio Page 

- [ ] Bot Scrapes Research Page

- [ ] Bot compares and evaluates stock based on the information gathered from scraped data

- [ ] Psuedo Unattended Bot is able to start and end using Orchestrator (Condition: Loop every 5m)

**Stretch Goals**
--------------
- [ ] Program is able to suggest stock options to user

- [ ] User is able to remove stock options that reach a certain level (negative)

- [ ] User is able to Initiate transaction process as a bulk transaction for Multiple Clients

- [ ] User is able to send out multiple emails after bulk transaction process

- [ ] User is able to receive end of day report in PDF format (Using PDF Automation - Transfer Excel Graph Data into PDF Format)

- [ ] User is able to receive Email graph data to a client 

**Constraint**
--------------
Websites:

* Utilized the investopedipa website: https://www.investopedia.com/simulator/

* Using a State Machine

* Using Data Scraped Data to Buy and Sell(transaction) as a single client (Selecting the five best options out a pool of 20 stock options)

* Using Excel - Exporting the final report as a graph

* Timed Conditions(Start at x time, end at y time, Restart program at time z)

	Note: The purpose of timed conditions is to create a fully automated application that does not require manual input

**Tech Stack**
-------------

UiPath Studio

Orchestrator

PostgreSQL/SQL Server(Azure)

