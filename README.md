# P2---AI-BIRRI_P-MAXIE_R-RYMARZ_N-SIELATSHOM_O
------------------------------------------------

**Project #2**

Goal - The Best Return: User will make the most out of investments. 
This will occur through an automated process that will optimize their options concerning Stock.
Allowing customers to buy and sell optimized stock options.

Workflow Goal: The goal for this automation is to reflect the following workflow.

(Workflow Condition: Can only Buy and Sell from time x to time y)

**Login**

Use Customer Database to input Customer information (User Name and Password)

**Stock On Hand**

View Stock List On Hand

**Lookup New Stock**

View Updated Stock List

**Compare Stock**

Comparison of Stock via Stock List (Condition: 5m)

**Buy or Sell **

Buy or Sell stock based on comparison

**Return to Stock Owned**

Return to View Stock List On hand

**MVP/User Stories**
--------------
User is able to View Stock Options

Bot is able to Buy

Bot is able to Sell

User is able to see application results at the end of the day

**Stretch**
--------------
Program is able to suggest stock options to user

User is able to remove stock options that reach a certain level (negative)

User is able to Initiate transaction process as a bulk transaction for Multiple Clients

User is able to send out multiple emails after bulk transaction process

User is able to receive end of day report by email.

User is able to receive end of day report in PDF format (Using PDF Automation - Transfer Excel Graph Data into PDF Format)

**Constraint**
--------------
Using a State Machine

Using Data Scraped Data to Buy and Sell(transaction) as a single client (Selecting the five best options out a pool of 20 stock options)

Using Excel - Exporting the final report as a graph

Email graph data to a client 

Timed Conditions(Start at x time, end at y time, Restart program at time z)

	Note: The purpose of timed conditions is to create a fully automated application that does not require manual input
