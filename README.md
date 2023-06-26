# portfolio
just a html-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="student.css">
</head>
<body>
    <h1>STUDENT REGISTRATION FORM</h1>
    <div class="container">
        <form>
            <div class="form-group">
                <label for="name">NAME:</label>
                <input type="text" id="name" name="name" maxlength="50" autofocus="on" required>
            </div><br>
            <div class="form-group">
                <label for="fname">FATHER'S NAME:</label>
                <input type="text" id="fname"name="fathersname" maxlength="20" autofocus="on" required>
            </div><br>
            <div class="form-group">
                <label for="mname">MOTHER'S NAME:</label>
                <input type="text" id="mname" name="mothersname" maxlength="20" autofocus="on" required>
            </div><br>
            <div class="form-group">
                <label for="pnum">PHONE NUMBER:</label>
                <input type="number" id="pnum" name="phonenumber"  required>
            </div><br>
            <div class="form-group">
                <label for="email">E-MAIL ADDRESS:</label>
                <input type="text" id="email" name="email address" maxlength="20" autofocus="on" required>
            </div><br>
            <div class="form-group">
                <label for="gname">GENDER:</label>
                <input type="checkbox" id="gname" name="gender" value="Male" required>MALE  
                <input type="checkbox" id="gname" name="gender" value="Femaale" required>FEMALE  
                <input type="checkbox" id="gname" name="gender" value="other" required>OTHER
            </div><br>
            

            
            
        
            
            
            
        </form>
    </div>    
</body>
</html>
