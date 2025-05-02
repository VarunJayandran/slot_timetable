# Ex03 Time Table
## Date:02/05/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="5" border="7" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - VARUN J C </b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th> 
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">SATURDAY</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td colspan="2">FREE SLOT</td>
<td>DE</td>
<td>ML</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>RE</td>
<td>DE</td>
<td>FWAD</td>
<td>PQM</td>
<td>HRM</td>
<td>PQM</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>BEEE</td>
<td>HRM</td>
<td>MENTOR</td>
<td>PYTHON</td>
<td>PYTHON</td>
<td>ML</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2">FREE SLOT</td>
<td>BEEE</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EE305</td>
<td>BASIC ELECTRICAL, ELECTRONICS AND MEASURMENT ENGINEERING </td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS (DE)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI410</td>
<td>INTRODUCTION TO MACHINE LEARNING (ML)</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA222</td>
<td>PROBABILITY AND QUEUEING MODELS (PQM)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI301</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19MS156</td>
<td>HUMAN RESOURCE MANAGEMENT AND TEAM BUILDING (HRM)</td>
</tr>
<tr>
<td align="center">8.</td>
<td align="center">19EY709</td>
<td>RESONING ABILITY(RA)</td>
</tr>
</table>
</body>
</html>                                         
~~~
## OUTPUT
![alt text](<WhatsApp Image 2025-04-25 at 6.48.15 PM.jpeg>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
