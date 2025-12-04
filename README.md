# Ex03 Time Table
## Date:28/11/2025
ref no:25003242

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

~~~
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - your name , reg no</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="/static/logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE- R K NIKKIL VARSHAN(25003242) </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="2" bgcolor="Cyan">CRYPTO</th>
            <th colspan="1" bgcolor="Cyan">PYTHON</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">PYTHON</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">PYTHON</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">CRYPTO</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
             <th colspan="1" bgcolor="Cyan">PYTHON</th>
             <th colspan="1" bgcolor="Cyan">CRYPTO</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">PYTHON</th>
            <th colspan="1" bgcolor="Cyan">CRYPTO</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI414</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19AI403</th>
            <th colspan="2" bgcolor="White">PYTHON </th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19CS547</th>
            <th colspan="2" bgcolor="White">CRYPTO CURRENCY</th> 
        </tr>
           </table>
</body>
</html>
~~~

## OUTPUT
<img width="1831" height="903" alt="Screenshot 2025-12-04 104709" src="https://github.com/user-attachments/assets/9d616dcc-ee69-4b76-879f-e15ef57e2e2c" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
