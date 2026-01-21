
## Library Management System

This project focuses on developing a **Library Management System** designed to streamline and organize library operations efficiently. The system supports managing books, members, staff, book lending, and returns through a structured SQL-based database. It stores detailed information about books, including their availability, rental charges, and related metadata, while also handling customer and employee records effectively.

---

## Database Initialization

A database named **“Library”** is created to store and manage all library-related data in an organized manner.

---

## Key Functionalities

### Book Handling

The system allows librarians to insert, modify, and delete book records. Each book entry includes details such as title, genre, rental fee, availability status, author name, and publisher information.

### Customer Records

Customer details are maintained, including name, address, date of registration, and history of issued books.

### Employee Records

Library staff information is stored and managed, covering employee names, job roles, salary details, and branch allocations.

### Book Lending and Returns

The system keeps track of books issued to customers and their return status, ensuring proper monitoring of due dates and availability.

### Branch Information

Details of various library branches are maintained, including branch ID, assigned manager, location address, and contact information.

---

## Queries and Data Insights

The project incorporates multiple SQL queries to analyze and retrieve meaningful information from the database. Some of the important queries include:

1. Fetch the titles, genres, and rental charges of books that are currently available.
2. Display employee names along with their salaries, sorted from highest to lowest.
3. Obtain the list of books issued along with the names of customers who borrowed them.
4. Show the total number of books available under each category.
5. Retrieve employee names and designations for those earning more than ₹50,000.
6. List customers who registered before **01-01-2022** and have not borrowed any books.
7. Display each branch number along with the total number of employees working in that branch.
8. Show the names of customers who borrowed books during **June 2023**.
9. Retrieve the titles of books that belong to the **History** category.
10. Display branch numbers and employee counts for branches that have more than five employees.
