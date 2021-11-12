# P2---AI-BIRRI_P-MAXIE_R-RYMARZ_N-SIELATSHOM_O
------------------------------------------------

**Project #2**

**Overview**

_The Best Return_: User will make the most out of investments. 
This will occur through an automated process that will optimize their options concerning Stock.
Allowing customers to buy and sell optimized stock options.

_What_: P2STOCK is an automation application that allows its’ user to buy and sell stock. With additional features.

_How_: P2STOCK searches and optimizes buying and selling options. Picking the result that will give its user the best return.

_Importance_: P2STOCK allows users to step away from their Stock Portfolio, letting the automation buy and sell stock without user input. This feature is especially useful to those who do not have the desired time or know-how to buy and sell stock. 

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

MVP
--------------

Bot is able to Buy - Complete

Bot is able to Sell - Complete

Bot Scrapes Porfolio Page - Complete

Bot Scrapes Research Page - Complete

Bot compares and evaluates stock based on the information gathered from scraped data - Complete

Psuedo Unattended Bot is able to start and end using Orchestrator - Complete

**Stretch**
--------------
Program is able to suggest stock options to user - Complete

User is able to remove stock options that reach a certain level (Top 20) - Complete 

User is able to Initiate transaction process as a bulk transaction for Multiple Clients - Incomplete

User is able to send out multiple emails after bulk transaction process - Complete

User is able to receive end of day report in PDF format (Using PDF Automation - Transfer Excel Graph Data into PDF Format) - Incomplete

User is able to receive Email graph data to a client - COmplete

**Constraint**
--------------
Websites:

Site #1
https://www.investopedia.com/simulator/

----

Using a State Machine

Using Data Scraped Data to Buy and Sell(transaction) as a single client (Selecting the five best options out a pool of 20 stock options)

Using Excel - Exporting the final report as a graph

Timed Conditions(Orchestrator Trigger)

	Note: The purpose of the Orchestrator Trigger is fully automate the application that does not require manual input
