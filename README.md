<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Create Account</title>

<style>
body{
  font-family: Arial, sans-serif;
  background:#111;
  color:white;
  text-align:center;
  padding:50px;
}

form{
  max-width:400px;
  margin:auto;
}

input{
  width:100%;
  padding:12px;
  margin:10px 0;
  border:none;
  border-radius:5px;
}

button{
  background:#d4af37;
  color:black;
  padding:12px 20px;
  border:none;
  border-radius:5px;
  font-weight:bold;
  cursor:pointer;
}
</style>
</head>

<body>

<h1>Create Account</h1>

<form https://formspree.io/f/mrevlevy>
  <input type="email" placeholder="Email Address">
  <input type="password" placeholder="Password">
  <input type="password" placeholder="Confirm Password">
  <button type="button" onclick="submitForm()">
    Submit Registration
</button>

<script>
function submitForm() {
    alert("Registration submitted successfully!");
}
</script>
</form>
https://formspree.io/f/mrevlevy

</body>
</html>
