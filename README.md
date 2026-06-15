<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Student Portfolio - Aarav Sharma</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f4f7ff;
    color:#333;
    scroll-behavior:smooth;
}

header{
    background:linear-gradient(135deg,#6a11cb,#2575fc);
    padding:20px 8%;
    position:sticky;
    top:0;
    z-index:999;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:#fff;
    font-size:28px;
    font-weight:700;
}

nav ul{
    display:flex;
    list-style:none;
    gap:20px;
}

nav ul li a{
    text-decoration:none;
    color:#fff;
    font-weight:500;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ffd700;
}

.hero{
    background:linear-gradient(135deg,#6a11cb,#2575fc);
    color:white;
    padding:80px 8%;
    display:flex;
    align-items:center;
    justify-content:space-between;
    flex-wrap:wrap;
}

.hero-text{
    max-width:600px;
}

.hero-text h1{
    font-size:50px;
}

.hero-text p{
    margin:20px 0;
    line-height:1.8;
}

.hero img{
    width:280px;
    border-radius:50%;
    border:8px solid white;
    box-shadow:0 0 30px rgba(0,0,0,0.2);
}

.btn{
    display:inline-block;
    background:#ffd700;
    color:#000;
    padding:12px 30px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
}

section{
    padding:70px 8%;
}

.section-title{
    text-align:center;
    font-size:35px;
    margin-bottom:40px;
    color:#2575fc;
}

.about-box{
    background:white;
    border-radius:20px;
    padding:30px;
    box-shadow:0 10px 25px rgba(0,0,0,0.1);
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:40px;
}

.stat-card{
    background:linear-gradient(135deg,#ff9966,#ff5e62);
    color:white;
    padding:30px;
    border-radius:20px;
    text-align:center;
    transition:0.3s;
}

.stat-card:hover{
    transform:translateY(-10px);
}

table{
    width:100%;
    border-collapse:collapse;
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

table th{
    background:#2575fc;
    color:white;
    padding:15px;
}

table td{
    padding:15px;
    text-align:center;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:20px;
    box-shadow:0 10px 20px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:#2575fc;
    margin-bottom:10px;
}

.skill{
    margin-bottom:20px;
}

.progress{
    background:#ddd;
    border-radius:20px;
    overflow:hidden;
}

.progress div{
    height:15px;
    background:linear-gradient(90deg,#6a11cb,#2575fc);
}

@media(max-width:768px){
.hero{
    text-align:center;
    justify-content:center;
}
.hero img{
    margin-top:30px;
}
.hero-text h1{
    font-size:35px;
}
nav ul{
    flex-wrap:wrap;
    justify-content:center;
}
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">Neeraj  Portfolio</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#academics">Academics</a></li>
<li><a href="#clubs">Clubs</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero">
<div class="hero-text">
<h1>Hello, I'm Neeraj Saini</h1>
<h3>Grade 8 | Sector 26 Panchkula engg college</h3>

<p>
Passionate Front End Developer with knowledge of
 HTML, CSS, and JavaScript. Skilled in creating responsive, 
 user-friendly, and attractive websites with a focus
 on good design and performance.”
</p>

<a href="#about" class="btn">Explore More</a>
</div>

<img src="https://via.placeholder.com/280" alt="Student Photo">
</section>

<section id="about">
<h2 class="section-title">About Me</h2>

<div class="about-box">
<p><strong>Full Name:</strong> Neeraj Saini</p>
<p><strong>Date of Birth:</strong> 15 August 2004</p>
<p><strong>Grade:</strong> 8</p>
<p><strong>School:</strong>  Sector 26 Panchkula engg college</p>
<p><strong>City/Country:</strong> Panchkula Haryana</p>
<p><strong>Career Goal:</strong> Front End Developer </p>

<br>


</div>

<div class="stats">
<div class="stat-card">
<h2>92%</h2>
<p>Academic Score</p>
</div>

<div class="stat-card">
<h2>5</h2>
<p>Club Participation</p>
</div>

<div class="stat-card">
<h2>10+</h2>
<p>Certificates</p>
</div>

<div class="stat-card">
<h2>3</h2>
<p>Competition Medals</p>
</div>
</div>
</section>

<section id="academics">
<h2 class="section-title">Academic Performance</h2>

<table>
<tr>
<th>Subject</th>
<th>Grade</th>
</tr>

<tr>
<td>Mathematics</td>
<td>A+</td>
</tr>

<tr>
<td>Science</td>
<td>A</td>
</tr>

<tr>
<td>English</td>
<td>A</td>
</tr>

<tr>
<td>Computer Science</td>
<td>A+</td>
</tr>

<tr>
<td>Social Studies</td>
<td>B+</td>
</tr>
</table>

<br><br>

<h3 style="text-align:center;">Overall Percentage: 92%</h3>
</section>

<section id="clubs">
<h2 class="section-title">GEMMA Club Participation</h2>

<div class="cards">

<div class="card">
<h3>Abacus Club</h3>
<p>2 years participation</p>
<p>State-level finalist</p>
</div>

<div class="card">
<h3>Coding Club</h3>
<p>Built Scratch projects</p>
<p>Participated in coding challenges</p>
</div>

<div class="card">
<h3>Public Speaking Club</h3>
<p>Participated in speech events</p>
<p>Improved communication skills</p>
</div>

<div class="card">
<h3>Science Club</h3>
<p>Innovation Projects</p>
<p>Science experiments</p>
</div>

</div>
</section>

<section id="skills">
<h2 class="section-title">Skills</h2>

<div class="skill">
<p>Problem Solving</p>
<div class="progress">
<div style="width:90%;"></div>
</div>
</div>

<div class="skill">
<p>HTML Basics</p>
<div class="progress">
<div style="width:80%;"></div>
</div>
</div>

<div class="skill">
<p>Public Speaking</p>
<div class="progress">
<div style="width:85%;"></div>
</div>
</div>

<div class="skill">
<p>Leadership</p>
<div class="progress">
<div style="width:88%;"></div>
</div>
</div>
</section>
<section id="projects">
<h2 class="section-title">Project Showcase</h2>

<div class="cards">

<div class="card">
<h3>Smart Irrigation System</h3>
<p><strong>Type:</strong> Science Project</p>
<p>Uses soil moisture sensors</p>
<p>Helps save water efficiently</p>
<p>Won School Innovation Award</p>
</div>

<div class="card">
<h3>Scratch Game: Temple Adventure</h3>
<p><strong>Type:</strong> Coding Project</p>
<p>Designed using Scratch</p>
<p>Includes scoring system</p>
<p>Multiple game levels</p>
</div>

<div class="card">
<h3>Climate Change Website</h3>
<p><strong>Type:</strong> Web Project</p>
<p>Built using HTML & CSS</p>
<p>Educational awareness project</p>
<p>Interactive content included</p>
</div>

</div>
</section>

<section id="achievements">
<h2 class="section-title">Achievements</h2>

<div class="cards">

<div class="card">
<h3>🥇 Gold Medal</h3>
<p>International Abacus Olympiad</p>
</div>

<div class="card">
<h3>🥈 Silver Medal</h3>
<p>Essay Writing Competition</p>
</div>

<div class="card">
<h3>🏅 Top 20 Finalist</h3>
<p>Young Scientist Award</p>
</div>

<div class="card">
<h3>🥉 Bronze Medal</h3>
<p>Student Speaker Competition</p>
</div>

</div>
</section>

<section id="certificates">
<h2 class="section-title">Certificates Gallery</h2>

<div class="cards">

<div class="card">
<h3>🏆 Abacus Olympiad</h3>
<p>Gold Medal Certificate</p>
</div>

<div class="card">
<h3>📜 Coding Competition</h3>
<p>Participation Certificate</p>
</div>

<div class="card">
<h3>🎤 Public Speaking</h3>
<p>Achievement Certificate</p>
</div>

<div class="card">
<h3>🔬 Science Fair</h3>
<p>Innovation Award</p>
</div>

</div>
</section>

<section id="blog">
<h2 class="section-title">Student Blog</h2>

<div class="cards">

<div class="card">
<h3>How Abacus Improved My Mental Math Skills</h3>
<p>
Abacus training improved my concentration and
helped me solve mathematics questions faster.
</p>
</div>

<div class="card">
<h3>My Experience at Student Speaker Competition</h3>
<p>
Participating in speech competitions improved
my confidence and communication skills.
</p>
</div>

<div class="card">
<h3>Why Coding is Important</h3>
<p>
Coding develops logical thinking and helps
students prepare for future careers in technology.
</p>
</div>

</div>
</section>

<section id="testimonials">
<h2 class="section-title">Testimonials</h2>

<div class="cards">

<div class="card">
<h3>Teacher Feedback</h3>
<p>
"Neeraj consistently demonstrates curiosity,
discipline and leadership in every activity."
</p>
</div>

<div class="card">
<h3>Parent Feedback</h3>
<p>
"GEMMA Clubs improved Neeraj’s confidence,
problem-solving and creativity."
</p>
</div>

</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Me</h2>

<div class="about-box">

<form>
<label>Name</label><br>
<input type="text" placeholder="Enter Name"
style="width:100%;padding:12px;margin:10px 0;border-radius:10px;border:1px solid #ccc;">

<label>Email</label><br>
<input type="email" placeholder="Enter Email"
style="width:100%;padding:12px;margin:10px 0;border-radius:10px;border:1px solid #ccc;">

<label>Message</label><br>
<textarea rows="5" placeholder="Write Message"
style="width:100%;padding:12px;margin:10px 0;border-radius:10px;border:1px solid #ccc;"></textarea>

<button class="btn" type="submit">
Send Message
</button>

</form>

<br>

<p><strong>Email:</strong> neerajsaini@example.com</p>
<p><strong>Phone:</strong> +91 9876543210</p>

</div>
</section>

<footer style="
background:linear-gradient(135deg,#6a11cb,#2575fc);
padding:30px;
text-align:center;
color:white;
margin-top:50px;
">
<h3> Neeraj Saini Portfolio</h3>
<p>© 2026 All Rights Reserved</p>
</footer>

</body>
</html>