# Ex03 Time Table
# Date:03.12.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html>
    <center>
        <img src="WhatsApp Image 2024-10-20 at 13.34.20_41a9b8cc.jpg"
    </center>
    <head>
        <title>TIME TABLE</title>
        <style>
            table,th,td{
                text-align: center;
                border: 4px ;
            }
        </style>
    </head>
    <body>
        <center>
            <h2 style="text-align: center;"> TIME TABLE- SAMRITHA R 24013637</h2>
            <table style="background-color: rgb(186, 27, 91)" >
            <tr style="background-color: rgb(186, 27, 91);"></tr>
                <th>DAYS</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91)">MONDAY</th>
                <td></td>
                <td>Web application</td>
                <td rowspan="7">l<br>u<br>n<br>c<br>h</td>
                <td>Math</td>
                <td></td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91);">TUESDAY</th>
                <td>Computer application</td>
                <td></td>
                
                <td>BEEE</td>
                <td></td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91);">WEDNESDAY</th>
                <td></td>
                <td>Career</td>
                
                <td> Mentor Meet</td>
                <td>Chemistry</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91);">THURSDAY</th>
                <td>Math</td>
                <td>Computer application</td>
                
                <td>Web application</td>
                <td></td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91);">FRIDAY</th>
                <td></td>
                <td>BEEE</td>
                
                <td>Public Speaking</td>
                <td></td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(186, 27, 91);">SATURDAY</th>
                <td></td>
                <td>Public Speaking</td>
                
                <td>Chemistry</td>
                <td>Web application</td>
            </tr>
           
            
        </table>
        </center>
    </body>
</html>
 <br>
 <br>
 <center>
    <table bgcolor="black">
        <tr style="background-color: rgb(235, 181, 111);">
            <th>S.no</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(236, 176, 103);">1</th>
            <td>19MA201</td>
            <td>Calculus ans Matrix Algebra</td>
            
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(222, 168, 102);">2</th>
            <td>19CS305</td>
            <td>Computer Architecture</td>
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(214, 161, 95);">3</th>
            <td>19EE305</td>
            <td>Basic Electrical, Electronics and Measurement Engineering</td>
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(204, 152, 89);">4</th>
            <td>19AI414</td>
            <td>Fundamental od Web Application Development</td>
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(209, 157, 92);">5</th>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engneering</td>
        </tr>
        <tr style="background-color: antiquewhite;">
            <th style="background-color: rgb(208, 151, 81);">6</th>
            <td>19EY708</td>
            <td>Career Develpoment Skills</td>
        </tr>
    </table>
 </center>
```
# OUTPUT
![alt text](<Screenshot 2024-12-13 120847.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
