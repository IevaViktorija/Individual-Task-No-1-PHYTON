# Individual-Task-No-1-PHYTON
Bank Deposit Challenge!

```py
print("Hello! Welcome to the World's Best Bank.")
print(f"The total amount of your balance is {balance}. ")

balance = 0
deposit = input("Please enter the amount of your deposit: ") 

deposit = int(deposit)
balance = 0 + deposit
print(f"Your balance now is {balance} EUR.")

while True:
  choiceOfDepositMore = input('To make an additional deposit, enter the amount of your next deposit. To stop depositing, type "exit". ')
  if choiceOfDepositMore == "exit":
    print("You have left your bank account. See you next time!")
    break
  deposit = int(deposit)
  choiceOfDepositMore = int(choiceOfDepositMore)
  deposit += choiceOfDepositMore
  print(f"The deposit has been successfully added to your bank account. Your total balance now is: {deposit} EUR.")
```
