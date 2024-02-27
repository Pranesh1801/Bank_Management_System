## BANK MANAGEMENT SYSTEM

### A console based application created using pure Java programming to enhance my knowledge on implementation of Data Structures and Object Oriented Programming.

Here's a breakdown of the data structures and OOP concepts used in the provided Java code:

### Data Structures:
1. **HashMap**:
    - The `HashMap<String, BankAccount> accounts` is used to store bank accounts. It maps account numbers (strings) to `BankAccount` objects.
    - It allows efficient retrieval of bank accounts based on their account numbers.

2. **Scanner**:
    - The `Scanner` class is used for taking user input from the command line (`System.in`).

### Object-Oriented Programming (OOP) Concepts:
1. **Class**:
    - The `BankAccount` class encapsulates the properties and behaviors of a bank account.
    - It has private instance variables (`accountNumber`, `balance`, `password`, `accountHolderName`) and public methods to operate on these variables.
    - It follows the principles of encapsulation by keeping its fields private and providing public methods to access and manipulate them.

2. **Constructor**:
    - The `BankAccount` class has a constructor that initializes its instance variables when a new `BankAccount` object is created.

3. **Encapsulation**:
    - Instance variables of the `BankAccount` class are declared as private, which encapsulates the data within the class.
    - Public methods (`getAccountNumber()`, `getAccountHolderName()`, `getBalance()`, `authenticate()`, `deposit()`, `withdraw()`) are provided to access and modify the private variables in a controlled manner.

4. **Inheritance** (Not explicitly used in the provided code):
    - Inheritance is not used in this code snippet. There is only one class defined (`BankAccount`), and it doesn't extend or inherit from any other class.

5. **Polymorphism** (Not explicitly used in the provided code):
    - Polymorphism is not explicitly used in the provided code. There are no method overrides or interface implementations that demonstrate polymorphic behavior.

6. **Object Instantiation**:
    - Objects of the `BankAccount` class are instantiated in the `main` method to represent bank accounts, and they are stored in the `HashMap` for later retrieval and manipulation.

7. **Method Invocation**:
    - Methods of the `BankAccount` class (e.g., `deposit()`, `withdraw()`, `authenticate()`, `getBalance()`) are invoked based on user input and program logic to perform various operations on bank accounts.

Overall, the code demonstrates principles of object-oriented programming by encapsulating related functionality within the `BankAccount` class and using data structures like `HashMap` for managing collections of bank accounts efficiently.
