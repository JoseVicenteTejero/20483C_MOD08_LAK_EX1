# 20483C_MOD08_LAK_EX1
Exercise 1: Creating a WCF Data Service for the SchoolGrades Database

JOSE VICENTE TEJERO CALDERERA - 30/10/2020

RESUMEN
Configure data service in the Grades.Web project
 Specify the GradesDBEntities data context for the data service
 Add an operation to retrieve all of the students in a specified class
 Add an operation to retrieve all of the students in a specified class
 
 <service xmlns="http://www.w3.org/2007/app" xmlns:atom="http://www.w3.org/2005/Atom" xml:base="http://localhost:1655/Services/GradesWebDataService.svc/">
<workspace>
<atom:title>Default</atom:title>
<collection href="Grades">
<atom:title>Grades</atom:title>
</collection>
<collection href="Students">
<atom:title>Students</atom:title>
</collection>
<collection href="Subjects">
<atom:title>Subjects</atom:title>
</collection>
<collection href="Teachers">
<atom:title>Teachers</atom:title>
</collection>
<collection href="Users">
<atom:title>Users</atom:title>
</collection>
</workspace>
</service>

PROBLEMAS
Ninguno
