

expenses = []

def add_expense(amount, category):
    expenses.append({"amount": amount, "category": category})

def show_expenses():
    total = sum(item["amount"] for item in expenses)
    print("\nExpenses List:")
    for item in expenses:
        print(f"{item['category']}: ₹{item['amount']}")
    print(f"Total Spending: ₹{total}")

while True:
    print("\n1. Add Expense\n2. Show Expenses\n3. Exit")
    choice = input("Enter choice: ")

    if choice == "1":
        amount = float(input("Enter amount: "))
        category = input("Enter category: ")
        add_expense(amount, category)
    elif choice == "2":
        show_expenses()
    elif choice == "3":
        break
    else:
        print("Invalid choice, try again.")
