# Dataflow
# Goal: The goal is to create a Library Management System
# PROBLEM STATEMENT
AASOM INTERNATIONAL SCHOOL presently use the conventional library system which is the manual process of library operation where registered members need to visit the library physically, check the card catalog for books and get it from the shelf. The manual operation is cumbersome and less efficient. There are cases where members visit the library and the books are scarce/not available either because there aren’t enough copies or they haven’t been refunded. The manual process has also made managing the library a very tedious task for its staff. Retrieval of data is very slow, viewing of library reports and files in terms of issuing and returning of books were not well documented. There is also a lack of information where reports and updates with respect to library transactions and services are not well disseminated. Misplaced Library cards with respect of issuing and returning of books means request for books by users were declined.

AASOM INTERNATIONAL SCHOOL decides to engage a software development company called SAMOA in order to address these setbacks. SAMOA is to provide an automated e-library management system that will make the library operation seamless for all its users. 

The system is expected to handle the following processes where;
A student who must register to become a user can login, search for books, borrow and return books, download books (downloading to a local device attracts a fee while downloading to the system storage system is free) and be required to pay a fine if they fail to return books on due date.
The librarian can also login, add and remove books, maintain the inventory and send broadcast notifications to members on new available books etc.

After receiving inputs, the system is expected to generate the following:
•	reports of the name of library staff that have made modifications to the inventory.
•	reports on the number of books borrowed
•	reports on the number of books returned per day, per week and per month.
•	reports of the names and number of registered students that have borrowed books over time.
•	notifications for new available books.
•	notifications for overdue books that were borrowed 
•	response to queries by the librarian and registered user
Scope
With the library automated members can; 
•	login into the system from their mobile phone or any other device.
•	see the list of books available. 
•	search for books based on the author’s name or book title.
•	read or download books online in form of e-books from the convenience of their various locations instead of going directly to the library.
•	The job of the librarian is made easy as the entire process is automated.
The actors on the system are as follows;
•	Librarian: Responsible for adding, deleting and modifying books as well as maintaining the inventory. 
•	Members: Members (Patrons can sign in and search for the list of available books, order and return books).
•	System: Responsible for sending notifications for overdue and available books, as well as giving response to queries by the members/user

The following inputs are expected to be entered into the system;
1.	Book details such as book title, author’s name, year of publication, publisher’s name, collection amount and the book ID which is gotten by scanning its barcode.
2.	Uploading of books by the librarian.
3.	Division of books into categories based on its content.
4.	User details for registration and login 
5.	Communication details like email, phone number and contact address of registered students.

The outputs expected from the system include:
•	Notifications of book collections.
•	Notifications of due dates and all users involved. 
•	List of available books in the library catalog.
•	Notification of successful download of e-book
•	Display of new available books.
•	Book prices.
•	Default fees
•	Generated reports. 


Constraints:
1.	Due to slow internet connection and/or deadlock, the book ordering or cancellation process can be unstable. 
2.	In case of any error, the system must be able to detect it and notify a member of the maintenance team.
3.	All books are not available in e-book format.
4.	Rapid response in sending updates and notifications to the users in case of any due dates due to system downtime.
