# Subscription_manager
To help a user maintain a clear record of active subscriptions and calculate the total monthly cost, budget management.

# Overview of the project
    subscriptions = []

    def main():
        while True:
            print("\n |Subscription Manager Menu")
            print("1. Add New Subscription\n"
                  "2. Delete Subscription\n"
                  "3. View All Subscriptions & Total Cost\n"
                  "4. Exit Program\n")
            choice = input("Enter your choice:")

            if choice == '1':
                name = input("Enter Subscription Name: ")
                cost = float(input("Enter the subscription cost: "))
                new = {'name': name, 'cost': cost}
                subscriptions.append(new)
                print(f"\n Added '{name}' with a cost of Rs{cost}.")

            elif choice == '2':
                if len(subscriptions) == 0:
                    print("\n No subscriptions to delete.")
                else:
                    delete = input("Enter the name of the subscription you want to delete: ")
                    delete = delete.lower()
                    templist = []
                    delcount = 0

                    for i in subscriptions:
                        if i['name'].lower() == delete:
                            delcount += 1
                        else:
                            templist.append(i)

                    if delcount > 0:
                        subscriptions[:] = templist
                        print(f"Entry Deleted: {delete}")
                    else:
                        print("No subscription found.")

            elif choice == '3':
                if len(subscriptions) == 0:
                    print("\n No subscriptions to display.")
                    continue

                print("\n |Your Current Subscriptions| ")
                totalcost = 0.0

                for subs in subscriptions:
                    name = subs['name']
                    cost = subs['cost']
                    print(f"{name} | Monthly cost: {cost}")
                    totalcost += cost

                print(f"Total Monthly cost: {totalcost}")

            elif choice == '4':
                print("Thank you for using Subscription Manager.")
                break

            else:
                print("Invalid choice. Please try again.")

    main()
