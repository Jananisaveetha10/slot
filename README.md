# Ex03 Time Table
## Date:25/11/2024

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
    <body>
        <img src="logo.png">
        <table border="2" cellspacing="3">
            <caption>Weekly Timetable-janani(24900080)</caption>
            <tr bgcolor="pink" align="center">
                <th>Day/Time</th>
                <th> Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>

            </tr>
            <tr align="centre"> 
                <td>8-10</td>
                <td EDM="3">Free</td>
                <td>EDM</td>
                <td>COMM E</td>
                <td>WEB</td>
            </tr>
            <tr align="center"> 
                <td>10-12</td>
                <td>Comm E</td>
                <td>MATH</td>
                <td>Chem</td>
                <td>FREE</td>
                <td>Chem</td>
                <td>MATH</td>
            </tr>
            <tr align="centre">
                <td>12-1</td>
                <td colspan="6">LUNCH</td>

            </tr>
            <tr align="centre"> 
                <td>1-3</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>MENT Meet</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>FREE</td>
            </tr>
            <tr align="centre"> 
                <td>3-5</td>
                <td>Free</td>
                <td>FREE</td>
                <td colspan="4">Free</td>

            </tr>
        </table>
        <table border="2" cellpadding="2">
            <tr> 
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr> 
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>2</td>
                 <td>19CY205</td>
                <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr> 
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </tr>
            <tr>
                <td>5</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>
            </tr>
            <tr> 
                <td>6</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            
        </table>


        </table>
    </body>
</html>

```

## OUTPUT
![Screenshot 2024-11-26 092050](https://github.com/user-attachments/assets/7673d9cb-c035-4111-ad48-d7c627fcfaf5)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
