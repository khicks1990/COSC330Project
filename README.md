# Project Requirements

## 1. Menu-Driven Application (5 pts)

Create a menu-driven interface that allows users to interact with the system.

The menu must:

- Use loops to remain active until the user exits
- Validate user input
- Contain multiple submenus
- Use selection statements appropriately

---

## 2. File Input and Output (10 pts)

Your application must persist data using files.

### Requirements

- Load data when the program starts
- Save data before exit
- Read from at least one file
- Write to at least one file
- Support updates to stored records

### Example Applications

- Books in a library
- Students in a course system
- Products in inventory

---

## 3. Functions and Modular Design (5 pts)

Your project must be separated into multiple source files.

### Requirements

- Use meaningful functions
- Pass parameters appropriately
- Include reference parameters where appropriate
- Separate implementation and interface files

### Minimum Structure

- `main.cpp`
- At least three additional implementation files (`.cpp`)
- Corresponding header files (`.h`)

---

## 4. Arrays and Searching/Sorting (7 pts)

Your system must store collections of data and perform operations on them.

### Requirements

- Use at least one array or dynamically allocated collection
- Implement searching
- Implement sorting

### Possible Operations

- Search by ID
- Search by name
- Sort alphabetically
- Sort numerically

---

## 5. Classes and Encapsulation (8 pts)

Create at least three classes.

### Requirements

- Private data members
- Constructors
- Accessor and mutator methods
- Member functions
- Proper encapsulation

### Example

- `Person`
- `Student`
- `Course`

---

## 6. Inheritance (7 pts)

Implement an inheritance hierarchy.

### Requirements

- At least one base class
- At least two derived classes

### Example

```text
Account
├── SavingsAccount
└── CheckingAccount

## How to Run Example Programs

Enter the given commands in the terminal at the bottom of the codespace to run the code.

- **C++**: Compile with `g++ hello.cpp -o hello` and run with `./hello`.
