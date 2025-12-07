📚 Book Management System – ServiceNow Studio

A custom application built on the ServiceNow Platform to manage book records efficiently.
This project was developed as part of my ServiceNow trainee program while practicing CSA & CAD concepts.

🚀 Features

   - Add, update, and delete book records
   - Automated data validation using Client Scripts
   - Record-level automation using Business Rules
   - Custom table to store book information
   - Clean form design with field-level controls
   - Search and filter books using standard list functionalities

🛠️ ServiceNow Concepts Used

 - Custom Table (u_book_records)
 - Forms & Lists Configuration
 - Business Rules
 - Client Scripts (onChange, onSubmit)
 - Script Includes (if used)
 - UI Policies
 - Flow Designer (optional)
 - Access Control (ACL) basics

📁 Application Structure

  Component	Description
  
   u_book_records	 - Stores book details (title, author, price, ISBN, published year)
   Business Rules	 - Automate updates, validations, default values
   Client Scripts	 - Validate form inputs, improve UX
   UI Policies	 - Show/Hide and Make Mandatory conditions
   Flow Designer -	Approval or post-create actions (if implemented)

🎯 What I Learned from This Project

 - How to build a complete application from scratch in ServiceNow Studio
 - Working with Business Rules and Client Scripts
 - Data handling using custom tables
 - Improving user experience using UI Policies
 - Basics of form/UI customization
 - Understanding application logic flow

🧪 How to Test the App

- Install/update the application from Studio
- Open Book Management System > Manage Books
- Create test book records
- Validate automation triggers (Business Rules & Client Scripts)
-  Review list filtering and searching
