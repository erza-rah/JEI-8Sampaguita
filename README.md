# JEI-8Sampaguita

##Project title:  simple date reminder 

##Project desc.: This program reminds the user about dates they have inputted in before hand so they wont forget it.
##Features:
-Enter date
-Asks for another date (again and again up until the user's goal/s are/is satisfied) using a loop
-Relates it to a clock
-When the date arrives, the program may notify you
-Handles input value errors

##How to run progam
1. Make sure you have Python installed.
2. Download 'Date_reminder.py'
3. Open a terminal/command prompt.
4. Run the program by either pressing run on the screen or f5 on your keyboard.
5. Proceed with the program as it guides you.

##example output
Enter a date [mm/dd/yy]: 8/19/23
Enter a reminder for 8/19/23: TEST CODE RUN
Would you like to input another date? [y/n]: n

*on date

Reminder for 'TEST CODE RUN' for today, set on [date when the reminder was made]
Goodbye!


##Contributors (before starting on the project):
-Legion [wrote this entire thing]
-Guevarra [responsible for this entire idea]
-Acorda [emotional support]

Simple Reminder Application

Problem Statement: Reminders are more likely to be forgotten in 3-4 hours. People in general forget information is 1 hour or more. This can affect learning, important meetings, or that wedding you were invited to a few months ago. In general, reminders are crucial for understanding and learning.

Project Objectives: 
To give important reminders for those that the user needs that is timely and relevant.
To make time management more manageable in everyday learning.

Planned Features:
An input date and time of reminder system
A settings menu to toggle anything that the user may not like.
A notification system for when the date of reminder comes
A schedule system.

Planned Inputs and Outputs:
Input Date and time = Output reminder for said date and time
Input settings toggle = output change of said setting for user convenience
Input to show schedule = Output schedule with reminders

Logic Plan:
START 
Output “Hello! What do we want to do today?”
Output “a. Schedule /n b. Reminder /n c. Settings”
Input choice 
If choice = a 
Output schedule
If choice = b
Output “Enter date and time”
Input dt
#WHEN SAID DATE AND TIME COMES 
Output “Ding dong! Reminder to do this.”

If choice = c 
Output “What setting do you want to change?”
Input settingchange
Output “Okay!”

END

#CHANGELOG

This file contains all the updates to our simple date reminder project. 

---

## Version v1.2.0 – August 21, 2025
- Added feature to input dates and times. 
- Changed first output statement
- Fixed date and time mix up. 

---

## Version v1.1.0 – August 30, 2025
- Added option to input multiple times in one day. 
- Fixed the error with inputting multiple times in one day. 

---

## Version v1.0.1 – July 22, 2025
- added option to either notify with a sound or a vibration. 
- fixed volume bug that made it too loud. 

---

## Version v1.0.0 – July 15, 2025
 - added option to input multiple dates
- User can:
  - Enter a date
  - on set date, device will ring loudly.
  - has an option to do multiple dates. 
