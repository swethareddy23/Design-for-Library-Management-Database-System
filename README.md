# Design for Library Management Database System

## INTRODUCTION:
### WHAT IS LIBRARY MANAGEMENT SYSTEM?
Library management system is a system that facilitates the easiness in using and tracking 
the library assets. It provides an instant real picture and process of all the activities that 
happens in a library commencing from the member joining the library and the same 
leaving the library with all the utilization and rendering of the library facilities in 
between.
 Objective:
• The objective of the entire project is Design and implement a library database.
• Construct the expandable search alternatives for the best handling of member queries, 
searching the books by book title, book author, ISBN.
• Construct the search option for the librarian to find the overdue books and fine details.
ENTITIES:
• Author
• Employee
• Student
• Media
• Media_author
• Condition
• Checkout
• Reservation
ATTRIBUTES:
• AUTHOR
➢ Author_name
➢ Author_DOB
• EMPLOYEE
➢ Empname
➢ Empid
➢ Salary
➢ Job
➢ Employee_DOB
➢ Phonenumber
• STUDENT
➢ Library_Card_Number
➢ Student_Name
➢ Student_DOB
➢ Mail_id
➢ Phone_number
4 | P a g e
• MEDIA ➢ Barcode ➢ Title ➢ ISBN ➢ Edition, ➢ Published_Date ➢ Publisher ➢ Type ➢ Subject ➢ Order_Cost ➢ Initial_condition ) • MEDIA_AUTHOR ➢ Barcode ➢ Authorname ➢ Author_DOB) • CONDITION ➢ Grade ➢ Percentage • CHECK_OUT ➢ Library_card_number ➢ Barcode ➢ Checkoutdate, ➢ Renewed ➢ Amount_Paid ➢ Fee ➢ Tobereturndate ➢ Checkindate ➢ Current_condition) • RESERVATION ➢ Library_card_number ➢ Barcode ➢ Date_requested ➢ Check_out_status ➢ Reshelf_date
