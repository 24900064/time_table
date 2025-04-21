# Ex03 Time Table
# Date:21-04-2025
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
~~~
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE (EVEN SEM)</title>
</head>
<body>
    <br>
    <h2 style="text-align: center;">SLOT TIME TABLE - PRAGATHEESHRAJ D (212224230199)</h2>

    <table border="5" width="570" align="center">
        <tr>
            <th bgcolor="WHITE">Day/Time</th>
            <th bgcolor="WHITE">Monday</th>
            <th bgcolor="WHITE">Tuesday</th>
            <th bgcolor="WHITE">Wednesday</th>
            <th bgcolor="WHITE">Thursday</th>
            <th bgcolor="WHITE">Friday</th>
        </tr>
        <tr>
            <th bgcolor="NAVY">8-10</th>
            <td bgcolor="PINK">INTRO OF ML</td>
            <td bgcolor="WHITE">FREE SLOT</td>
            <td bgcolor="PINK">FWAD</td>
            <td bgcolor="WHITE">FREE SLOT</td>
            <td bgcolor="SILVER">PRINCIPAL OF CHEMISTRY</td>
        </tr>
        <tr>
            <th bgcolor="NAVY">10-12</th>
            <td bgcolor="PINK">COMMUNICATIVE ENGLISH</td>
            <td bgcolor="olive">FWAD</td>
            <td bgcolor="SILVER">COMMUNICATIVE ENGLISH</td>
            <td bgcolor="WHITE">FREE SLOT</td>
            <td bgcolor="WHITE">FREE SLOT</td>
        </tr>
        <tr>
            <th bgcolor="NAVY">12-1</th>
            <td colspan="5" align="center" bgcolor="CREAM">LUNCH</td>
        </tr>
        <tr>
            <th bgcolor="NAVY">1-3</th>
            <td bgcolor="olive">FWAD</td>
            <td bgcolor="TEAL">INTRO OF ML</td>
            <td bgcolor="SILVER">COMPUTER NETWORK</td>
            <td bgcolor="SILVER">COMMUNICATIVE ENGLISH</td>
            <td bgcolor="PINK">COMPUTER NETWORK</td>
        </tr>
        <tr>
            <th bgcolor="NAVY">3-5</th>
            <td bgcolor="WHITE">FREE SLOT</td>
            <td bgcolor="WHITE">FREE SLOT</td>
            <td bgcolor="olive">FWAD</td>
            <td bgcolor="PINK">PY</td>
            <td bgcolor="WHITE">FREE SLOT</td>
        </tr>
    </table>

    <br>

    <table border="5" width="570" align="center">
        <tr>
            <td>S.NO.</td>
            <td>Subject Code</td>
            <td>Subject Name</td>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI301</td>
            <td>Python Programming</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS406</td>
            <td>Computer Network</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19AI410</td>
            <td>Intro Of ML</td>
        </tr>
    </table>
</body>
</html>

~~~
# OUTPUT

![Screenshot 2025-04-21 144853](https://github.com/user-attachments/assets/4401d759-2c07-41f6-b4d8-02d0de0fb2a4)



# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
