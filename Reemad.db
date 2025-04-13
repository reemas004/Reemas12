CREATE TABLE DEPARTMENTS
(
DeptNo int primary key ,
DeptName varchar(30) not null
);
CREATE TABLE STUDENTS
(
StdNo int primary key not null,
StdFirstName varchar(30) not null,
StdFamilly varchar(30) ,
DOB date,
DeptNo int ,
foreign key (DeptNo) references DEPARTMENTS(DeptNo)
)
INSERT INTO DEPARTMENTS (DeptName, DeptNo)
VALUES ('Technical support', 203);
INSERT INTO DEPARTMENTS (DeptName, DeptNo)
VALUES ('Marketing', 202);
INSERT INTO DEPARTMENTS (DeptName, DeptNo)
VALUES ('Engineering', 201);
INSERT INTO DEPARTMENTS (DeptName, DeptNo)
VALUES ('programming', 200);
INSERT INTO STUDENTS (DeptNo, DOB, StdFamilly, StdFirstName, StdNo)
VALUES (202, '17-APR-1993', 'Nasser', 'Lamia', 100005);
INSERT INTO STUDENTS (DeptNo, DOB, StdFamilly, StdFirstName, StdNo)
VALUES (203, '20-MAY-1992', 'Fahad', 'Sara', 100004);
INSERT INTO STUDENTS (DeptNo, DOB, StdFamilly, StdFirstName, StdNo)
VALUES (201, '14-AUG-1995', 'Ahmad', 'Noura', 100003);
INSERT INTO STUDENTS (DeptNo, DOB, StdFamilly, StdFirstName, StdNo)
VALUES (200, '11-APR-1990', 'Khaled', 'Amal', 100002);
SELECT * FROM STUDENTS ;
UPDATE STUDENTS
SET StdFamilly = 'Fahad'
WHERE StdNo = 100002;
DELETE FROM STUDENTS WHERE DeptNo = 203;
DELETE FROM DEPARTMENTS WHERE DeptNo = 203;
