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
-------------------css file-----------------------------
body
{
    background-color:mediumpurple;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    margin:0;
    padding:0;
    display:table;
    justify-content:center;
    display:flex;
}
form {
    background-color: white;
    width: 400px;
    border-radius: 10px;
    padding: 20px 40px;
    box-shadow: 0 10px 25px rgba(92, 99, 105, .2);
}
input[type=text]
{
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
}
label2 {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size:26px;
}

input[type=password]
{
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
}
label3 {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 26px;
}
input[type=email] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
}
label4 {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 26px;
}
input[type=date] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
}
label5 {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 26px;
}
input[type=submit] {
    background-color:aqua;
    border: none;
    color: black;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 26px;
    font:200;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
   
}
label1 {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 26px;
}
