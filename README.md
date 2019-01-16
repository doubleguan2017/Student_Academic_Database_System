# Student_Academic_Database_System
The Database client of this Student Academic Database System is implemented by using C++ and MySQL, it is the second projects of EECS 495 Intro to Database System of Northwestern University, the original student database is provided by professor Peter Scheuermann in 2017.

Here are the schema of the database:

STUDENT (ID, NAME, PASSWORD, ADDRESS)

FACULTY (ID, NAME, DEPTID, PASSWORD, ADDRESS)

CLASSROOM (CLASSROOM_ID, SEATS, TYPE)

UOSOFFERING (UOSCODE, SEMESTER, YEAR, TEXTBOOK, ENROLLMENT, MAXENROLLMENT, INSTRUCTOR_ID)

UNITSOFSTUDY (UOSCODE, DEPT_ID, UOSNAME, CREDITS)

WHENOFFERED (UOSCODE, SEMESTER)

REQUIRES(UOSCODE, PREREQ_UOSCODE, ENFORCED_SINCE)

TRANSCRIPT (STUDENT_ID, UOSCODE, SEMESTER, YEAR, GRADE)

LECTURE (CLASSROOM_ID, UOSCODE, SEMESTER, YEAR, CLASS_TIME)

# Functionalities
The implemented screen flow of the database application
![app](https://github.com/doubleguan2017/Student_Academic_Database_System/blob/master/workFlow.png?raw=true)

# Requirement and Restriction 
The requirement and the restriction can be viewed from the Project_des.pdf file.
