## HackerRank Problem: The Report



You are given two tables: Students and Grades. Students contains three columns ID, Name and Marks.

![image](https://user-images.githubusercontent.com/93556280/162318113-259829b4-5ae0-4e5a-9a60-49baac2f2006.png)


Grades contains the following data:

![image](https://user-images.githubusercontent.com/93556280/162318223-57be5243-f3bd-4904-89c3-c5751ce43432.png)


Ketty gives Eve a task to generate a report containing three columns: Name, Grade and Mark. Ketty doesn't want the NAMES of those students who received a grade lower than 8. The report must be in descending order by grade -- i.e. higher grades are entered first. If there is more than one student with the same grade (8-10) assigned to them, order those particular students by their name alphabetically. Finally, if the grade is lower than 8, use "NULL" as their name and list them by their grades in descending order. If there is more than one student with the same grade (1-7) assigned to them, order those particular students by their marks in ascending order.

Write a query to help Eve.

Sample Input

![image](https://user-images.githubusercontent.com/93556280/162318377-09cf1645-85fe-4be7-8b62-5e46d253103b.png)


Sample Output

Maria 10 99

Jane 9 81

Julia 9 88 

Scarlet 8 78

NULL 7 63

NULL 7 68

Note

Print "NULL"  as the name if the grade is less than 8.

Explanation

Consider the following table with the grades assigned to the students:

![image](https://user-images.githubusercontent.com/93556280/162318743-f2b07f1f-f6c5-4ff6-a778-1434160e90d9.png)


So, the following students got 8, 9 or 10 grades:

Maria (grade 10)

Jane (grade 9)

Julia (grade 9)

Scarlet (grade 8)
