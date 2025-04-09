# Ex03 Time Table
## Date: 09.04.2025

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
    <title>Slot Time Table - Sathana V</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="100"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - SATHANA V (212224220091)</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td> - </td>
            <td>FREE SLOT</td>
            <td> - </td>
            <td>PHY</td>
            <td>-</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>FWAD</td>
            <td>M2</td>
            <td>FWAD</td>
            <td>CN</td>
            <td>CA</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>CA</td>
            <td>PHY</td>
            <td>MM</td>
            <td></td>
            <td>M2</td>
        </tr>
       <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>CN</td>
            <td>FREE</td>
            <td>HV</td>
            <td>FREE</td>
            <td>EVS</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS305</td>
            <td>Computer architrcture(CA)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH814</td>
            <td>Physics for quantum computing (PHY)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS406</td>
            <td>Computer network (CN)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (M2)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19HS801</td>
            <td>Human values (HV)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>ECA-M</td>
            <td>Mentor meet (MM)</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19CY801</td>
            <td>Environmental sciences and sustainability (EVS)</td>
        </tr>

    </table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-04-09 111157.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
