# Ex03 Time Table
## Date:14/03/2024

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
<title> Time Table </title>
</head>
<body>
<center><img src="logo.png" height="200" width="1200"></center>
<h1>
<center>SLOT TIMETABLE - Tharun V K (23003686)</center>
</h1>
<center>
<table bgcolor="green" border="9" cellspacing="10" cellpadding="10" width="800",height="1000">
<tr>
    <th bgcolor="red">Day/Time</th>
    <th bgcolor="red">Monday</th>
    <th bgcolor="red">Tuesday</th>
    <th bgcolor="red">Wednesday</th>
    <th bgcolor="red">Thursday</th>
    <th bgcolor="red">Friday</th>   
</tr>
<tr align="center">
    <th bgcolor="red">8-10</th>
    <td>ADVANCE C</td>
    <td>ETHICAL HACKING</td>
    <td>FREE SLOT</td>
    <td>FWAD</td>
    <td>PYTHON</td>   
</tr>
<tr align="center">
    <th bgcolor="red">10-12</th>
    <td>PYTHON</td>
    <td>COMPUTER NETWORKS</td>
    <td>ADVANCE C</td>
    <td>ETHICAL HACKING</td>
    <td>COMPUTER NETWORKS</td>     
</tr>
<tr>
    <th bgcolor="red">12-1</th>
    <th colspan="5" align="center">LUNCH</th>      
</tr>
<tr align="center">
    <th bgcolor="red">1-3</th>
    <td>FWAD</td>
    <td>ENGLISH</td>
    <td>FWAD</td>
    <td>PYTHON</td>
    <td>FREE SLOT</td>        
</tr>
<tr align="center">
    <th bgcolor="red">3-5</th>
    <td>FREE SLOT</td>
    <td>PYTHON</td>
    <td>FREE SLOT</td>
    <td>ENGLISH</td>
    <td>FREE SLOT</td>    
</tr>
</table>
</center>
<br>
<br>
<center>
<table border="3" cellspacing="10" cellpadding="10" width="800",height="1000">
<tr align="center">
    <th>S.No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>
<tr>
    <td align="center">1.</td>
    <td align="center">19AI414</td>
    <td>Fundamentals of Web Application Development</td>
</tr>
<tr>
    <td align="center">2.</td>
    <td align="center">19AI305</td>
    <td>Advanced C Programming</td>
</tr>
<tr>
    <td align="center">3.</td>
    <td align="center">19AI301C</td>
    <td>Python and Linear Algebra</td>
</tr>
<tr>
    <td align="center">4.</td>
    <td align="center">19EN101</td>
    <td>Communicative English</td>
</tr>
<tr>
    <td align="center">5.</td>
    <td align="center">19CS417</td>
    <td>Ethical Hacking Techniques</td>
</tr>
<tr>
    <td align="center">6.</td>
    <td align="center">19CS406</td>
    <td>Computer Networks</td>
</tr>
</table>
</center>
</body>
</html>

```

## OUTPUT
![Screenshot 2024-03-19 140449](https://github.com/tharunkumaran2006/slot/assets/151625188/99511db3-eb80-44c4-a6b8-d4322cf700f6)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
