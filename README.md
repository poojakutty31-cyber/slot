# Ex03 Time Table
## Date:10.12.25

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - S SIVASAKTHI (25018480)</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>SAVEETHA ENGINEERING COLLEGE</h2>
    <h3>SLOT TIME TABLE - S SIVASAKTHI (25018480)</h3>

    <tableborder="1">
        <tr BGCOLOR="YELLOW">
            <th>DAY/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <TH>SATURDAY</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>PUBLIC SPEAKING</td>
            <td>C PROGRAMMING</td>
            <td>PUBLIC SPEAKING</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>C PROGRAMMING</td>
            <td></td>
            <td>WEB APPLICATION</td>
            <td></td>
            <td>WEB APPLICATION</td>
            <td>WEB APPLICATION</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>WEB APPLICATION</td>
            <td>PUBLIC SPEAKING</td>
            <td>MENTOR MEET</td>
            <td>PUBLIC SPEAKING</td>
            <td>WEB APPLICATION</td>
            <td></td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td></td>
            <td>C PROGRAMMING</td>
            <td>C PROGRAMMING</td>
            <td>C PROGRAMMING</td>
            <td></td>
            <td></td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <tableborder="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>WEB APPLICATION</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI304</td>
            <td>C PROGRAMMING</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EN105</td>
            <td>PUBLIC SPEAKING</td>
        </tr>
            </table>
</body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2025-12-24 083800.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
