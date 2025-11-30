<!DOCTYPE html>
<html>
<head>
	<title>My Portfolio</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
	body{
		background-image: linear-gradient(
        rgba(0, 0, 0, 0.6), 
        rgba(0, 0, 0, 0.6)
		), url('https://media1.tenor.com/m/9vRAkntogEMAAAAd/background.gif');
		background-size: cover;
		padding:0;
		margin:0;
		background-attachment: fixed;
		color: #fff;
		font-size: 20px;
		font-family: Candara, Calibri, Segoe UI, sans-serif;
	}
	nav {
		background-color: rgba(0,0,0,0.5);
		backdrop-filter: blur(6px);
		-webkit-backdrop-filter: blur(6px);
		padding: 10px;
		margin: 0 auto;
		position: sticky;
		top: 0;
    }
	nav a {
		margin: 0 15px;
		text-decoration: none;
		color: #fff;
		font-weight: bold;
    }
    nav a:hover {
		color: #BB8AFB; 
	}
	a {
		text-decoration: none;
		transition: all 0.4s;
	}
	a:hover {
		letter-spacing: 4px;
		color: #BB8AFB;
	}
	#main {
		width: 70%;
		margin: 0 auto;
	}	
	section {
		margin: 40px auto;
	}
	h1 {
		margin: 30px auto;
		margin-bottom: 40px;
	}
	h2 {
		margin: 30px auto;
		margin-bottom: 40px;
	}
	h3 {
		margin: 30px auto;
		margin-bottom: 40px;
	}
	p {
		margin: 30px auto;
		margin-bottom: 40px;
		max-width: 800px;
	}
	.project {
		display: grid;
		grid-template-columns: 200px 1fr 120px;
		gap: 20px;
		align-items: center;
		margin-bottom: 30px;
	}
	.project h3 {
		margin: 0;
		text-align: right;
	}
	.project p {
		margin: 0;
	}
	#RecentProjects p {
		text-align: left;
	}
	#Home {
		height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		text-align: center;
	}
	#Home h1 {
		font-size: 5rem;
		margin: 0;
		text-shadow: 0 0 10px rgba(187, 138, 251, 0.7);
	}
	#Home h2 {
		font-size: 2rem;
		margin: 20px 0 0 0;
		font-family:"times new roman";
	}
	#Home h1, #Home h2 {
		animation: fadeIn 2s ease-in-out;
	}
	@keyframes fadeIn {
		from { opacity: 0; transform: translateY(20px); }
		to { opacity: 1; transform: translateY(0); }
	}
	hr {
		border: none;
		border-top: 2px solid #BB8AFB;
		width: 50%;
		margin: 40px auto;
		animation: expandWidth 5s ease-in-out forwards infinite alternate;
	}
	@keyframes expandWidth {
		from { width: 50%; opacity: 0.7;}
		to { width: 40%; opacity: 1;}
	}
	.scroll-down {
		position: absolute;
		bottom: 20px;
		font-size: 2rem;
		animation: bounce 2s infinite;
		color: #BB8AFB;
	}
	@keyframes bounce {
		0%, 100% { transform: translateY(0); }
		50% { transform: translateY(10px); }
	}
	#AboutMe h2 {
		font-family:"times new roman";
	}
	#Hobbies h2 {
		font-family:"times new roman";
	}
	#Skillset h2 {
		font-family:"times new roman";
	}
	#RecentProjects h2 {
		font-family:"times new roman";
	}
	html {
		scroll-behaviour: smooth;
	}
</style>

</head>
<body style="text-align:center;"> 
<nav>
    <a href="#Home">Home</a>
    <a href="#AboutMe">About Me</a>
    <a href="#Hobbies">Hobbies</a>
    <a href="#Skillset">Skillset</a>
    <a href="#RecentProjects">Recent Projects</a>
</nav>
<div id="main">
<section id="Home">
    <h1>Lauren Davies</h1>
    <h2>Welcome to my portfolio!</h2> 
	<div class="scroll-down">
	 ↓
	</div>
</section>

<section id="AboutMe">
	<hr>
    <h2>About Me</h2>
    <p>My name is Lauren. I am a 23 year old student currently enrolled in my first year of university at the University of South Wales, studying a BSc with honours degree in computer science. </p>
	<hr>
</section>

<section id="Hobbies">
    <h2>Hobbies</h2>
    <p>I have a passion for video games and their development, my favourite games include <em>The Last of Us</em> and <em>Silent Hill</em> series. I began playing video games in early childhood and my love for them has followed me throughout my life, which sparked my interest in technology and code. I enjoy learning languages in my spare time, I am currently in the process of improving my previous Welsh skills and learning how to speak and read Japanese. I also enjoy playing instruments as a hobby, my skills include piano, guitar and ukulele.</p>
	<hr>
</section>

<section id="Skillset">
    <h2>Skillset</h2> 
    <p>I am able to use Python, and at university I am currently learning how to program in C++ and HTML. I am also learning <abbr title="Structured Query Language">SQL</abbr> and cryptography in my studies. Whilst learning cryptography at university, we evaluated different cryptographic methods such as the Caesar and Vigenère cipher and covered their real-world uses. We also covered how to develop entity relationship diagrams as database concept models and how to develop the databases futher in SQL.</p>
	<hr>
</section>

<section id="RecentProjects">
    <h2>Recent Projects in C++</h2>
	<div class="project">
		<h3>Monthly income</h3>
		<p>Program that calculates the total monthly income of an employee by increasing the basic monthly pay by the percentage of bonus and medical allowance pay.</p>
		<a href="https://github.com/ldavies442/Monthly-Income" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Height in meters</h3>
		<p>Program that converts the height inputted by the user from feet and inches into meters.</p>
		<a href="https://github.com/ldavies442/Height-in-Meters" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Annual high temperatures</h3>
		<p>Program that calculates the average temperature of 3 cities if the temperature rose by 15%.</p>
		<a href="https://github.com/ldavies442/Annual-Temperatures" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>How much paint</h3>
		<p>Program that calculates the area of a fence that is 6ft tall and 100ft wide, and tells the user the amount of paint tins needed to paint the fence.</p>
		<a href="https://github.com/ldavies442/How-Much-Paint" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Burger stall</h3>
		<p>Program that calculates the total profit of a burger stall in a day, by asking the user to input the amount of sales of each type of burger.</p>
		<a href="https://github.com/ldavies442/Burger-Stall" style="color:white;" target="_blank"><u>View</u></a>
    </div>
	<div class="project">
		<h3>Project hours</h3>
		<p>Program that uses user input of days spent to calculate the total amount of time two people spend on a project, which is then displayed in hours and minutes.</p>
		<a href="https://github.com/ldavies442/Project-Hours" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>House budget</h3>
		<p>Program that takes in data regarding monthly expenses and uses the data to calculate the annual cost of each expense.</p>
		<a href="https://github.com/ldavies442/Budget" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Coin toss</h3>
		<p>Program that simulates a random coin toss, allowing the user to guess heads or tails to win.</p>
		<a href="https://github.com/ldavies442/Coin-Toss" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Area of triangle</h3>
		<p>Program that requests 3 lengths of the sides of a triangle from the user, checks for validity and calculates the area of the triangle.</p>
		<a href="https://github.com/ldavies442/Triangle" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Rainfall</h3>
		<p>Program that reads information from a file to calculate the total and average rainfall amounts between 2 months.</p>
		<a href="https://github.com/ldavies442/Rainfall" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Distance travelled</h3>
		<p>Program that allows the user to input a vehicles speed in mph and hours travelled to display the distance travelled using a table which breaks down the distance through each hour.</p>
		<a href="https://github.com/ldavies442/Distance" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Weight conversion table</h3>
		<p>Program that displays a table with imperial tons converted into pounds and kilograms in increments of 2, starting with 2 and ending with 20 tons.</p>
		<a href="https://github.com/ldavies442/Weight-Table" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Average speed</h3>
		<p>Program that uses two inputted distances with two corresponding times to calculate the average speed in km/h.</p>
		<a href="https://github.com/ldavies442/Average-Speed" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<div class="project">
		<h3>Student Performance</h3>
		<p>Program that uses a class to recieve and store information about a student and their academic scores, this program then calculated the performance using a formula of 75% academic score and 25% extra curricular score to then find the overall grade of the student. This program used loops to ensure that inputted scores were valid, and stored the students personal information in a private class.</p>
		<a href="https://github.com/ldavies442/Student-Performance" style="color:white;" target="_blank"><u>View</u></a>
	</div>
	<hr>
</section>

<h3>Thank you for reading!</h3>
<br>
</div>
</body>
</html>