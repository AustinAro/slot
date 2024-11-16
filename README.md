# Ex03 Time Table
## Date:16/11/2024

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
'''<html>
    <head>
        <title>Slot Table</title>
    </head>
    <body>
        <img src="logo.png" alt="Logo" style="width: 1350; height: 100;"><br>
        <table border="5" align="centre" cellpadding="15" >
        <tr><th>Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th>
        </tr><tr><th>8:00-10:00</th><th style="background-color: antiquewhite;">Free Period</th><th style="background-color: red;">Fundamentals of c</th><th style="background-color: antiquewhite;">Free Period</th><th style="background-color: aquamarine;">Principles of chemistry</th><th style="background-color: antiquewhite;">Free Period</th><th style="background-color: antiquewhite;">Free Period</th></tr>
        <tr><th>10:00-12:00</th><th style="background-color: aqua;">Web Development</th><th style="background-color: black; color: white;">Digital Electronics</th><th style="background-color: aqua;">Web Development</th><th style="background-color: black; color: white;">Digital Electronics</th><th style="background-color: blueviolet;">Communicative English</th><th style="background-color: orangered;">Probability and queueing</th></tr>
        <tr><th>1:00-3:00</th><th style="background-color: red;">Fundamentals of c</th><th style="background-color: aquamarine;">Principle of chemistry</th><th style="background-color: yellow;">Mentor meeting</th><th style="background-color: blueviolet;">Communicative English</th><th style="background-color: orangered;">Probability and queueing</th><th style="background-color: aqua;">Web Development</th></tr>
        <tr><th>3:00-5:00</th><th style="background-color: antiquewhite;">Free Period</th><th style="background-color: antiquewhite;">Free Period</th><th Style="background-color: antiquewhite;">Free Period</th><th style="background-color: antiquewhite;">Free Period</th><th style="background-color: azure;">C.D.S</th><th style="background-color: antiquewhite;">Free Period</th></tr>
        </tr>
        </table>
        <br>
        <table border="5" cellpadding="10" style="align-items: center;">
            <tr><th>S.NO</th><th>Course Code</th><th>Course Name</th></tr>
            <tr><th>1</th><th>19AI304</th><th>Fundamentals of C</th></tr>
            <tr><th>2</th><th>19AI414</th><th>Fundamentals of Web Development</th></tr>
            <tr><th>3</th><th>19CY205</th><th>Principle of chemistry</th></tr>
            <tr><th>4</th><th>19EE404</th><th>Digital Electronics</th></tr>
            <tr><th>5</th><th>19EN101</th><th>Communicative English</th></tr>
            <tr><th>6</th><th>19EY708</th><th>C.D.S</th></tr>
            <tr><th>7</th><th>19MA222</th><th>Probability and Queueing</th></tr>
            <tr><th>8</th><th>ECA-M-SCOFT</th><th>Mentor Metting</th></tr>
        </table>
    </body>
</html>'''


## OUTPUT
![alt text](<Screenshot 2024-11-16 172253.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
