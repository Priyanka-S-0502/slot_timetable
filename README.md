# Ex03 Time Table
## Date:22.04.2025

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
        <title align="center">SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="870">
        </center>
        <br>        
        <center>
            <b><font color="black" size="5">SLOT TIMETABLE-PRIYANKA S(24900022)</font></b>
        </center>
            <table align="center" border="2" cellpadding="4" bordercolor=" black" bgcolor="#e9e1fd">
                <tr>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">Day/Time</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">8:00 to 10:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">10:00 to 12:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">12:00 to 1:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">1:00 to 3:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">3:00 to 5:00</font></th>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Monday</font></td>
                    <td align="center"><font color="black" size="5">Free Hour </font></td>
                    <td align="center "><font color="black"  size="5">Free Hour</font></td>
                    <td align="center" rowspan="6"><font color="black"  size="5"> LUNCH HOUR</font></td>
                    <td align="center"><font color="black"  size="5">PQC</font></td>
                    <td align="center"><font color="black" size="5">CN</font></td>
 </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Tuesday</font></td>
                     <td align="center"><font colour="black" size="5">TSAF</font></td>
                    <td align="center "><font color="black"  size="5">Free Hour</font></td>
                    <td align="center"><font color="black"  size="5">PQM</font></td>
                     <td align="center"><font color="black"  size="5">Free Hour</font></td>

                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Wednesday</font></td>
                     <td align="center "><font color="black"  size="5">Free Hour</font></td>
                     <td align="center "><font color="black"  size="5">HVPE</font></td>
                    <td align="center"><font color="black"  size="5">Mentor Meet</font></td>
                    <td align="center"><font color="black"  size="5">PQC</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Thursday</font></td>
                    <td align="center"><font color="black"  size="5">FOC</font></td>
                    <td align="center "><font color="black"  size="5">CN</font></td>
                    <td align="center"><font color="black"  size="5">Free Hour</font></td>
                    <td align="center" ><font color="black" size="5">FWAD</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Friday</font></td>
                    <td align="center"><font color="black"  size="5">FOC</font></td>
                    <td align="center "><font color="black"  size="5">FWAD</font></td>
                    <td align="center"><font color="black"  size="5">PQM</font></td>
                    <td align="center"><font color="black"  size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black" size="5">Saturday</font></td>
                    <td align="center"><font color="black"  size="5">Free Hour</font></td>
                    <td align="center "><font color="black" size="5">GEN-AI</font></td>
                    <td align="center"><font color="black"  size="5">RA</font></td>
                    <td align="center"><font color="black"  size="5">TSAF</font></td>

                </tr>
            </table>
            <br>
            <table align="center" border="1" cellspacing="0" cellpadding="4" width="850">
                <thead>
                  <tr>
                    <th><font color="black"  size="5">S. No.</font></th>
                    <th><font color="black"  size="5">Subject Code</font></th>
                    <th><font color="black"  size="5">Subject Name</font></th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td align="center">1<font size="5"></font></td>
                    <td align="center">19AI414<font size="5"></font></td>
                    <td align="center">Fundamentals of Web Application Development (FWAD)<font size="5"></font></td>
                  </tr>
                  <tr>
                   <td align="center">2<font size="5"></font></td>
                   <td align="center">19AI304<font size="5"></font></td>
                   <td align="center">Fundamentals of C Programming<font size="5"></font></td>                    
                  </tr>
                  <tr>
                    <td align="center">3<font size="5"></font></td>
                    <td align="center">19AM401<font size="5"></font></td>
                    <td align="center">Time Series Analysis and Forecasting <font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">4<font size="5"></font></td>
                    <td align="center">19CS406<font size="5"></font></td>
                    <td align="center">Computer Networks<font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">5<font size="5"></font></td>
                    <td align="center">19PH814<font size="5"></font></td>
                    <td align="center">Physics foe Quantum Computing<font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">6<font size="5"></font></td>>
                    <td align="center">19MA222<font size="5"></font></td>
                    <td align="center">Probability and Queuening Models <font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">7<font size="5"></font></td>
                    <td align="center">19HS801<font size="5"></font></td>
                    <td align="center">Human Values and Professional Ethics <font size="5"></font></td>
                  </tr>
                   <tr>
                    <td align="center">8<font size="5"></font></td>
                    <td align="center">19CS579<font size="5"></font></td>
                    <td align="center">Generative AI Application Development <font size="5"></font></td>
                   </tr>
                    <tr>
                    <td align="center">9<font size="5"></font></td>
                    <td align="center">19EY409<font size="5"></font></td>
                    <td align="center">Reasoning Ability <font size="5"></font></td>
                   </tr>

                </tbody>
              </table>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-04-22 220403.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
