# Basic Banking System

This is a simple banking system implemented in Java. It provides a basic command-line interface to interact with a bank account, allowing users to deposit money, withdraw money, and check their account balance.

## Features

- **Deposit Funds**: Add money to the account.
- **Withdraw Funds**: Remove money from the account, subject to available balance.
- **Check Balance**: View the current account balance.

## Getting Started

To run this banking system, you need to have Java installed on your machine. Follow these instructions to get started:

### Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) installed.

### Installation

1. **Clone the Repository** (if using version control, otherwise skip this step):
   ```bash
   git clone https://github.com/GAURITYAGI1/Basic-Banking-System.git
   cd Basic-Banking-System
   ```

2. **Compile the Code**:
   Save the provided Java code into a file named `bankingSystem.java`. Open your terminal and navigate to the directory containing this file. Compile it using:
   ```bash
   javac bankingSystem.java
   ```

3. **Run the Program**:
   After compiling, run the program using:
   ```bash
   java bankingSystem
   ```

## Usage

When you run the program, you will be presented with a command-line menu with the following options:

1. **Deposit**: Enter the amount to deposit into the account.
2. **Withdraw**: Enter the amount to withdraw from the account.
3. **Check Balance**: View the current balance of the account.
4. **Exit**: Close the program.

### Example

```
Banking System Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option: 1
Enter amount to deposit: 500
Deposited: $500.0
```

## Code Overview

- **BankAccount Class**: Represents a bank account with methods to deposit, withdraw, and check the balance.
- **SimpleBankingSystem Class**: Contains the main method which provides a simple command-line interface for interacting with the `BankAccount`.

## Notes

- This is a basic implementation and does not include advanced features such as multiple accounts, persistent storage, or transaction history.
- For a production-level application, consider implementing additional features, such as input validation, error handling, and a more robust user interface.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

If you have suggestions or improvements, feel free to submit a pull request or open an issue on the repository.

## Author

[Gauri Tyagi](https://github.com/GAURITYAGI1)

Create with🤍💖!!
