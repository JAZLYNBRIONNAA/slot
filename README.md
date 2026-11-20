# Ex04 Time Table
## Date:20.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>timetable</title>
    </head>
    <body bgcolor="lavender">
        <center>
        <img src="\static\logo.png" height="155" width="1530" alt="error!" title="SEC logo">
        </center>
        <br><br><h1 align="center"><b>FIRST SEMESTER TIMETABLE</b></h1>
        <h2 align="center"><b>JAZLYNBRIONNA A REF NO: 26016009</b></h2>
        <br><br><br><table border="8" cellspacing="9" cellpadding="10" align="center">
            <tr bgcolor="burgundy" align="center">
                <th bgcolor="magenta">day/time</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="burgundy">8:00-9:30</td>
                <td>free</td>
                <td>cds</td>
                <td>free</td>
                <td>pyt</td>
                <td>free</td>
                <td>pyt</td>        
            <tr align="center">
                <td bgcolor="burgundy">9:45-11:15</td>
                <td>pyt</td>
                <td>fwad</td>
                <td>free</td>
                <td>ca</td>
                <td>fwad</td>
                <td>de</td>
            </tr>
            <tr align="center">
                <td bgcolor="burgundy">11:30-12:15</td>
                <td colspan="6">lunch</td>
            </tr>
            <tr align="center">
                <td bgcolor="burgundy">12:15-1:00</td>
                <td>free</td>
                <td colspan="5">SCOFT-MM</td>
            </tr>
            <tr align="center">
                <td bgcolor="burgundy">1:15-2:45</td>
                <td>fwad</td>
                <td>de</td>
                <td colspan="3">free</td>
                <td>ca</td>
            </tr>
            <tr align="center">
                <td bgcolor="burgundy">3:00-4:30</td>
                <td colspan="3">free</td>
                <td>beee</td>
                <td>edm</td>
                <td>edm</td>
            </tr>
           </table>       
           <br><br><br><table border="8" cellspacing="9" cellpadding="10" align="center">
            <tr bgcolor="violet" align="center">
                <th>S.No</th>
                <th>subject code</th>
                <th>subject name</th>              
            </tr>
            <tr align="center">
                <td>1.</td>
                <td>19AI301</td>
                <td>Python Programming(pyt)</td>
            </tr>
            <tr align="center">
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(fwad)</td>
            </tr>
            <tr align="center">
                <td>3.</td>
                <td>19EY708</td>
                <td>Career Development Skills(cds)</td>
            </tr>
            <tr align="center">
                <td>4.</td>
                <td>19EE404</td>
                <td>Digital Electronics(de)</td>
            </tr>
             <tr align="center">
                <td>5.</td>
                <td>19CS305</td>
                <td>Computer Architecture(ca)</td>
            </tr>
            <tr align="center">
                <td>6.</td>
                <td>19EE305</td>
                <td>Basic Electrical, Electronics and Measurement Engineering(beee)</td>
            </tr>
            <tr align="center">
                <td>7.</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling(edm)</td>
            </tr>
            <tr align="center">
                <td>8.</td>
                <td>NIL</td>
                <td>mentor meet(MM)</td>
            </tr>
           </table>         
    </body>
</html>

```
## OUTPUT
![alt text](<Screenshot (29).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
