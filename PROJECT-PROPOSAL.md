Project Proposal: Subscription Cost Splitter and Payment Tracker

1. Project Title

Billing tracker and payment distributor

2. Problem Statement

Many people share subscription accounts with friends or family members to reduce expenses. However, dividing the total subscription cost equally and keeping track of each person's payments can be difficult. Some users may forget when they last paid or when their next payment is due. This project aims to solve these problems by creating a simple program that calculates each user's share of the subscription cost and records their payment information.

sources:
https://www.reddit.com/r/Adulting/comments/1ouv5c9/whats_your_system_for_managing_bills/  (A user talks about how billing can become a hassle in adulthood)
https://culi.app/articles/bill-payment-timing/ (Talks about how people can struggle with deadlines rather than the payment itself)

3. Objectives

- Calculate the total subscription cost per person based on the number of users sharing an account.
- Record the number of people using a subscription.
- Make subscription cost sharing more organized and convenient.

4. Planned Features

- Subscription Details: Allow the user to enter the subscription name and total cost.
- User Count: Ask how many people are sharing the subscription.
- Automatic Cost Division: Divide the total subscription cost equally among all users.
- Payment Records: Record each user's name, last payment date, and next payment date.
- Payment Status: Indicate whether a user has paid or still needs to pay.
- Menu System: Allow users to add subscriptions, view records, update payments, and exit the program.

5. Planned Input/Output

Input:

- Subscription name
- Total subscription cost
- Number of users sharing the account
- Next payment dates
- Payment status

Output:

- Subscription details
- Total subscription cost
- Number of users
- Cost per person
- Each user's payment history
- Next payment date

Example:

If a subscription costs ₱600 per month and is shared by 4 people:

- Total subscription cost: ₱600
- Number of users: 4
- Cost per person: ₱150

The program will also display the next payment dat  and payment status.

6. Logic Plan

1. Start the program.
2. Display the main menu.
3. Ask the user to choose an option.
4. If the user selects Add Subscription:
   - Ask for the subscription name and total cost.
   - Ask how many people will share the account.
   - Calculate the cost per person by dividing the total cost by the number of users.
   - Save the subscription and user records.
5. If the user selects View Records, display the subscription details, cost per person, and payment records.
6. If the user selects Update Payment, allow the user to update the last payment date, next payment date, and payment status.
7. If the user selects Exit, terminate the program.
8. Otherwise, display an invalid-choice message and return to the main menu.

Formula:

Cost per person = Total subscription cost ÷ Number of users

The program must also check that the total cost and number of users are valid before performing the calculation. 

