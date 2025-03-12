 Ex03 Time Table
## Date: 12/03/2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center><h1>SLOT TIME TABLE - JAYADEV PALLINTI(212223240058)</h1></center>
    <center><table border="5"</center>
        <caption></caption>
        <tr>
            
            <th bgcolor="grey">DAY/TIME</th>
            <th bgcolor="yellow">MONDAY</th>
            <th bgcolor="yellow">TUESDAY</th>
            <th bgcolor="yellow">WEDNESDAY</th>
            <th bgcolor="yellow">THURSDAY</th>
            <th bgcolor="yellow">FRIDAY</th>
            <th bgcolor="yellow">SATURDAY</th>
        </tr>
        <tr>
            <td bgcolor="yellow">8 TO 10</td>
            <td>FWD</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>PHY</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="yellow">10 TO 12</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>CHY</td>
            <td>SS</td>
        </tr>
        <tr>
            <td bgcolor="yellow">12 TO 1</td>
            <td colspan="6" style="text-align: center;">LUNCH BRAK</td>
        </tr>
        <tr>
            <td bgcolor="yellow">1 TO 3</td>
            <td>MAT</td>
            <td>FWD</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="yellow">3 TO 5</td>
            <td>MAT</td>
            <td>PHY</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>SS</td>
            <td>CHY</td>
        </tr>
        
        
        
</body>
</html>
```

## OUTPUT
```
![image](https://github.com/user-attachments/assets/ef3889ce-a37e-4171-ab16-2fc458a58c26)

```

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
