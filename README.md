<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		body {
			font-family: Arial, sans-serif;
			text-align: center;
			background-image: url("https://images.unsplash.com/photo-1554260570-e9689a3418b8?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=882&q=80");
			background-size: cover;
			justify-content: center;
			align-items: center;
		}
		.login-form {
			display: inline-block;
			margin: 0 auto;
			text-align: left;
			padding: 20px;
			border: 1px solid #ccc;
			border-radius: 5px;
			background-color: rgba(255, 255, 255, 0.8);
			align-items: center;
		}
		input[type=text], input[type=password] {
			width: 100%;
			padding: 12px 20px;
			margin: 8px 0;
			box-sizing: border-box;
			border: 1px solid #ccc;
			border-radius: 4px;
		}
		input[type=submit] {
			width: 100%;
			background-color: #4CAF50;
			color: white;
			padding: 14px 20px;
			margin: 8px 0;
			border: none;
			border-radius: 4px;
			cursor: pointer;
		}
		input[type=submit]:hover {
			background-color: #45a049;
		}
		.error {
			color: red;
			font-weight: bold;}
		@media only screen and (max-width: 600px) {
			form {
				padding: 10px;
			}
			input[type=text], input[type=password] {
				padding: 8px;
			}
			input[type=submit] {
				padding: 10px;
			}
			body {
				font-size: 1.1em;
			}
		}
	</style>
</head>
<body>
	<form class="login-form" action="/login" method="POST">
		<label for="username">Username:</label><br>
		<input type="text" id="username" name="username"><br>
		<label for="password">Password:</label><br>
		<input type="password" id="password" name="password"><br><br>
		<input type="submit" value="Submit" onclick="validateForm()">
	</form> 
	<div class="error" id="error"></div>
	<script>
		function validateForm() {
			var username = document.getElementById	; 
			var username =
			document.getElementById("username").value;
			var password =
			document.getElementById("password").value;
			if (username == "Abtin816" && password == "atn197808") {
				window.location.href =
				'https://webdjrkd.simdif.com';
			} else {
				document.getElementById("error").innerHTML = "Error: Incorrect username or password.";
			}
		}
	</script>
</body>
</html>
