ATM Simulation Program :

1.Description :
     This is a basic Python-based ATM simulation that allows users to check their balance, deposit money, withdraw money, and exit the ATM service. The program validates the user's PIN and  
       provides an interactive menu for performing different banking operations.

2.Features :
    * PIN Authentication : The user must enter the correct PIN to access the ATM services.
    * Balance Enquiry : The user can check their current balance.
    * Deposit : The user can deposit an amount into their account, which will be added to the balance.
    * Withdrawal : The user can withdraw an amount from their account, provided there is sufficient balance.
    * Exi t: The user can choose to exit the ATM service.

3.Requirements :
    Python 3.x

4.Installation :
   * Ensure that you have Python 3.x installed on your system.
   * Copy the code to a Python (.py) file, for example, atm_simulation.py.
   * Run the script using the following command in your terminal or command prompt: python atm_simulation.py

5.How to Use :
    * When prompted, enter your PIN number (the default is 1831).
    * After entering the correct PIN, you will be presented with an ATM menu:
       Option 1: Balance Enquiry – Check your current balance.
       Option 2: Deposit – Enter an amount to deposit into your account.
       Option 3: Withdrawal – Enter an amount to withdraw from your account (must not exceed the balance).
       Option 4: Exit – Exit the ATM service.
    * If you enter an incorrect PIN, the program will ask you to try again.

6.Example Interaction :
    Enter your pin number: 1831
      Welcome to our ATM service
       1. Balance Enquiry
       2. Deposit the amount
       3. Debit the amount
       4. Exit
    Choose any option: 1
      Your current balance is: Rs. 2000

7.Error Handling :
    * If an incorrect PIN is entered, the user will be asked to try again.
    * If an invalid option is chosen from the menu, the program will notify the user.
    * If the user tries to withdraw more than the available balance, the program will show an error message.

8.Future Improvements :
   * Allow multiple attempts for entering the PIN.
   * Handle non-integer inputs for deposit and withdrawal amounts.
   * Add a transaction history or logs.
   * Implement security features like locking the account after several failed PIN attempts.

9.License :
   This project is open-source and free to use.
