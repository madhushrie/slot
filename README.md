# Ex03 Time Table
## Date:15.11.24

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
<img src="logo.png" height="200" width="1000">
<table border="2">
    <h1> SLOT TIME TABLE - MADHU SHRIE J (24900852) </h1>
    <tr bgcolor="red">
        <th>TIME/DAY</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESSDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr bgcolor="yellow">
        <th>8-10</th>
        <td>free</td>
        <td>web</td>
        <td>edm</td>
        <td>english</td>
        <td>free</td>
        <td>maths</td>
    </tr>
    <tr bgcolor="yellow">
        <th>10-12</th>
        <td>english</td>
        <td>maths</td>
        <td>free</td>
        <td>c</td>
        <td>c</td>
        <td>free</td>
    </tr>
    <tr bgcolor="yellow">
        <th>1-3</th>
        <td>edm</td>
        <td>es</td>
        <td>mentor</td>
        <td>python</td>
        <td>web</td>
        <td>web</td>
    </tr>
    <tr bgcolor="yellow">
        <th>3-5</th>
        <td>free</td>
        <td>python</td>
        <td>free</td>
        <td>free</td>
        <td>free</td>
        <td>free</td>
    </tr>
    </table>
    <table border="2">
        <tr bgcolor="red">
            <th>S.no</th>
            <th>Couse code</th>
            <th>Course name</th>
        </tr>
        <tr bgcolor="yellow">
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr bgcolor="yellow">
            <td>2</td>
            <td>19AI304</td>
            <td>FUNDAMENTAL OF C PROGRAMMING</td>
        </tr>
        <tr bgcolor="yellow">
            <td>3</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr bgcolor="yellow">
            <td>4</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr bgcolor="yellow">
            <td>5</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELING</td>
        </tr>
        <tr bgcolor="yellow">
            <td>6</td>
            <td>19AI403</td>
            <td>STATISTICS AND NUMERICAL METHODS</td>
        </tr>
        <tr bgcolor="yellow">
            <td>7</td>
            <td>19MA211</td>
            <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
        </tr>
    </table>
```
## OUTPUT
![alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
