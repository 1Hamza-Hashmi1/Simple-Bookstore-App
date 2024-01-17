# Simple-Bookstore-App

- To login as admin, use username: admin and pswd:admin
  - To add in a new user, login using the admin account and going to "Customer" tab
  - To add new books, login using the admin account and going to "Books" tab

- To login in as one of the few customers that have their information in the system already, use username:a and pswd:b
  - To buy a book, simply select book and hit the "Buy" button at the bottom
  - To buy a book with a discounted preice, select the book and hit the "Redeem and Buy" button at the bottom

Greetings to the Book Store Application, a JavaFX application with a graphical user interface (GUI) designed to oversee a virtual book store. This application offers a user-friendly interface for both owners and registered customers to engage with the inventory and customer database of the bookstore.

Owner Features

Login Interface: Secure access with a username and password for owners.
Owner Dashboard: Once logged in, owners gain access to tools for book and customer management.
Book Management: Modify book details such as name and price by adding, deleting, or updating information in the inventory.
Customer Management: Add, remove, or update customer information, including username, password, and points.
Logout Option: Safely exit the owner's interface by logging out.

For Registered Customers

Login Interface: Registered customers can sign in using their provided credentials.
Customer Dashboard: Gain access to the book inventory, points, and status information upon logging in.
Book Selection: Choose books for purchase by using checkboxes.
Purchase Books: Determine the total cost of selected books for purchase.
Points Redemption and Purchase: Calculate the final cost after redeeming customer points.
Logout Option: Safely exit the customer's interface by logging out.

Data Handling: The application relies on text files (books.txt and customers.txt) to store all data, loading it during startup. Any modifications to the inventory or customer details are saved to the files.
