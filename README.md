<img width="1919" height="1079" alt="Screenshot 2025-12-06 110053" src="https://github.com/user-attachments/assets/1ec71039-584c-4593-bcfd-6e171ccf4ecd" /># Ex03 Time Table
## Date: 6-12-2025
## Ref no: 25013558

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
itle>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - Nivetha N (25013558)</b></caption>
            <tr align="center">
                <th bgcolor="green">Day/Time</th>
                <th bgcolor="green">Monday</th>
                <th bgcolor="green">Tuesday</th>
                <th bgcolor="green">Wednesday</th>
                <th bgcolor="green">Thursday</th>
                <th bgcolor="green">Friday</th>
                <th bgcolor="green">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="green">8-10</th>
                <td >FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
            <th bgcolor="green">10-12</th>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            </tr>
            <tr>
                <th bgcolor="green">12-1</th>
                <td colspan="5" align="center">L U N C H</td>
            </tr>
            <tr align="center">
            <th bgcolor="green">1-3</th>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr align="center">
            <th bgcolor="green">3-5</th>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FREE SLOT</td>
            </tr>
         </table>
         <br>
         <table align="center"  cellspacing="2" cellpadding="4" border="2">
          <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Code</th>
          </tr>
          <tr> 
          <td align="center">1.</td> 
          <td align="center">19AI414</td>
          <td> Fundamentals of Web Application Development (FWAD)</td>
          </tr>
          <tr> 
          <td align="center">2.</td> 
          <td align="center">19AI302</td>
          <td> Fundamentals of C Programming (C Program)</td>
          </tr>
          <tr> 
          <td align="center">3.</td> 
          <td align="center">19EN101</td>
          <td> Communicative English (CE)</td>
          </tr>
        </table>
    </body>
    </html>
~~~


## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-12-06 110053" src="https://github.com/user-attachments/assets/e8495c23-70fc-4244-9c6b-504d8548c79f" />


<img width="1918" height="1079" alt="Screenshot 2025-12-06 113149" src="https://github.com/user-attachments/assets/9b3e7938-25df-4d4e-a7d3-8a3167571efc" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
