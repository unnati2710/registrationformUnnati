
<html lang="en">
 <head>
<meta charset="utf-8">

<meta name="keywords" content="example, JavaScript Form Validation, Sample registration form" />
<meta name="description" content="This document is an example of JavaScript Form Validation using a sample registration form. " />
<link rel='stylesheet' href='js-form-validation.css' type='text/css' />

</head>
<body onload="document.registration.userid.focus();">
<h1>Registration Form</h1>
<form name='registration' onSubmit="return formValidation();">
<ul>
 <li> <label for="username">Name:</label></li>
<input type="text" name="username" size="50" />
  
<li><label for="email">Email:</label></li>
<input type="text" name="email" size="50" />

<li><label for="passid">Password:</label></li>
<input type="password" name="passid" size="12" />

<li><label for="address">Date Of Birth:</label></li>
<input type="text" name="dob" size="50" />
 <li><input type="checkbox" id="accept">Terms & Conditions</li>
<li><button onclick="myFunction()">Submit</button></li>
</ul>
</form>
</body>
</html>
