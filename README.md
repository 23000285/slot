# Ex03 Time Table

## Date: 18/03/2024

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
    <head>
        <title>
            My Time-Table
        </Title>
    </head>
    <body align="Center" bgcolor="khaki">
        <img width="500" height="100" src="/static/logo.png">
	<br>
	<br>
        <table align="center" border= "6" cellspacing="6" cellpadding="10" bgcolor="aqua">
            <caption >SLOT TIME TABLE - VENKATANATHAN P R (212223240173)</caption>
                <tr bgcolor="lawngreen">
                    <th>Day/Time</th>
                    <th>8-10</th>
                    <th>10-12</th>
                    <th>12-1</th>
                    <th>1-3</th>
                    <th>3-5</th>
                </tr>
                
                <tr bgcolor="bisque">
                    <th bgcolor="lawngreen">Monday</th>
                    <td colspan="2">FREE SLOT</td>
		    <td>LUNCH</td>
                    <td>WEB</td>
                    <td>FREE SLOT</td>
                </tr>
            
                <tr bgcolor="bisque">
                    <th bgcolor="lawngreen">Tuesday</th>
                    <td>CE</td>
                    <td>WEB</td>
		    <td>LUNCH</td>
                    <td>OS</td>
                    <td>FREE SLOT</td>
                </tr>
            
                <tr bgcolor="bisque">
                    <th bgcolor="lawngreen">Wednesday</th>
                    <td>WEB</td>
                    <td>AD-C</td>
		    <td>LUNCH</td>
                    <td colspan="2" align="center">FREE SLOT</td>
                </tr>
                
                <tr bgcolor="bisque">
            <th bgcolor="lawngreen">Thursday</th>
                    <td>OS</td>
                    <td>PQM</td>
		    <td>LUNCH</td>
                    <td>ML</td>
                    <td align="center">CN</td>
                </tr>
            
                <tr bgcolor="bisque">
		    <th bgcolor="lawngreen">Friday</th>
                    <td colspan="2">FREE SLOT</td>
		    <td>LUNCH</td>
                    <td>AD-C</td>
                    <td align="center">ML</td>
                </tr>   
                
                <tr bgcolor="bisque">
		    <th bgcolor="lawngreen">Satruday</th>
                    <td>PQM</td>
                    <td>CE</td>
		    <td>LUNCH</td>
                    <td>CN</td>
		    <td>FREE SLOT</td>
                </tr>
        </table>
	<br>


        <table align="center" border="7" cellspacing="4" cellpadding="6" bgcolor="whitesmoke">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>

            <tr align="center">
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWARD)</td>
            </tr>

            <tr align="center">
                <td>2.</td>
                <td>19AI305</td>
                <td>Advanced C Programming(AD-C)</td>
            </tr>

            <tr align="center">
                <td>3.</td>
                <td>19CS405</td>
                <td>Operating System(OS)</td>
            </tr>

            <tr align="center">
                <td>4.</td>
                <td>19CS406</td>
                <td>Computer Networks(CN)</td>
            </tr>

            <tr align="center">
                <td>5.</td>
                <td>19EN101</td>
                <td>Communicative English(CE)</td>
            </tr>

            <tr align="center">
                <td>6.</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models(PQM)</td>
            </tr>

            <tr align="center">
                <td>7.</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning(ML)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-18 195130.png>)

![alt text](<Screenshot 2024-03-18 194847.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
