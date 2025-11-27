# array 
income_history = [] # add history of calculated income

# loop
while True: # infinite loop
   
   # user input
   user_selection = input("Select income type to calculate income. \n1. Weekly\n2. Monthly\n3. Yearly\nType the option: ").lower()
   
    # conditions for calculating tax based on user selection
   if user_selection == "1" or user_selection == "weekly": # weekly
    weekly_income = float(input("Enter your weekly income: "))
    if weekly_income <= 0:
        print("Invalid input. Please enter a valid income.")
    elif weekly_income <= 250000:
        weekly_tax = 0
        print(f"Total weekly income tax for an income of {weekly_income} is PHP 0")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
    elif weekly_income <= 400000:
        weekly_tax = (weekly_income - 250000) * 0.15
        print(f"Total weekly income tax for an income of {weekly_income} is PHP {weekly_tax}.")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
    elif weekly_income <= 800000:
        weekly_tax = 22500 + (weekly_income - 400000) * 0.20
        print(f"Total weekly income tax for an income of {weekly_income} is PHP {weekly_tax}.")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
    elif weekly_income <= 2000000:
        weekly_tax = 102500 + (weekly_income - 800000) * 0.25
        print(f"Total weekly income tax for an income of {weekly_income} is PHP {weekly_tax}.")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
    elif weekly_income <= 8000000:
        weekly_tax = 402500 + (weekly_income - 2000000) * 0.30
        print(f"Total weekly income tax for an income of {weekly_income} is PHP {weekly_tax}.")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
    else: # income > 8000000
        weekly_tax = 2202500 + (weekly_income - 8000000) * 0.35
        print(f"Total weekly income tax for an income of {weekly_income} is PHP {weekly_tax}.")
        income_history.append({"type": "Weekly", "income": weekly_income, "tax": weekly_tax})
   
   elif user_selection == "2" or user_selection == "monthly": # monthly income calculation
    monthly_income = float(input("Enter your monthly income: "))
    if monthly_income <= 0:
        print("Invalid input. Please enter a valid income.")
    elif monthly_income <= 250000:
        monthly_tax = 0
        print(f"Total monthly income tax for an income of {monthly_income} is PHP 0")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
    elif monthly_income <= 400000:
        monthly_tax = (monthly_income - 250000) * 0.15
        print(f"Total monthly income tax for an income of {monthly_income} is PHP {monthly_tax}.")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
    elif monthly_income <= 800000:
        monthly_tax = 22500 + (monthly_income - 400000) * 0.20
        print(f"Total monthly income tax for an income of {monthly_income} is PHP {monthly_tax}.")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
    elif monthly_income <= 2000000:
        monthly_tax = 102500 + (monthly_income - 800000) * 0.25
        print(f"Total monthly income tax for an income of {monthly_income} is PHP {monthly_tax}.")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
    elif monthly_income <= 8000000:
        monthly_tax = 402500 + (monthly_income - 2000000) * 0.30
        print(f"Total monthly income tax for an income of {monthly_income} is PHP {monthly_tax}.")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
    else: # income > 8000000
        monthly_tax = 2202500 + (monthly_income - 8000000) * 0.35
        print(f"Total monthly income tax for an income of {monthly_income} is PHP {monthly_tax}.")
        income_history.append({"type": "Monthly", "income": monthly_income, "tax": monthly_tax})
   
   elif user_selection == "3" or user_selection == "yearly": # yearly income calculation
    yearly_income = float(input("Enter your yearly income: "))
    if yearly_income <= 0:
        print("Invalid input. Please enter a valid income.")
    elif yearly_income <= 250000:
        yearly_tax = 0
        print(f"Total yearly income tax for an income of {yearly_income} is PHP 0")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
    elif yearly_income <= 400000:
        yearly_tax = (yearly_income - 250000) * 0.15
        print(f"Total yearly income tax for an income of {yearly_income} is PHP {yearly_tax}.")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
    elif yearly_income <= 800000:
        yearly_tax = 22500 + (yearly_income - 400000) * 0.20
        print(f"Total yearly income tax for an income of {yearly_income} is PHP {yearly_tax}.")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
    elif yearly_income <= 2000000:
        yearly_tax = 102500 + (yearly_income - 800000) * 0.25
        print(f"Total yearly income tax for an income of {yearly_income} is PHP {yearly_tax}.")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
    elif yearly_income <= 8000000:
        yearly_tax = 402500 + (yearly_income - 2000000) * 0.30
        print(f"Total yearly income tax for an income of {yearly_income} is PHP {yearly_tax}.")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
    else: # income > 8000000
        yearly_tax = 2202500 + (yearly_income - 8000000) * 0.35
        print(f"Total yearly income tax for an income of {yearly_income} is PHP {yearly_tax}.")
        income_history.append({"type": "Yearly", "income": yearly_income, "tax": yearly_tax})
   else:
        print("Invalid choice, please select a valid option.")
        continue
   
   # ask user if they want to calculate again
   redo = input("Do you want to calculate your income again?\n(Yes/No): ").lower()
   if redo == "yes":
        continue
   elif redo == "no":
        print("Thank you for using the Income Tax Calculator.")
    # ask user if they want to see all calculated income
   show_calculated_income = input("Do you want to see all your calculated income after tax?\n(Yes/No): ").lower()
   if show_calculated_income == "yes":
       print("--- Income History ---")
       for i, record in enumerate(income_history, 1):
           print(f"{i}. {record['type']}: PHP {record['income']:,.2f} (Tax: PHP {record['tax']:,.2f})")
       print("----------------------\nThank you for using the Income Tax Calculator.")
       break
   elif show_calculated_income == "no":
        print("Thank you for using the Income Tax Calculator.")
        break
   else:
        print("Invalid input. Exiting program.")
        break     
   
   