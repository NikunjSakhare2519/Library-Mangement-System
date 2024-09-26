# Library Management System

## Project Overview
This is a simple Library Management System built using Java Swing. The application allows users to perform basic library operations such as adding books, borrowing books, returning books, and viewing the available books in the library.

## Features
- **Add Books**: Users can add new books to the library collection. Each book is associated with an ISBN (unique identifier), title, author, and publication year.
- **Borrow Books**: Users can borrow books from the library if they are available. The system will display an error message if the requested book is not available.
- **Return Books**: Users can return borrowed books, and the system will update the book’s availability.
- **View Available Books**: Users can view a list of all books currently available in the library.

## Prerequisites
To run the project, you will need the following software:
- **Java Development Kit (JDK)** (version 8 or later)
- **Integrated Development Environment (IDE)** such as Eclipse, IntelliJ IDEA, or NetBeans (optional, but recommended for easier management and debugging)

## Setup and Running the Project

### 1. Clone or Download the Repository
- If you have a Git repository, clone the project using the following command:
  ```
  git clone <repository_url>
  ```
  Alternatively, download the project zip file and extract it to your desired location.

### 2. Compile and Run the Project
#### Option 1: Using an IDE (Recommended)
1. **Open the Project in an IDE**:
   - Open your preferred IDE.
   - Import the project as a Java project or open the folder where the source code is located.

2. **Build the Project**:
   - Make sure your IDE recognizes the Java files and compiles them automatically.
   - If required, you can manually build the project by selecting the "Build" or "Compile" option in the IDE.

3. **Run the Application**:
   - Locate the main class of the project (typically named `Main.java` or `LibraryManagementSystem.java`).
   - Right-click on the main class and select the "Run" option to start the application.

#### Option 2: Using Command Line
1. **Navigate to the Project Directory**:
   Open a terminal or command prompt and navigate to the root directory of the project where your source code is located.

2. **Compile the Source Code**:
   Use the following command to compile the Java files:
   ```
   javac -d bin src/*.java
   ```
   This will compile all the source files in the `src` directory and place the `.class` files in the `bin` directory.

3. **Run the Application**:
   After compiling, run the application using:
   ```
   java -cp bin LibraryManagementSystem
   ```
   This assumes your main class is named `LibraryManagementSystem.java`. Replace the class name accordingly if it is different.

## How to Use the Application
1. **Add Books**:
   - Navigate to the “Add Book” section in the user interface.
   - Enter the book details, including ISBN, title, author, and publication year.
   - Click on the "Add Book" button to add the book to the library.

2. **Borrow Books**:
   - In the “Borrow Book” section, select a book from the list of available books.
   - If the book is available, click "Borrow" to complete the operation.
   - If the book is not available, you will see an error message.

3. **Return Books**:
   - Navigate to the “Return Book” section.
   - Select the book you want to return from the list of borrowed books and click "Return".

4. **View Available Books**:
   - In the “Available Books” section, view the list of all books that are currently available in the library.

## Project Structure
```
|-- src
|   |-- LibraryManagementSystem.java  // Main class
|   |-- Book.java                     // Book class representing individual books
|   |-- Library.java                  // Library class handling the collection of books
|   |-- BorrowBook.java               // Functionality for borrowing books
|   |-- ReturnBook.java               // Functionality for returning books
|   |-- ViewAvailableBooks.java       // Functionality to view available books
|-- bin                               // Directory for compiled class files
|-- README.md                         // Project documentation (this file)
```

## License
This project is for educational purposes only. You are free to modify and use the code for personal or academic projects.

## Contact
For any questions or issues, feel free to contact me at [nikunjsakhare@gmail.com] or raise an issue in the repository.

