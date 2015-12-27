# Lab 5: SQL Query on Multiple Tables: JOIN  

##Assignment: Using the VLABS environment, log into SQL SERVER and use the tables IST210-WC schema with the prefix of UC, and perform the following queries:

1. Display student id, student first name, student last name, the students’ faculty advisor id, advisor last name, advisor location and phone number. You will join uc_student and uc_faculty

2. Write a SELECT statement that will return the faculty last name, faculty first name and the room for faculty whose offices are located in the ‘BUS’ building.

3. Display data from the uc_course_section table by performing a Three Table Join with the uc_course_section, uc_location and uc_course. The SELECT statement will display the course section id (c_sec_id), the course name, number of credits, maximum number of enrollments in a course section, building and room where the class meets and the capacity of the room … and only for courses for term_id 5.

4. Write a select statement that will display student id, student last name and the number of courses a student has been enrolled. You will need to join two table, use a COUNT aggregate and a GROUP BY clause in your SELECT statement.

5. Create a SELECT statement that would provide data for a faculty directory. Display should include faculty id, first name, middle initial, last name, office location (building and room), rank and phone number. The display should be sorted by last name ascending. Concatenate first name, middle initial and last name to look like ‘ James E. Smith’. Concatenate building and room to look like ‘ENG102’. Override the column labels with meaningful descriptions.
