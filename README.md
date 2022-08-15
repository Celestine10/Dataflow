# Dataflow
# Problem Statement
# Goal: Library Management System
### Overview of the Existing System:
The current system is the manual process of library operation where registered members need to visit the library, check the card catalog for their desirable books and get it on the shelf. The manual operation is cumbersome and less efficient. There is now a need for an automated system that will make the operation seamless in which users can have access to books directly from their homes or any location using their devices without having to physically visit the library. 

### Actors (Roles and Responsivities):
1.	Librarian: Responsible for adding, deleting and modifying books as well as maintaining the inventory. 
2.	Members: Members (Patrons can sign in and search for the list of available books, order and return books).
3.	System: Responsible for sending notifications for overdue and available books, as well as giving response to queries by the members/users.

### Input
1.	Book details such as book title, author’s name, year of publication, publisher’s name, collection amount and the book ID which is gotten by scanning its barcode.
2.	Dividing the book into categories based on its content.
3.	User details for registration and login 
4.	Communication details like email, phone number and contact address.

### Output:
-	Notifications of book collections.
-	Notifications of due dates and all users involved. 
-	List of available books in the library catalog.
-	Notification of successful download of e-book
-	Display of new available books.
-	Book prices.
-	Default fees
-	Generate reports. 

### Process
Users: A user who must register to become a member can;
	login.
	search for books.
	borrow and return books.
	be required to pay a fine if they fail to return books on due date
	 download books (downloading to a local device attracts a fee while downloading to the system storage system is free).
Librarian: The librarian can login, add and remove books, maintain the inventory and send broadcast notifications to members on new available books etc.
System admins: They can maintain the system and its processes.

### Scope
- Members can to login into the system from their mobile phone or any other device.
- Members can see the list of books available. 
- Members can search for books based on the author’s name or book title.
- Members can read or download books online in form of e-books instead of going directly to the library.
- The job of the librarian is made easy as the entire process is automated.
- Automation helps to ensure a rapid response and increase in system efficiency. 

### Constraints:
1.	Due to slow internet connection and/or deadlock, the book ordering or cancellation process can be unstable. 
2.	In case of any error, the system must be able to detect it and notify a member of the maintenance team.
3.	All books are not available in e-book format.
4.	Rapid response in sending updates and notifications to the users in case of any due dates due to system downtime.
