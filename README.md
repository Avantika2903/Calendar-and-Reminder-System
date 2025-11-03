                                                                                      🌸 Calendar and Reminder System
** BY:**

Avantika Pandey
Roll No: 241033120
Section: 24I11

** Overview
This project is a UNIX shell script–based Calendar and Reminder System.
It allows the user to:

View a calendar for any given year.

Add reminders or events for specific dates.

View all saved reminders.

Delete any reminder when it’s no longer needed.

All reminders are saved permanently in a text file (reminders.txt), so they remain even after the program ends.

⚙️ Functionalities

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

💻 UNIX Commands Used
Command	Purpose
echo	To display messages or text to the user.
read	To take input from the user (like date, event, or choice).
cal	To display the calendar for a specific year.
date	To show today’s date and current time.
cat	To view the contents of the reminder file.
grep	To search for a specific reminder or date inside the file.
sed	To delete a particular line or reminder entry.
tput	To apply text colors and formatting (for pink text).
if, case, while	Conditional and looping structures used in the script.
sleep	Adds small delays for smoother user experience.
clear	Clears the terminal screen (optional — can be removed).
exit	Ends the script execution.
                                                                                         
