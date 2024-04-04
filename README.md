# Ex03 Time Table
## Date: 4.4.23
## reg no:212223240104

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
<title>Slot Timetable</title>
</head>
<body>
<img  src="na23.png" height="100" width="540" style="padding-left: 30%;">
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SCHEDULE OF ALL COURSES</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >C ENGLISH</td>
<td></td>
<td>WEB </td>
<td></td>
<td>WEB</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>PRO MICRO</td>
<td> STORK MARKET </td>
<td>PROBABBILITY</td>
<td></td>
<td>TRAMS FORM AND APPLICATION</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >COMPUTER NETWORK </td>
<td>PHYAICS</td>
<td>PHYSICS</td>
<td></td>
<td>PROGRAMING MICRO</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>TRANSFORM</td>
<td>COMPUTERNETWORK</td>
<td>FUNDAMENTALS OF WEB</td>
<td>FPHYSICS</td>
<td>STOCK MARKET</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CSE401</td>
<td>C COMPUTER NETWORK</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH325</td>
<td> PHYSICS (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EEE32</td>
<td>MICRO CONTROLER</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>PROBABILITY (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS (SS)</td>
</tr>
</table>
</body>
</html>

```

## OUTPUT
![image](https://github.com/feryjfgkuyfgewjfgew/slot/assets/150319377/8a6e2cb3-547b-464f-bbb2-a1431cf72668)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
