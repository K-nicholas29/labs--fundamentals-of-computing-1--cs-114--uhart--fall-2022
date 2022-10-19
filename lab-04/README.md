# Lab 4, CS 114, Fundamentals of Computing I
Remember **not** to work in this repository. Copy any files you need from this repo into another folder, then work from there.

## Bank Account Class
1. File `Account.java` contains a partial definition for a class representing a bank account. Study it. Then complete the `Account` class as described below. **Note**: You won’t be able to test your methods until you write `ManageAccounts` in question #2.
   1. Fill in the code for method `toString`, which should return a string containing the name, account number, and balance for the account.
   2. Fill in the code for method `chargeFee`, which should deduct a service fee from the account.
   3. Modify `chargeFee` so that instead of returning void, it returns the new balance. Note that you will have to make changes in two places.
   4. Fill in the code for method `changeName` that takes a string as a parameter and changes the name on the account to be that string.
2. File `ManageAccounts.java` contains a shell program that uses the Account class above. Complete it as indicated by the comments.
3. Modify `ManageAccounts` so that it prints the balance after the calls to `chargeFees`. Instead of using the `getBalance` method, like you did after the deposit and withdrawal, use the balance that is returned from the `chargeFees` method. You can either store it in a variable and then print the value of the variable, or embed the method call in a `println` statement.
