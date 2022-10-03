# WebDev
Book Reservation Web Site.

The aim of this assignment is to develop a book reservation web site using PHP and MySQL database. The application will allow users to search for and reserve library books. Specifically, the application will enable the following:

· Search for a book 

· Reserve a book 

· View all the books that they have reserved 

  •	Login – The user must identify themselves to the system in order to use the system and throughout the whole site. If they have not previously used the system, they     must register their details.
  
  •	Registration - This allows a user to enter their details on the system. The registration process should validate that all details are entered. Mobile phone numbers     should be numeric and 10 characters in length. Password should be six characters and have a password confirmation function. The system should ensure that each user     can   be identified using a unique username. 
  
  •	Search for a book: The system should allow the user to search in a number of ways: 
  
    o	by book title and/or author (including partial search on both) 
    
    o	by book category description in a dropdown menu (book category should retrieved from database)
    
  •	The results of the search should display as a list from which the user can then reserve a book if available. If the book is already reserved, the user should not be   allowed to reserve the book.
  
  •	Reserve a book – The system should allow a user to reserve a book provided that no-one else has reserved the book yet. The reservation functionality should capture     the date on which the reservation was made.
  
  •	View reserved books – the system should allow the user to see a list of the book(s) currently reserved by that user. User should be able to remove the reservation as   well.

*************************************************************************************************************************************************************************
The book database contains four tables: 
1.	Users table - to hold user registration and password details. Each user is uniquely identified by a user name. 
2.	Books table - holding all book details, indexed by ISBN number 
3.	Category table – indicating the list of book categories (fiction, business etc). It is linked to the Books table by category code 
4.	Reserved Books table - holding a list of books reserved by the user  (identified by username). It is linked to the books table by ISBN number and the Users table by     username. 
