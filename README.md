 Name:SMRUTI MOHAPATRA
 
 Company:CODETECH IT SOLUTION
 
 ID:CT08DS6478
 
 Domain:java
 
 Duration:August to September 2024

Overview of the project:-Library Management System

Library Management System Overview
          1.Item Types: Books, Magazines, DVDs
          2.User Roles: Librarian, Patron
          3.Functionalities:
          -Add new items
          -Check out and return items
          -Manage overdue fines
          -Search for items
          -Data persistence using file handling
Implementation Outline
          1.Define the Models:

             -Item class (base class)
             -Book, Magazine, DVD (subclasses of Item)
             -User class (base class)
             -Librarian, Patron (subclasses of User)
         2.Library Management:

             -Methods for adding, checking out, returning, and searching items.
             -File handling for data persistence.
         3.Command-line Interface
             -Menu-based system for user interaction.


Explanation:
   1.Item and Subclasses: Define different types of items. Each item has a title, author, category, and checked-out status.

   2.User and Subclasses: Define user roles. Librarians and Patrons have different permissions, but for simplicity, this implementation doesn't enforce role-specific actions.

   3.LibraryManagement Class:

         -addItem(): Adds an item to the library.
         -checkOutItem(): Checks out an item if it's available.
         -returnItem(): Returns an item if it's checked out.
         -searchItems(): Searches for items by title, author, or category.
         -saveData() and loadData(): Handle data persistence using serialization.
   4.Command-line Interface: Provides a simple menu for interacting with the library system.


Running the Program:
       -Compile the Java files using javac *.java.
       -Run the program using java LibraryManagement.
This is a basic version, and there are many ways to extend it, including implementing more complex user roles, handling overdue fines, and using a relational database for persistence.

Output of the code:-

1. Add Item
2. Check Out Item
3. Return Item
4. Search Items
5. Exit
Choose an option: 1

Enter item type (Book/Magazine/DVD): book

Enter title: Five Points Some One

Enter author: Chetan Bhagat

Enter category: fiction

Item added.

 
