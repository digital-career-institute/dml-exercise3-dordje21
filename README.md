# DML exercise3
Exercise Set:
Exercise Set:
create student table , add columns such as maths,chemistry,physics, and age.

add entries of studnets who have scored more than 75 in physics.add entry for the studnet whose name is alice and bob.

add some students who scored less than 70.

Task 1: SELECT Queries

1.Retrieve all information from the "Students" table:
SELECT * FROM Students;

2.Fetch only the names and ages of students:
SELECT Name, Age FROM Students;

3.Get the details of students who scored above 75 in the "Physics" subject:
SELECT * FROM Students WHERE Physics > 75;

4.Insert a new student into the "Students" table:
INSERT INTO Students (Name, Age, Mathematics, Physics, Chemistry) VALUES ('Emma', 21, 85, 78, 82);

5.Add a student who excelled only in Mathematics and Chemistry:
INSERT INTO Students (Name, Age, Mathematics, Chemistry) VALUES ('Sam', 19, 90, 88);

6.Update the age of a student named "Alice" to 23 years:
UPDATE Students SET Age = 23 WHERE Name = 'Alice';

7.Increase the Chemistry score of all students by 5 points:
UPDATE Students SET Chemistry = Chemistry + 5;

8.Delete a student named "Bob" from the "Students" table:
DELETE FROM Students WHERE Name = 'Bob';

9.Remove all students who scored below 70 in Mathematics:
DELETE FROM Students WHERE Mathematics < 70;







