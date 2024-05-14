# STUDENT-DATABSE-MANAGEMENT-DBMS
Welcome to the Student Management System, a simple SQL program to help you manage and track student information.

THE CODE CONSITS OF VIEWS AND TABLES SUCH AS:


Tables:

Contacts
Fields: ContactID (Primary Key), Email, Phone, Address

Students
Fields: StudentID (Primary Key), Name, ContactID (Foreign Key referencing Contacts table)

Courses
Fields: CourseID (Primary Key), Name, Credits

Grades
Fields: GradeID (Primary Key), StudentID (Foreign Key referencing Students table), CourseID (Foreign Key referencing Courses table), Grade

Departments
Fields: DepartmentID (Primary Key), DepartmentName (Unique), HeadOfDepartment, Location

Views:

StudentGrades
Description: A view to retrieve the student's name, course name, and grade.

EnrolledStudents
Description: Retrieves the number of enrolled students per course.

StudentContactInfo
Description: Retrieves student names along with their contact information (email and phone).

HighGrades
Description: Retrieves high-performing students (grades A and A+).

LowGrades
Description: Retrieves low-performing students (grades D and F).


