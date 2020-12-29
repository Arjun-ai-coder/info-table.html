<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=100px, initial-scale=1">
<style>
body {
  font-family: cursive;
  background-color: black;
}

* {
  box-sizing: border-box;
}

/* Add padding to containers */
.container {
  padding: 50px;
  background-color: white;
}

/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: box;
  background: white;
}





/* Set a style for the submit button */
.registerbtn {
  background-color:green;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor:pointer;
  width: 100%;
  
}

.submitbtn:hover {
  opacity: 1;
}

/* Add a blue text color to links */
a {
  color: darkblue;
}

/* Set a grey background color and center the text of the "sign in" section */
.signin {
  background-color: white;
  text-align: center;
}
</style>
</head>
<body>

<form action="/action_page.php">
  <div class="container">
    <h1>personal info</h1>
   
    <hr>
    
    <label for="name"><b>First name</b></label>
    <input type="text" name="name" placeholder="Enter your first name" required >
    
    <label for="name"><b>Second name</b>
    <input type="text" placeholder="Ener your second name" required><br>
    
    
    
    
   
    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" id="email"  pattern=".+@gmail.com.com" required>
    
    
    <label for="gender"><b>Gender</b></label><br>
  <input type="radio" name="gender" value="male"> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
  <br>
   <label for="birthday"><b>Date of birth</b></label>
  <input type="date" id="birthday" name="birthday">
  
  <br>
  
  <label for="number"><b>Contact number</b></label>
  <input type="text" placeholder="Enter your contact number" option>



    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" id="psw" required>
    

    <label for="psw-repeat"><b>Re-enter Password</b></label>
    <input type="password" placeholder="Repeat Password" name="psw-repeat" id="psw-repeat" required>
    <hr>

        <button type="submit" class="registerbtn">submit</button>
      </label>
    </div>
    </form>
    </body>
</html>

  
