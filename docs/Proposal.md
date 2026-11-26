Project Title:
Student Record Management System

Brief Description:
The project will help teachers and class advisors be able to access information in a well organized record. It will help prevent misinformation often due to the paper-based systems that are slow, messy, and have a chance to be lost. In this program, the user can search up a student record. They could either calculate the student GWA, find out if the student has a low grade, add a new student if they need to, and be able to edit the student record.

Problem Statement:
Schools often struggle to organize and manage student records because paper-based systems are slow, messy, and prone to loss. This makes it difficult for teachers and class advisers to access student information quickly and efficiently.  

Target Users / Beneficiaries:
The target users of this program are the teachers and class advisers.





Sample Wireframe
MAIN interface:

===============================
—-- Student Record —--
[1] Calculate GWA
[2] Low grade identification
[3] Student record search 
[4] Add new student
[5] Edit student record
[0] End Program
===============================
Input choice: (input)
If choice is between 0-5
	Proceed to selected feature
Else:
	Output(Invalid Choice. Please Try Again.)
             Return to MAIN interface

Flowchart:
MAIN interface0
|
|
|
* ==== [1] Calculate GWA
              |
             1. Enter student ID number
2. Student GWA output
|
Return to MAIN interface
|
|
* ==== [2] Low grade Identification
|
1. Enter student ID number
2. If student has a grade greater than 2.50:
Output(Low grade identified { GRADE })
    Else:
Output(No low grade identified)
|
Return to MAIN interface
|
|
*==== [3] Student record search 
|
1. Enter student ID number
2. Output(Student Record)
|
Return to MAIN interface
|
|
*==== [4] Add new student
|
1. Enter new student ID number
2. Enter student  FULL NAME
3. Enter student section / year level
4. Enter grade if any
5. Output(New student information)
|
Return to MAIN interface
|
|
*==== [5] Edit student record
|
1. Enter student ID number
2. Output(Current student Information)
3. Input(New student information)
4. Output(New student information)
|
Return to MAIN interface
|
|
*==== [0] End Program
END PROGRAM
