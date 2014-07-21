Moving-Freshdesk-tickets-to-Zendesk
===================================
Moving tickets from Freshdesk to Zendesk

Log-In credentials
===================================
Go to lines 351-357 and put in your log-in ID's for Freshdesk and Zendesk. Company name is important for the program to accurately export and import the tickets to the right account

Storing the JSON files
======================
Create a "fcashe" file in the same directory as your program resides. This is where the tickets are stored locally for the program to export into Zendesk. 

Type Migration
==============
line 377 has a type migration field. You will need to make sure these line up one to one with your Freshdesk and Zendesk type fields. I only had to use Questions, Incidents, and Problems. The Left side of the colon are the types from Freshdesk. The right side is where that field will reside in Zendesk. These words have to be the same letter by letter (s and no s make a different). You can created more custom fields, just make sure to spell the right one.

Number of tickets
==================
the last line, 384, has the number of tickets one would want to migrate. Just change the number inside the parenthesis to the number of tickets that need to be migrated.

