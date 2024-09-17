# Banking_System-in-C
## Code Description: A Simple ATM Simulation

**Purpose:**
This C code simulates a basic ATM (Automated Teller Machine) system. It allows users to log in, check their balance, withdraw cash, deposit cash, and exit.

**Key Features:**

1. **Login:** Users are prompted to enter their login ID and password. If the credentials match the predefined values, they can access the ATM's functionalities.
2. **Menu:** Once logged in, users are presented with a menu of options:
   - **Check Balance:** Displays the user's current account balance.
   - **Withdraw Cash:** Allows users to withdraw a specified amount from their account, provided they have sufficient funds.
   - **Deposit Cash:** Enables users to deposit funds into their account.
   - **Exit:** Terminates the ATM session.
3. **Balance Management:** The code maintains a balance variable that is updated whenever cash is withdrawn or deposited.
4. **Error Handling:** The code checks for insufficient funds during withdrawals and provides appropriate error messages.
5. **Loop:** The menu loop continues until the user chooses to exit.

**Code Structure:**

- **Functions:**
   - `Check_balance`: Displays the current balance.
   - `Withdraw_Cash`: Processes cash withdrawals.
   - `Deposit_Cash`: Processes cash deposits.
   - `menu`: Handles the login process and menu interactions.
- **Main Function:**
   - Initializes variables for login credentials and balance.
   - Calls the `menu` function to start the ATM simulation.

**Limitations:**

- **Hardcoded Credentials:** The login credentials are hardcoded. In a real-world application, they would be stored in a database for security.
- **Simple Error Handling:** The error handling is basic. More robust validation and error messages could be implemented.
- **Lack of Security Features:** The code doesn't include security measures like encryption or password hashing.
- **Single User:** The ATM is designed for a single user. A multi-user system would require additional features like user accounts and permissions.

Overall, this code provides a foundation for understanding ATM functionality and can be extended to include more features and security measures.
