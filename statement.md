# Problem statement
The use of streaming and software subscriptions makes it difficult for individuals to track total monthly spending and manage personal budgets. The core problem is that users often forget active services, leading to unexpected recurring costs. This project addresses this by developing a simple, single-session Python CLI tool to allow individual users to track, view, and calculate all their subscription expenses instantly.

# Scope of the project
Scope of the Project
The scope defines exactly what the Subscription Manager program is built to do, and what it is not built to do.
1. Application Type
a)Command-Line Interface (CLI): The program works only as a text-based tool. It does not have a graphical interface with buttons and windows.
2. User and Session Limit
a) Single-User Focus: The tool is designed to manage the subscriptions of only one individual user. It does not support multiple users or profiles.
b) Single-Session Use: The application is limited to a single running session.
3. Data Storage
a)In-Memory Storage: All data (subscription names and costs) is stored temporarily in the computer's memory (RAM) while the program is running.
4. Functionality
The scope includes the following core functions:
a)Adding: Allowing the user to input a new subscription name and its monthly cost.
b)Deleting: Allowing the user to remove a subscription by entering its name.
c)Viewing: Displaying the full list of currently active subscriptions.
d)Aggregation: Calculating and showing the total combined monthly cost of all active subscriptions.

# Target users
Developers: Users who prefer staying in the terminal environment.
Students: Those learning basics of python and wants to make an difficults code with basics command.

# High level features
1)Subscription Tracking:

a)The program acts as a central digital list where the user can enter and store the names and corresponding monthly costs of their various subscriptions.

2Total Cost Aggregation:

a)This is the main benefit. The tool automatically adds up all the individual monthly subscription costs entered by the user.

b)It provides the user with one clear, instant number: their total monthly spending on subscriptions. 

Simple Management:

a)The tool allows the user to easily view the complete list of all active services and delete any service they no longer pay for.

