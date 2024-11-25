# Ex03 Time Table
## Date: 26-11-2024

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
        <style>
            td
            {
                text-align: center;
            }
        </style>
    </head>
    <body>
        <img src="/static/WEB_LOGO-01.png" height="93" weight="500">
        <table border="5" cellspacing="5" cellpadding="10" bgcolor="cyan">
            <br>
            <br>
            <caption align="top">SLOT TIME TABLE - SAI HRISHI M (24900846)</caption>
            <tr>
                <th bgcolor="yellow">Day\Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                
            </tr>
            <tr>
                <td bgcolor="yellow">8-10</td>
                <td colspan="3">FREE SLOT</td>
                <td>PHY</td>
                <td>CHE</td>
            </tr>
            <tr>
                <td bgcolor="yellow">10-12</td>
                <td>GRE</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>PHY</td>
            </tr>
            <tr>
                <td bgcolor="yellow">12-1</td>
                <td colspan="5">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="yellow">1-3</td>
                <td colspan="2">FREE SLOT</td>
                <td>MAT</td>
                <td>MAT</td>
                <td>SS</td>
            </tr>
            <tr>
                <td bgcolor="yellow">3-5</td>
                <td colspan="2">FREE SLOT</td>
                <td>GRE</td>
                <td>CHE</td>
                <td>FWAD</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="5" cellpadding="10">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamental Application of Web Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN612</td>
                <td>German Basic(GER)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19PH206</td>
                <td>Physics For Infomation Technology(PHY)</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering(CHE)</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra(MAT)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Soft Skill(SS)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-11-26 002822.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
