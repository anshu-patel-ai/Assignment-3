!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coding Club</title>
<link rel="icon" href="favicon.ico">
</head>
<body>
<nav>
<a href="#events">Events</a> |
<a href="#register">Register</a> |
<a href="#about">About</a> |
<a href="#contact">Contact</a>
</nav>
<h1>Coding Club</h1>
<h2 id="events">Upcoming Events</h2>
<table border="1">
<caption>Club Events</caption>
<thead>
<tr><th>Event</th><th>Date</th><th>Venue</th></tr>
</thead>
<tbody>
<tr><td>HTML Workshop</td><td>12 Nov</td><td>Lab 1</td></tr>
<tr><td>Hackathon</td><td>20 Nov</td><td>Seminar Hall</td></tr>
</tbody>
<tfoot>
<tr><td colspan="3">Total events: 2</td></tr>
</tfoot>
</table>
<h2 id="register">Register</h2>
<form>
<label for="name">Name:</label>
<input type="text" id="name" name="name" value="Anshu Patel" required>
<br><br>
<label for="email">Email:</label>
<input type="email" id="email" name="email" value="anshupatel976230@gmail.com" required>
<br><br>
<label for="password">Password:</label>
<input type="password" id="password" name="password" required>
<br><br>
<label for="dob">Date of birth:</label>
<input type="date" id="dob" name="dob">
<br><br>
<label for="phone">Phone:</label>
<input type="tel" id="phone" name="phone" value="9762309872">
<br><br>
Gender:
<input type="radio" id="male" name="gender" value="Male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="Female">
<label for="female">Female</label>
<br><br>
Interests:
<input type="checkbox" id="web" name="interest" value="Web Development">
<label for="web">Web</label>
<input type="checkbox" id="dsa" name="interest" value="DSA">
<label for="dsa">DSA</label>
<br><br>
<label for="branch">Branch:</label>
<select id="branch" name="branch">
<option value="AI" selected>B.Tech AI</option>
<option value="CSE">CSE</option>
<option value="IT">IT</option>
</select>
<br><br>
<label for="reason">Why do you want to join?</label>
<br>
<textarea id="reason" name="reason" rows="3" cols="30"></textarea>
<br><br>
<button type="submit">Register</button>
</form>
<h2 id="about">About</h2>
<p>Coding Club helps students learn programming and web development.</p>
<h2 id="contact">Contact</h2>
<p>Anshu Patel | Invertis University</p>
</body>
</html>

