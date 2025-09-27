# Ex03 Time Table
## Date:20/09/2025
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
        <title>timetable
        </title>
        
    </head>
    <body>
        <img src="logo.png" width="470" height="100">
        <h2>SLOT TIMETABLE-VIVEK A(25013444)</h2>
        <table border="3" bgcolor="green">
            <tr bgcolor="yellow">
            <th>date/time</th>
            <th>monday</th>
            <th>tuesday</th>
            <th>wednesday</th>
            <th>thursday</th>
            <th>friday</th>
            <th>saturday</th>
            </tr>
            <tr bgcolor="red">
                <th>8-10</th>
                <td colspan="2">free slot</td>
                <td>fwad</td>
                <td colspan="2">free slot</td>
                <td>fwad</td>
            </tr>
            <tr bgcolor="red">
                <th>10-12</th>
                <td>python</td>
                <td>english</td>
                <td>fwad</td>
                <td>english</td>
                <td colspan="2">free slot</td>
            </tr>
            <tr bgcolor="red">
                <th>12-1</th>
                <th colspan='6'>lunch break</th>
            </tr>
            <tr bgcolor="red">
                <th>1-3</th>
                <td colspan="2">python</td>
                <td>mentor meet</td>
                <td>python</td>
                <td>fwad</td>
                <td>fwad</td>
            </tr>
            <tr bgcolor="red">
                <th>3-5</th>
                <td colspan="3">english</td>
                <td>python</td>
                <td>free slot</td>
                <td>english</td>
            </tr>
        </table>
        <br>


        </br>
        <table border="3">
            <tr>
                <th>si.no</th>
                <td>subject code</td>
                <td>subject name</td>
            </tr>
            <tr>
            <th>1</th>
            <td>19AI414</td>
            <td>fwad</td>
            </tr>
            <tr>
                <th>1</th>
                <td>19EN101</td>
                <td>english</td>
            </tr>
            <tr>
                <th>3</th>
                <td>19AI301</td>
                <td>python</td>
            </tr>
        </table>
    </body>
  
</html>

```


## OUTPUT
![alt text](<Screenshot (23).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
