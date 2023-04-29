<!DOCTYPE html>
<html>
<head>
	<title>Printing Shop</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Printing Shop</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">About Us</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section class="banner">
			<img src="banner.jpg" alt="Banner Image">
		</section>
		<section class="services">
			<h2>Our Services</h2>
			<ul>
				<li><a href="#">Business Cards</a></li>
				<li><a href="#">Flyers and Brochures</a></li>
				<li><a href="#">Posters</a></li>
				<li><a href="#">Signs and Banners</a></li>
			</ul>
		</section>
		<section class="about">
			<h2>About Us</h2>
			<p>We are a printing shop that provides high-quality printing services for businesses and individuals. We use the latest technology and equipment to ensure that our customers get the best possible results.</p>
		</section>
		<section class="contact">
			<h2>Contact Us</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name"><br><br>
				<label for="email">Email:</label>
				<input type="email" id="email" name="email"><br><br>
				<label for="message">Message:</label>
				<textarea id="message" name="message"></textarea><br><br>
				<input type="submit" value="Send">
			</form>
		</section>
	</main>
	<footer>
		<p>&copy; 2023 Printing Shop. All rights reserved.</p>
	</footer>
</body>
</html>
And here's the corresponding CSS code:

css
Copy code
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 20px;
}

h1 {
	margin: 0;
	font-size: 36px;
}

nav {
	float: right;
	margin-top: 10px;
}

nav ul {
	list-style: none;
	margin: 0;
	padding: 0;
}

nav li {
	display: inline-block;
	margin-left: 20px;
}

nav li:first-child {
	margin-left: 0;
}

nav a {
	color: #fff;
	text-decoration: none;
}

nav a:hover {
	text-decoration: underline;
}

.banner img {
	width: 100%;
}

.services {
	background-color: #f9f9f9;
	padding: 20px;
}

.services h2 {
	margin-top: 0;
}

.services ul {
	list-style: none;
	margin: 0;
	padding: 0;
}

.services li {
	margin-bottom: 10px;
}

.services a {
	color: #333;
	text-decoration: none;
}

.services a:hover {
	text-decoration: underline;
}

.about {
	padding: 20px;
}

.about h2 {
	margin-top: 0;
}

.contact {
