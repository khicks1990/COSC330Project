# Project Requirements

## 1. Menu-Driven Application (5 pts)

Create a menu-driven interface that allows users to interact with the system.

The menu must:

- Use loops to remain active until the user exits
- Validate user input
- Contain multiple submenus
- Use selection statements appropriately

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

## 5. Classes and Encapsulation (8 pts)

Create at least three classes.

### Requirements

- Private data members
- Constructors
- Accessor and mutator methods
- Member functions
- Proper encapsulation

### Example

- Person
- Student
- Course

## 6. Inheritance (8 pts)

Implement an inheritance hierarchy.

### Requirements

- At least one base class
- At least two derived classes

### Example

```text
Account
├── SavingsAccount
└── CheckingAccount
```

## 7. Composition (5 pts)

Demonstrate a "has-a" relationship.

### Examples

- Student has a Transcript
- LibraryItem has an Author
- VehicleRental has a Customer

## 8. Dynamic Memory and Rule of Three (10 pts)

Your project must use dynamic memory.

### Requirements

- Use pointers
- Allocate memory with `new`
- Release memory with `delete`

Create a class that requires:

- Copy constructor
- Assignment operator
- Destructor

Demonstrate a correct Rule of Three implementation.

## 9. Polymorphism and Abstract Classes (10 pts)

Create an abstract base class containing at least one pure virtual function.

### Requirements

- Abstract base class
- Virtual functions
- Runtime polymorphism
- Base class pointer or reference

### Example

```cpp
class Report
{
public:
    virtual void display() = 0;
};
```

## 10. Templates and Operator Overloading (8 pts)

Implement at least one template and one overloaded operator.

### Examples

- Generic search function
- Generic sorting function
- Generic container class
- Overload `<<` for output
- Overload comparison operators

## 11. Exception Handling (5 pts)

Use exception handling to manage errors.

### Examples

- Invalid menu choices
- Missing files
- Invalid record IDs
- Failed data entry

### Requirements

```cpp
try
{
    // code
}
catch (...)
{
    // error handling
}
```

At least three unique exception scenarios must be handled.

## 12. Project Complexity and Overall Design (14 pts)

The project should demonstrate a thoughtful design and meaningful integration of course concepts.

Requirements:

- The application solves a realistic problem
- Features work together cohesively
- Appropriate use of object-oriented design principles
- Demonstrates effort beyond minimum requirements

Your code should demonstrate professional programming practices.

Requirements:

- Meaningful variable and function names
- Consistent formatting and indentation
- Appropriate comments
- Elimination of unnecessary or duplicate code

## 15. Git Commit History (5 pts)

Your repository must show evidence of consistent development throughout the project.

Requirements:

- Multiple commits across both weeks
- Meaningful commit messages
- Clear progression of implementation
- Development performed within GitHub Codespaces

---

## How to Run Example Programs

Enter the given commands in the terminal at the bottom of the codespace to run the code.

- **C++**: Compile with `g++ hello.cpp -o hello` and run with `./hello`.
