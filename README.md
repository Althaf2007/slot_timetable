# Ex03 Time Table
## Date:17/11/2024

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
'''
<html>
<head> 
<title>Slot Timetable</title> 
</head> 
<body> 
<center> 
<img src="/static/logo.png" height="100" width="548">
</center> 
<br> 
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan"> 
<caption><b>SLOT TIME TABLE K.MOHAMED ALTHAF (24005994)</b></caption> 
<tr align="center"> 
<th bgcolor="yellow">Day/Time</th> 
<th bgcolor="yellow">Monday</th> 
<th bgcolor="yellow">Tuesday</th> 
<th bgcolor="yellow">Wednesday</th> 
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th> 
<th bgcolor="yellow">Saturday</th>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">8-10</th> 
<td>FUNDAMENTALS OF C PROGRAMMING</td> 
<td>FREE SLOT</td> 
<td>FUNDAMENTALS OF C PROGRAMMING</td> 
<td>PHYSICS FOR QUANTUM COMPUTING</td> 
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">10-12</th> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td> 
<td>FREE SLOT</td> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td> 
<td>CAREER DEVELOPMENT SKILLS</td> 
<td>COMMNUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td> 
</tr> 
<tr> 
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">LUNCH</td> 
</tr> 
<tr align="center"> 
<th bgcolor="yellow">1-3</th> 
<td>FUNDAMENTALS OF C PROGRAMMING</td> 
<td>DIGITAL ELECTRONICS</td> 
<td>MENTOR MEET</td> 
<td>COMMUNICATIVE ENGLISH</td> 
<td>FREE SLOT</td> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">3-5</th> 
<td>FREE SLOT</td> 
<td>FREE SLOT</td> 
<td>FREE SLOT</td>
<td>FREE SLOT</td> 
<td>FREE SLOT</td>
<td>FREE SLOT</td> 
</tr> 
</table> 
<br> 
<table align="center" cellspacing="2" cellpadding="4" border="2"> 
<tr align="center"> 
<th>S. No.</th>
<th>Subject Code</th> 
<th>Subject Name</th> 
</tr> 
<tr> 
<td align="center">1.</td> 
<td align="center">19A1414</td> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td> 
</tr> 
<tr> 
<td align="center">2.</td> 
<td align="center">19A1304</td> 
<td>FUNDAMENTALS OF C PROGRAMMING</td> 
</tr> 
<tr> 
<td align="center">3.</td> 
<td align="center">19A1414</td> 
<td>COMMUNICATIVE ENGLISH</td> 
</tr>
<tr> 
<td align="center">4.</td> 
<td align="center">SH3214</td> 
<td>PHYSICS FOR QUANTUM COMPUTING</td> 
</tr> 
<tr> 
<td align="center">5.</td> 
<td align="center">19EE404</td> 
<td>DIGITAL ELECTRONICS</td> 
</tr> 
<tr> 
<td align="center">6.</td> 
<td align="center">19EY708</td> 
<td>CAREER DEVELOPMENT SKILLS</td> 
</tr> 
<tr> 
<td align="center">7.</td> 
<td align="center">TSI0T004</td> 
<td>MENTOR MEET</td> 
</tr> 
</table> 
</body> 
</html>
'''
## OUTPUT
C:\Users\admin\tt\Eligibility-for-Admission\slot_timetable\Screenshot 2024-11-17 160500.png


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
