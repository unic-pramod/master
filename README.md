# master
new project
<!DOCTYPE html>
<html>
<head>
	<title>My Web Application</Birdstore>
</head>
<body>
	<h1>Welcome to my web application!</h1>
	<p>Enter your name: <input type="text" id="nameInput"></p>
	<button onclick="greet()">Greet</button>
	<p id="greeting"></p>

	<script src="app.js"></script>
</body>
</html>

function greet() {
	// Get the value of the name input field
	var name = document.getElementById("nameInput").value;

	// Set the greeting text
	var greetingText = "Hello, " + name + "!";
	document.getElementById("greeting").innerHTML = greetingText;
}
