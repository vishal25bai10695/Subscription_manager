# Problem statement
The use of streaming and software subscriptions makes it difficult for individuals to track total monthly spending and manage personal budgets. The core problem is that users often forget active services, leading to unexpected recurring costs. This project addresses this by developing a simple, single-session Python CLI tool to allow individual users to track, view, and calculate all their subscription expenses instantly.

# Scope of the project
Scope of the Project
The scope defines exactly what the Subscription Manager program is built to do, and what it is not built to do.
1. Application Type

Command-Line Interface (CLI): The program works only as a text-based tool. It does not have a graphical interface with buttons and windows.

2. User and Session Limit

Single-User Focus: The tool is designed to manage the subscriptions of only one individual user. It does not support multiple users or profiles.

Single-Session Use: The application is limited to a single running session.

3. Data Storage

In-Memory Storage: All data (subscription names and costs) is stored temporarily in the computer's memory (RAM) while the program is running.

No Persistence: When the user exits the program (Choice 4), all the entered subscription data is automatically lost. The program does not save data to a file or a database.

4. Functionality

The scope includes the following core functions:

Adding: Allowing the user to input a new subscription name and its monthly cost.

Deleting: Allowing the user to remove a subscription by entering its name.

Viewing: Displaying the full list of currently active subscriptions.

Aggregation: Calculating and showing the total combined monthly cost of all active subscriptions.

5. Exclusions (What the Project Does Not Include)

The project does not include:

Saving data permanently (no file I/O or database).

User authentication (no login/password required).

Handling payments or payment dates.

Advanced filtering or sorting of subscriptions.

# Target users

# High level features
