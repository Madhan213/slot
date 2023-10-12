# Ex03 Time Table
## DATE:-12/10/2023
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

## CODE
```
<!DOCTYPE html>
<meta name="viewport">
<img src="logo.png" width="500" >

<html>
<head>
    <title>Time Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: cyan  (173, 230, 221);">
    <p>Slot Time Table - Madhan (212221040091) </p>

<table border="1">
    <tr>
        <th style="background-color: rgb(119, 31, 181);">Day/Time</th>
        <th style="background-color: rgb(119, 31, 181);">Monday</th>
        <th style="background-color: rgb(119, 31, 181);">Tuesday</th>
        <th style="background-color: rgb(119, 31, 181);">Wednesday</th>
        <th style="background-color: rgb(119, 31, 181);">Thursday</th>
        <th style="background-color: rgb(119, 31, 181);">Friday</th>
        <th style="background-color: rgb(119, 31, 181);">Saturday</th>
    </tr>
    
    <tr>
        <td style="background-color: rgb(15, 82, 182) ;">8-10</td>
        <td style="background-color: rgb(15, 151, 182);"> Free</td>
        <td style="background-color: rgb(15, 151, 182);">Compiler Design</td>
        <td style="background-color: rgb(15, 151, 182);">Free</td>
        <td style="background-color: rgba(15, 151, 182);" >Theory Of Computation</td>
        <td style="background-color: rgb(15, 151, 182);">Free</td>
        <td style="background-color: rgb(15, 151, 182);">Applied Artificial Intelligence</td>
    </tr>
    <tr>
        <td style="background-color: rgb(15, 82, 182);">10-12</td>
        <td style="background-color: rgb(15, 151, 182);">Fundamental Of Web Application Development</td>
       <td style="background-color: rgb(15, 151, 182);">Free</td>
       <td style="background-color: rgb(15, 151, 182);">Compiler Design</td>
       <td style="background-color: rgb(15, 151, 182);">Theory Of Computation</td>
       <td style="background-color: rgb(15, 151, 182);">Computer Network</td>
       <td style="background-color: rgb(15, 151, 182);">Free</td>
    </tr>
    <tr>
        <td style="background-color: rgb(15, 82, 182);">1-3 </td>
        <td style="background-color: rgb(15, 151, 182);">Free</td>
        <td style="background-color: rgb(15, 151, 182);">Fundamental Of Web Application Development</td>
        <td style="background-color: rgb(15, 151, 182);">Theory Of Computation</td>
        <td style="background-color: rgb(15, 151, 182);">Operating System</td>
        <td style="background-color: rgb(15, 151, 182);">Compiler Design</td>
        <td style="background-color: rgba(15, 151, 182);">Free</td>
    </tr>
    <tr>
        <td style="background-color: rgb(15, 82, 182);">3-5 </td>
        <td style="background-color: rgb(15, 151, 182);">Operating System</td>
        <td style="background-color: rgb(15, 151, 182);">Fundamentals Of Web Apllication Development</td>
        <td style="background-color: rgb(15, 151, 182);">Computer Network</td>
        <td style="background-color: rgb(15, 151, 182);">Free</td>
        <td style="background-color: rgb(15, 151, 182);">Applied Artificial Intelligence</td>
        <td style="background-color: rgb(15, 151, 182);">Free</td>
    </tr>
    
</table>
<br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS409</td>
            <td>Compiler Design(CD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS406</td>
            <td>Computer Network(CN)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS405</td>
            <td>Operating System (OS)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI409</td>
            <td>Applied Artificial Intelligence(AAI)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CS407</td>
            <td>Theory Of Computation(TOC)</td>
        </tr>
</body>
</html>
```
## OUTPUT
![image](https://github.com/Madhan213/slot/assets/130206230/d2ba6648-7510-4ec1-a83b-7fab29d92667)


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
