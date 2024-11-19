# Ex03 Time Table
## Date: 16/11/24

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
```
<html>
    <body>
      <center><img src="logo.png" height="100" width="540">
      </center>
       <center> <table border="5" cellpadding="10" bgcolor="yellow">
            <caption align="center">TIME TABLE</caption>    
            <tr>
                <th>TIME/DAY</th><th>MONDAY</th><th>TUESDAY</th><th>WEDNESDAY</th><th>THURSDAY</th><th>FRIDAY</th><th>SATURDAY</th>
             </tr>   
            <tr>
                <td>8.00-10.00</td>
<td>-</td>
                <td>-</td>
                <td>fundamental of c</td>
                <td>physics</td>
                <td>-</td>                
                <td>-</td>
             </tr>   
             <tr>
                <td>10.00-12.00</td>
                <td>chemistry</td>
                <td>digital electronics</td>
                <td>-</td>
                <td>digital electronics</td>
                <td>chemistry</td>
                <td>web application</td>
             </tr>
             <tr>
                <td>1.00-3.00</td>
                <td>c program</td>
                <td>web application</td>
                <td>-</td>
                <td>web application</td>
                <td>physics</td>
                <td>carrier skill</td>
             </tr></center>
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
<td>Fundamentals of Web Application Development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19A1304</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">SH5601</td>
<td>PHYSICS </td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE305</td>
<td>CHEMISTRY</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>DIGITAL ELECTRONICS</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY708</td>
<td>CAREER DEVELOPEMENT SKILLS</td>
</tr>
</table>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-11-19 130741.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
