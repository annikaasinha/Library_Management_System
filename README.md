Library Management System


The project is an implementation of a library management system using Object Oriented Programming in Java.

4 classes have been defined


-->Book Class
The book class defines the books which are there in the library. It has the attributes
1)author
2)title
3)number of copies
A book Id is generated for each book added to the library which acts as the primary means of uniquely identifying a book. All the attributes have been declared as private variables within the function.
Various methods have also been defined. All the functions are public. Functions include
1)getter
2)setter
3)toString method for printing the details of the book when necessary.


--->Member Class
The member class defines the members who register themselves in the library
The various attributes within the member class as follows
(All of them private variables)
1)name
2)phone number
3)age
4)borrowed books  (a map which has the book name along with the issue date)
5)fine amount
The various methods/functions are as follows
1)getter and setter methods for private variables
2)issue book
3)return book
4)toString method to print the details of the members


---->BookManager class
This class has been defined to look at all the books inside the library as a whole
The only attribute in it is the list of books.
The methods within this class include
1)AddBook
2)RemoveBook
3)ViewBook(helps the user view all the books in the library)
4)Various methods for searching for a particular book

---->MemberManager class
The only attribute within this class is the Member List
The methods within the class are as follows
1)Add member
2)Remove member
3)viewing the members
4)various methods for searching for a book

--->The main interface calls various methods from these classes which can be accessed easily as most of them
have been defined as public.
