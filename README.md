# Basic-Python-Code-for-Budget-Tracker-with-SMS-Notifications
The user can set the budget with percentages for Needs, Wants, and Savings. Expense Tracking:  As the user adds expenses, the app checks if the spending exceeds the allocated budget. If it does, a text alert is sent. Sending Notifications:  When a budget is exceeded, an SMS is sent to the user using Twilio, notifying them of the overage.
Instructions for a Non-Technical User
Install Python & Twilio:

Ensure Python is installed on the system.
Install the twilio library by running:
bash
Copy code
pip install twilio
Set Up Twilio:

Sign up for Twilio at twilio.com and obtain your Twilio SID, Auth Token, and Twilio phone number.
Enter these details directly in the script.
Run the Program:

Save the Python code in a file, e.g., budget_tracker.py.
Open the command line (Terminal) and navigate to the directory where the file is saved.
Run the script:
bash
Copy code
python budget_tracker.py
Follow the Prompts:

The program will ask for your monthly income, set your budget percentages, and allow you to add expenses. If any expense exceeds the allocated budget, you'll receive an SMS alert.
