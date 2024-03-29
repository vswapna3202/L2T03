## L2T03 : SQL ##
This task executes various SQL statements. The SQLs are executed on https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all.

Student.txt has the following SQL statements:

1. The SQL code to create a table called Student. The table structure is
summarised in the table below. STU_NUM is set up as the primary key.

| Attribute Name | Data Type     |
|----------------|---------------|
| STU_NUM        | CHAR(6)       |
| STU_SNAME      | VARCHAR(15)   |
| STU_FNAME      | VARCHAR(15)   |
| STU_INITIAL    | CHAR(1)       |
| STU_STARTDATE  | DATE          |
| COURSE_CODE    | CHAR(3)       |
| PROJ_NUM       | INT(2)        |

2. Data is inserted into the created table. The following rows are added to the table.

| STU_NUM | STU_SNAME  | STU_FNAME | STU_INITIAL | STU_STARTDATE | COURSE_CODE | PROJ_NUM |
|---------|------------|-----------|-------------|---------------|-------------|----------|
| 01      | Snow       | Jon       | E           | 2014-04-05    | 201         | 6        |
| 02      | Stark      | Arya      | C           | 2017-07-12    | 305         | 11       |
| 03      | Lannister  | Jamie     | C           | 2012-09-05    | 101         | 2        |
| 04      | Lannister  | Cersei    | J           | 2012-09-05    | 101         | 2        |
| 05      | Greyjoy    | Theon     | I           | 2015-12-09    | 402         | 14       |
| 06      | Tyrell     | Margaery  | Y           | 2017-07-12    | 305         | 10       |
| 07      | Baratheon  | Tommen    | R           | 2019-06-13    | 201         | 5        |

3. SQL statement for returning all records which have a COURSE_CODE of 305.
4. SQL statement to modify the course code to 304 for the person whose student number is 07.
5. SQL code to delete the row of the person named Jamie Lannister, who started on 5 September 2012, whose course code is 101 and project number is 2. Logical operators are used to include all of the information given in the task.  
6. SQL code that changes the PROJ_NUM to 14 for all those students who started before 1 January 2016 and whose course code is at least 201.
7. SQL code that deletes the Student table entirely.

