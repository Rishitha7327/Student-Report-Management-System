Student Record Management System (C Program)

This is a simple Student Record Management System written in C.
It allows Admin, Staff, and Guest users to manage student details with different access levels.

Features

Login system with three roles:

Admin – Add, display, search, update, delete students

Staff – Add, display, search, update students

Guest – View and search only

Store student details such as:

Registration Number

Name

Branch

CGPA

Year/Semester

Records are saved in students.txt

Credentials stored in credentials.txt

Data is loaded and saved automatically

Uses dynamic memory allocation and file handling

File Formats
credentials.txt
username,password,role
admin,adminpass,admin
staff,staffpass,staff
guest,guestpass,guest

students.txt
regNo, name, branch, cgpa, yearSem

How to Compile and Run
gcc main.c -o student_mgmt
./student_mgmt
