# Design for Library Management Database System

## INTRODUCTION:
### What is Library Management System?
Library management system is a system that facilitates the easiness in using and tracking 
the library assets. It provides an instant real picture and process of all the activities that 
happens in a library commencing from the member joining the library and the same 
leaving the library with all the utilization and rendering of the library facilities in 
between.</br>
## Objective:
* The objective of the entire project is Design and implement a library database.</br>
* Construct the expandable search alternatives for the best handling of member queries, 
searching the books by book title, book author, ISBN.</br>
* Construct the search option for the librarian to find the overdue books and fine details.
### Entities:
* Author </br>
* Employee </br>
* Student </br>
* Media </br>
* Media_author </br>
* Condition </br>
* Checkout </br>
* Reservation </br>
### ATTRIBUTES:
#### AUTHOR
➢ Author_name </br>
➢ Author_DOB </br>
#### EMPLOYEE
➢ Empname </br>
➢ Empid </br>
➢ Salary </br>
➢ Job </br>
➢ Employee_DOB </br>
➢ Phonenumber </br>
#### STUDENT
➢ Library_Card_Number </br>
➢ Student_Name </br>
➢ Student_DOB </br>
➢ Mail_id </br>
➢ Phone_number </br>
#### MEDIA
➢ Barcode </br> 
➢ Title </br>
➢ ISBN </br>
➢ Edition </br> 
➢ Published_Date </br>
➢ Publisher </br>
➢ Type </br>
➢ Subject </br>
➢ Order_Cost </br>
➢ Initial_condition </br>
#### MEDIA_AUTHOR 
➢ Barcode </br>
➢ Authorname </br>
➢ Author_DOB</br>
#### CONDITION 
➢ Grade </br>
➢ Percentage </br>
#### CHECK_OUT 
➢ Library_card_number </br>
➢ Barcode </br>
➢ Checkoutdate </br>
➢ Renewed </br>
➢ Amount_Paid </br>
➢ Fee </br>
➢ Tobereturndate </br>
➢ Checkindate </br>
➢ Current_condition </br>
#### RESERVATION 
➢ Library_card_number </br>
➢ Barcode </br>
➢ Date_requested </br>
➢ Check_out_status </br>
➢ Reshelf_date

## Entity Relationship (ER) Diagram

<img src=https://github.com/swethareddy23/Design-for-Library-Management-Database-System/blob/main/ER%20Diagram.png  width='400' height='250' /></br>
