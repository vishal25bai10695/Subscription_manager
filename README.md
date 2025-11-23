# Subscription_manager
To help a user maintain a clear record of active subscriptions and calculate the total monthly cost, budget management.

# Overview of the project
The main job of this tool is to help one person keep a clear list of all the things they pay for every month (like Netflix, Spotify, or mobile games). It helps the user know exactly how much money they spend on subscriptions each month. This is helpful for managing a budget.This project is small and simple. It only works for one user at a time.The system saves all the subscription details (like the name and cost) only while the program is running. 

# Features
Here are the main features it offers:

1)Adding Subscriptions (Choice 1):
The program lets you add a new subscription.
You just type the name of the service (like 'Netflix') and then type the monthly price (like '499.00').
The program adds this new information to its list.

2)Deleting Subscriptions (Choice 2):
If you stop paying for a service, you can easily remove it from the list.
You type the name of the subscription you want to delete.
The program searches for that name in the list and removes it.

3)Viewing and Totaling Costs (Choice 3):
This is the most important feature for budget management.
It shows you the full list of all your active subscriptions and their costs.
At the end of the list, it adds up all the monthly costs to show you the Total Monthly Cost. This helps you know your total spending. 

4)Exiting the Program (Choice 4):
This choice closes the program properly and gives you a thank-you message.

# Technologies/Tools used
1)Language: Python 3

2)Interface: Command Line Interface (CLI) / Terminal

3)Libraries: Standard Python libraries 

# Steps to install and Run the project
To run this tool, you only need Python installed on your system.
Ensure you have Python 3 (version 3.6 or newer) installed

Step 1: Download the Script
Copy the entire Python code for the Subscription Manager into a new file.
Save the file as subscription_manager.py in a folder on your computer.

Step 2: Open Your Terminal
Open your system's command-line application:
Windows: Command Prompt or PowerShell.
macOS / Linux: Terminal.

Step 3: Navigate to the File
Use the cd (Change Directory) command to move into the folder where you saved subscription_manager.py.

Step 4: Execute the Script
Run the program using the Python interpreter:

Step 5: Using the Menu (User Interface)
Once the script starts, you will see the main menu. To use the tool, simply type the number corresponding to the action you want to perform and press Enter.

# Instruction for testing
1)Start the Program: Open your terminal and run the script.

2)Test Case 1: Adding and Viewing (Choices 1 and 3)

Action 2.1: Choose 1 (Add New Subscription).

Result: The program asks for the subscription name.

Action 2.2: Enter Netflix (Name) and 600 (Cost).

Result: The program confirms, "Added 'Netflix' with a cost of Rs600.0."

Action 2.3: Choose 1 (Add New Subscription) again.

Result: The program asks for the subscription name.

Action 2.4: Enter Spotify (Name) and 150 (Cost).

Result: The program confirms, "Added 'Spotify' with a cost of Rs150.0."

Action 2.5: Choose 3 (View All Subscriptions & Total Cost).

Result: Both 'Netflix' and 'Spotify' are shown in the list.

Action 2.6: Check the Total Cost display.

Result: The program displays the correct sum: Total Monthly cost: 750.0 (600 + 150).

3)Test Case 2: Deleting (Choice 2)

Action 3.1: Choose 2 (Delete Subscription).

Result: The program asks for the name of the subscription to delete.

Action 3.2: Enter Spotify.

Result: The program confirms: "Entry Deleted: spotify".

Action 3.3: Choose 3 (View All Subscriptions & Total Cost).

Result: Only 'Netflix' is listed (Spotify is removed).

Action 3.4: Check the Total Cost display.

Result: The program displays the updated cost: Total Monthly cost: 600.0.

Action 3.5: Choose 2 (Delete Subscription) again.

Result: The program asks for the name.

Action 3.6: Enter a name that is not on the list (e.g., Prime).

Result: Program correctly displays: "No subscription found."

4)Test Case 3: Exiting (Choice 4)

Action 4.1: Choose 4 (Exit Program).

Result: Program displays: "Thank you for using Subscription Manager." The program completely stops 

# Screenshots
1) Subscription Manager: Main Menu
<img width="363" height="145" alt="Screenshot 2025-11-23 at 2 39 08 PM" src="https://github.com/user-attachments/assets/a1515c60-09d3-4d0a-8730-03075210eff5" />

2) Adding Subscriptions and its total cost (choosing option 1):
<img width="386" height="108" alt="Screenshot 2025-11-23 at 2 43 46 PM" src="https://github.com/user-attachments/assets/2ecdd65e-f980-4f6b-8658-77163026fb11" />

<img width="375" height="113" alt="Screenshot 2025-11-23 at 2 43 59 PM" src="https://github.com/user-attachments/assets/3c5af1a6-4945-4688-b29b-d6189a89a625" />

3) Viewing all subscription and cost (choosing option 3):
 <img width="278" height="134" alt="Screenshot 2025-11-23 at 2 45 49 PM" src="https://github.com/user-attachments/assets/629c8dfb-fdbe-4c4e-b81d-c0a8c361e99c" />

4) Removing the subscription and viewing the final subscription and cost ( choosing option 2 & 3):
 <img width="575" height="67" alt="Screenshot 2025-11-23 at 2 48 08 PM" src="https://github.com/user-attachments/assets/6189a179-05f9-4d6a-93f5-0bb61d92016a" />

<img width="301" height="104" alt="Screenshot 2025-11-23 at 2 48 34 PM" src="https://github.com/user-attachments/assets/6708c7fe-b15e-4b9e-807c-2302d7aaf133" />

5) Closing the program:
<img width="380" height="45" alt="Screenshot 2025-11-23 at 2 50 01 PM" src="https://github.com/user-attachments/assets/315ec0b6-c85c-49b8-b6d7-f20e52fa5ae7" />


