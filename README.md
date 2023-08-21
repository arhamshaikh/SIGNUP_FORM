# SIGNUP_FORM
#Simple Signup form in programming language HTML with CSS
#html file 
<!DOCTYPE html>

<html>
<head>
    <meta charset="utf-8" />
    <title> SIGNUP FORM </title>
    <link type="text/css" rel="stylesheet"  href="style.css">
</head>
<body>
    <form>
        <table>
            <tr>
                <td>
                        <center>
        <h1 style="background-color:aqua"> SIGNUP FORM</h1>
                   
        <label1 for="fname"><b>FIRST NAME</b></label1>
        <input type="text" id="fname" name="fname"required><br><br>
        <label2 for="lname"><b> LAST NAME</b></label2>
        <input type="text" id="lname" name="lname" required><br><br>
        <label3 for="DateOfBirth"><b>DATE OF BIRTH</b></label3>
        <input type="date" id="dateofbirth" name="DateOfBirth" required><br><br>
        <label4 for="Email"><b> EMAIL</b></label4>
        <input type="email" id="Email" name="Email" required><br><br>
        <label5 for="Password"><b> PASSWORD</b></label5>
        <input type="password" id="password" name="Password"><br><br>
        <input type="submit" value="Submit" required>
                        </center>
                    </td>
                </tr>
            </table>
    </form>
</body>
</html>
