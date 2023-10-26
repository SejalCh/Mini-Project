# Mini-Project

# Library Management System Report

##**AIM**: To write a program for library management using linked list.

##**Introduction**

<p>The Library Management System is a C++ program designed to streamline the management and organization of a library's book collection. This report offers an in-depth look at the system's functionalities and provides insight into its code structure and key features.</p><br>

##**System Features**
<p>The Library Management System boasts a set of versatile features that cater to the needs of librarians and users:<br>
1. Insert New Record<br>
One of the system's primary functions is the ability to insert new book records into the library. Users can provide essential book details, including a unique ID, title, author, and publisher. This feature is not limited to the insertion of a single record and facilitates bulk record additions.<br>
2. Search Record<br>
Users can effortlessly search for specific books within the library's extensive collection. By entering a book's unique ID, the system rapidly retrieves the relevant details of the book, allowing users to identify its availability and location within the library.<br>
3. Update Record<br>
The system offers the flexibility to update the information associated with any book in the library. Users can modify details such as the book's name, author, or publisher by specifying the book's unique ID, ensuring the library's records remain accurate and up to date.<br>
4. Delete Record<br>
Managing a library's collection also involves removing outdated or irrelevant books. The system permits users to delete records by specifying the unique ID of the book they wish to remove. The system effectively removes the book's record, contributing to a more organized and up-to-date library catalog.<br>
5. Show all Records<br>
To enhance the user's library experience, the system can display a comprehensive list of all the books in the library. This feature not only lists all books but also sorts them in ascending order based on their unique IDs, simplifying the search process for library patrons.</p>

##**Code Structure**
<p>The system's code structure is designed with modularity and ease of use in mind. It revolves around a single class:<br>
Class: library<br>
Private Structure: Node<br>
This private structure holds the book information, including the book's ID, name, author, publisher, and a pointer to the next book in the collection.<br>
  
*Public Member Variables*
Node *head: A pointer to the first book in the library's collection.<br>

*Public Member Functions*<br>
menu(): This function displays the main menu and manages user interactions.<br>
insert(): Inserts a new book into the library's collection.<br>
search(): Searches for a book by its unique ID and displays its details if found.<br>
update(): Allows users to update book information, such as name, author, or publisher, by specifying the book's unique ID.<br>
del(): Permits users to delete a book from the library's collection by entering its unique ID.<br>
sort(): Sorts the library's books in ascending order based on their unique IDs.<br>
show(): Displays the details of all books in the library, promoting easy access to the catalog.<br>
*User Guide*
The system's user interface is straightforward and user-friendly:<br>
->Run the program, and the main menu will be displayed.<br>
->Choose from the available options to insert, search, update, delete, or view books.<br>
->Follow the on-screen prompts for each action, and the system will execute the corresponding functionality, enhancing the overall library management experience.</p>
  
##**Conclusion**
<p>The Library Management System is an invaluable tool for both librarians and library users.Its multiple functionalities is useful for anybody using it as it is user friendly. This project is made using linked list but can be made using hash table which provides even more functionalities.</p>
