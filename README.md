                                                Calendar and Reminder System
 BY:

Avantika Pandey

Roll No: 241033120

Section: 24I11

---Overview---

This project is a UNIX shell script–based Calendar and Reminder System.

It allows the user to:

View a calendar for any given year.

Add reminders or events for specific dates.

View all saved reminders.

Delete any reminder when it’s no longer needed.

All reminders are saved permanently in a text file (reminders.txt), so they remain even after the program ends.

---Functionalities---

View Calendar

Displays the calendar of any specified year using the cal command.

Also shows today’s date and current time.

Supports colored output (pink/magenta for headings).

Add Reminder

User enters a specific date (DD-MM-YYYY) and an event description.

Reminder gets stored in reminders.txt.

View Reminders

Displays all saved reminders in a clean, formatted list.

Delete Reminder

Allows deleting a reminder by entering its exact date.

The system rewrites the file without the deleted entry.

Exit

Safely exits the program.

 ---UNIX Commands Used---

echo - To display messages or text to the user.

read - To take input from the user (like date, event, or choice)

cal	 - To display the calendar for a specific year.

date - To show today’s date and current time.

cat  - To view the contents of the reminder file.

grep - To search for a specific reminder or date inside the file.

sed  - To delete a particular line or reminder entry.

tput - To apply text colors and formatting (for pink text).

if, case, while	Conditional and looping structures used in the script.

sleep -	Adds small delays for smoother user experience.

exit	- Ends the script execution.

---Color Feature---

The script uses:

PINK=$(tput setaf 5)

RESET=$(tput sgr0)

---Files Used---

calendar_reminder.sh → main shell script

reminders.txt → stores all events and reminders permanently.

---ANSI Codes Used in Script---

Variable	                Code	                  Meaning / Effect

PINK	                 \033[1;35m	              Bold / bright magenta text

GREEN	                 \033[1;32m	              Bold / bright green text

YELLOW	               \033[1;33m	              Bold / bright yellow text

RED	                   \033[1;31m	              Bold / bright red text

NC	                   \033[0m	                Reset text color and style to normal

OUTPUT:



<img width="894" height="859" alt="Screenshot 2025-11-17 153327" src="https://github.com/user-attachments/assets/5ecde042-faf2-40ed-9635-58a9431f1c36" />

<img width="1110" height="750" alt="Screenshot 2025-11-17 153428" src="https://github.com/user-attachments/assets/e1690935-1b8a-4b8e-87f4-642c957df7a2" />

<img width="749" height="928" alt="Screenshot 2025-11-03 155829" src="https://github.com/user-attachments/assets/3e4aea6a-627e-4bd2-8a6a-2c5e44624df9" />

<img width="749" height="928" alt="Screenshot 2025-11-02 182330" src="https://github.com/user-attachments/assets/d66e1378-de15-4d43-a6ab-5c4c2d52f08b" />



                                                                                         
