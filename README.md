# OSTicket-OnHold
Current version of mod: V1.1
Designed for OSTicket: 1.10
Mod was created by: NickTheITGuy
(https://github.com/NickTheITGuy // http://osticket.com/forum/profile/208230/NickTheITguy)

# INSTALLATION

Step 1. 
Create a ticket status in the "Custom lists" tab.
Name this status "On-Hold" and set the state to "Open"

Step 2. 
Open any SQL database program (such as PHPmyadmin) and go to the "OST_ticket_status" table.
In this table, copy the ID of the On Hold status.

Step 3. 
Open the file "tickets.inc.php"
and go to line 96, and change the number to the ID you copied.

Step 4. 
Open the file "tickets.php"
and go to line 361, and change the number to the ID you copied.

Step 5. Upload the attached files to the below specified locations:
- Upload "scp.css" in the folder \scp\css\
- Upload "tickets.inc.php" in the folder \include\staff\
- Upload "tickets.php" in the folder \scp\
- Upload "onhold_ticket.gif" in the folder \scp\images\icons\ 
