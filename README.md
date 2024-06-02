# University Project Relational Database
This relational database is designed to manage and streamline the operations of a university. It encompasses various entities such as students, courses, professors, and enrollments. The database aims to efficiently handle student registrations, course offerings, and academic records while ensuring data integrity and facilitating easy access to information for administrative purposes.


# Entities and Relationships
# Students
Attributes: Student ID, Name, Date of Birth, Email, Major<br/>
Relationships: Enrollments, Majors
# Professors
Attributes: Professor ID, Name, Email, Department<br/>
Relationships: Courses
# Courses
Attributes: Course ID, Course Name, Credits, Department<br/>
Relationships: Enrollments, Professors
# Enrollments
Attributes: Enrollment ID, Student ID, Course ID, Grade<br/>
Relationships: Students, Courses
# Departments
Attributes: Department ID, Department Name<br/>
Relationships: Students, Professors, Courses
