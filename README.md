<!DOCTYPE html>

<html> <head> <title>User Registration Form</title> </head>

<body>

<h2 align="center">User Registration Form</h2>

<form>
    <label>Full Name:</label><br>
    <input type="text" name="name" placeholder="Enter your name" required>
    <br><br>

    <label>Email:</label><br>
    <input type="email" name="email" placeholder="Enter your email" required>
    <br><br>

    <label>Password:</label><br>
    <input type="password" name="password" placeholder="Enter password" required>
    <br><br>

    <label>Confirm Password:</label><br>
    <input type="password" name="confirm_password" placeholder="Confirm password" required>
    <br><br>

    <label>Phone Number:</label><br>
    <input type="tel" name="phone" placeholder="Enter phone number" required>
    <br><br>

    <label>Date of Birth:</label><br>
    <input type="date" name="dob">
    <br><br>

    <label>Gender:</label><br>
    <input type="radio" name="gender" value="Male"> Male
    <input type="radio" name="gender" value="Female"> Female
    <input type="radio" name="gender" value="Other"> Other
    <br><br>

    <label>Address:</label><br>
    <textarea name="address" rows="4" cols="30" placeholder="Enter your address"></textarea>
    <br><br>

    <input type="submit" value="Register">
    <input type="reset" value="Clear">

</form>


</body> </html>
