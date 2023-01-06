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

<img src=https://github.com/swethareddy23/Design-for-Library-Management-Database-System/blob/main/ER%20Diagram.png  width='600' height='450' /></br>

## Relational Model

<img src= https://github.com/swethareddy23/Design-for-Library-Management-Database-System/blob/main/Relational%20Model.png  width='400' height='450' /></br>

## Normalisation

After the conceptual model the logical representation of entities are created and then before 
converting them into the tables with physical existence normalization is carried out. </br>
Normalization is process by which the data redundancy is nullified.</br>
This is achieved by disintegrating the single relationship with ambiguity into multiple 
smaller and precise relations. The tables holding such data are split into several atomic tables 
so that they become isolated and the data manipulations are carried out in a propagative way 
i.e. a change in an entry point data in a relation makes it triggered and reflected throughout 
the relations which frees tables from modification anomalies, i.e. insertion, updation and 
deletion anomalies.</br>
Several levels of normalization exist in database design and are called Normal Forms. They 
are First Normal Form (1NF), Second Normal Form (2NF) and Third Normal form (3NF).</br>
#### First Normal Form (1NF)
First Normal form is concerned with multiple valued attributes. For the table to be in a first 
normal form it cannot contain multiple values for any attributes.
#### Second Normal Form (2NF)
For the table to be in second normal form the non key attributes of the table shouldn’t be 
partial dependent on any single element of composite primary key.
#### Third Normal Form (3NF)
For the table to be in third normal form the non key attributes shouldn’t have the transitive 
dependency on the primary key.
