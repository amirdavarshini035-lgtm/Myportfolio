# Myportfolio
My personal portfolio website
#index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amirdavarshini D | Portfolio</title>

    <link rel="stylesheet" href="sty.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
</head>

<body>

<!-- ================= NAVBAR ================= -->

<header>

    <div class="logo">
        <h2>Amirdavarshini D</h2>
    </div>

    <nav>

        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>

    </nav>

</header>

<!-- ================= HERO ================= -->

<section class="hero" id="home">

<div class="hero-text">

<h4>Hello, I'm</h4>

<h1>Amirdavarshini <span>D</span></h1>

<h3>Aspiring Software Developer</h3>

<p>

I'm a passionate B.Tech student who enjoys
creating beautiful websites using HTML,
CSS and JavaScript. I love learning
new technologies and solving problems.

</p>

<div class="buttons">

<a href="#">Download CV</a>

<a href="#contact" class="contact-btn">

Hire Me

</a>

</div>

<div class="social">

<a href="#"><i class="fab fa-github"></i></a>

<a href="#"><i class="fab fa-linkedin"></i></a>

<a href="#"><i class="fab fa-instagram"></i></a>

</div>

</div>

<div class="hero-image">

<img src="c:\Users\acer\Downloads\portfolio profile.jpeg" alt="Profile">

</div>

</section>

<!-- ================= ABOUT ================= -->

<section class="about" id="about">

<h2>About Me</h2>

<div class="about-content">

<div class="about-left">

<p>

I am currently pursuing my B.Tech degree.

My interest lies in Front-End Development,
UI Design and Programming.

I enjoy creating responsive websites and
continuously improving my coding skills.

</p>

</div>

<div class="about-right">

<p><strong>Name :</strong> Amirdavarshini D</p>

<p><strong>Age :</strong> 18</p>

<p><strong>Degree :</strong> B.Tech AI DS</p>

<p><strong>Location :</strong> Tamil Nadu</p>

<p><strong>Email :</strong> amirdavarshini035@gmail.com</p>

</div>

</div>

</section>

<!-- ================= SKILLS ================= -->

<section class="skills" id="skills">

<h2>My Skills</h2>

<div class="skill-box">

<div class="card">

<i class="fab fa-html5"></i>

<h3>HTML</h3>

<p>Responsive Web Design</p>

</div>

<div class="card">

<i class="fab fa-css3-alt"></i>

<h3>CSS</h3>

<p>Modern UI Design</p>

</div>

<div class="card">

<i class="fab fa-js"></i>

<h3>JavaScript</h3>

<p>Interactive Websites</p>

</div>

<div class="card">

<i class="fas fa-code"></i>

<h3>C Programming</h3>

<p>Problem Solving</p>

</div>

<div class="card">

<i class="fab fa-python"></i>

<h3>Python</h3>

<p>Basic Programming</p>

</div>

<div class="card">

<i class="fas fa-database"></i>

<h3>SQL</h3>

<p>Database Basics</p>

</div>

</div>

</section>

<!-- ================= PROJECTS ================= -->

<section class="projects" id="projects">

<h2>Projects</h2>

<div class="project-container">

<div class="project-card">

<h3>Portfolio Website</h3>

<p>

Personal portfolio built using
HTML, CSS and JavaScript.

</p>

</div>

<div class="project-card">

<h3>Student Management System</h3>

<p>

Simple student record management
using C Programming.

</p>

</div>

<div class="project-card">

<h3>Calculator</h3>

<p>

Responsive calculator using
HTML, CSS and JavaScript.

</p>

</div>

</div>

</section>

<!-- ================= CONTACT ================= -->

<section class="contact" id="contact">

<h2>Contact Me</h2>

<p>

Let's work together on exciting projects!

</p>

<a href="mailto:akila@email.com">

Send Email

</a>

</section>

<!-- ================= FOOTER ================= -->

<footer>

<p>

© 2026 Amirdavarshini D | All Rights Reserved

</p>

</footer>

<script src="script.js"></script>

</body>
</html>

#style.css
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#08111f;
    color:#ffffff;
}

/* =========================
   NAVBAR
========================= */

header{
    width:100%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    position:fixed;
    top:0;
    left:0;
    background:#08111f;
    z-index:1000;
}

.logo h2{
    color:#8b5cf6;
    font-size:30px;
}

nav a{
    text-decoration:none;
    color:white;
    margin-left:30px;
    font-size:17px;
    transition:0.3s;
}

nav a:hover{
    color:#8b5cf6;
}

/* =========================
   HERO SECTION
========================= */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:120px 8%;
}

.hero-text{
    width:55%;
}

.hero-text h4{
    color:#8b5cf6;
    font-size:25px;
}

.hero-text h1{
    font-size:70px;
    margin:10px 0;
}

.hero-text span{
    color:#8b5cf6;
}

.hero-text h3{
    font-size:30px;
    margin-bottom:20px;
}

.hero-text p{
    color:#d3d3d3;
    line-height:30px;
    margin-bottom:30px;
}

.buttons a{
    display:inline-block;
    text-decoration:none;
    color:white;
    background:#8b5cf6;
    padding:14px 30px;
    border-radius:8px;
    margin-right:15px;
    transition:.3s;
}

.contact-btn{
    background:transparent !important;
    border:2px solid #8b5cf6;
}

.buttons a:hover{
    transform:translateY(-5px);
}

.social{
    margin-top:35px;
}

.social a{
    color:white;
    font-size:28px;
    margin-right:20px;
    transition:.3s;
}

.social a:hover{
    color:#8b5cf6;
}

.hero-image img{
    width:400px;
    height:400px;
    object-fit:cover;
    border-radius:50%;
    border:5px solid #8b5cf6;
    box-shadow:0 0 30px rgba(139,92,246,.5);
}

/* =========================
   ABOUT
========================= */

.about{
    background:white;
    color:#222;
    padding:80px 8%;
}

.about h2{
    text-align:center;
    font-size:40px;
    color:#8b5cf6;
    margin-bottom:50px;
}

.about-content{
    display:flex;
    justify-content:space-between;
    gap:40px;
    flex-wrap:wrap;
}

.about-left,
.about-right{
    flex:1;
    min-width:280px;
}

.about-left p,
.about-right p{
    font-size:18px;
    line-height:35px;
}
/* =========================
   SKILLS
========================= */

.skills{
    background:#f4f4f4;
    padding:80px 8%;
}

.skills h2{
    text-align:center;
    font-size:40px;
    color:#222;
    margin-bottom:50px;
}

.skill-box{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.card{
    background:#ffffff;
    border-radius:15px;
    text-align:center;
    padding:35px 20px;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card i{
    font-size:55px;
    color:#8b5cf6;
    margin-bottom:20px;
}

.card h3{
    color:#222;
    margin-bottom:10px;
}

.card p{
    color:#666;
}

/* =========================
   PROJECTS
========================= */

.projects{
    background:#08111f;
    padding:80px 8%;
}

.projects h2{
    text-align:center;
    font-size:40px;
    margin-bottom:50px;
}

.project-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.project-card{
    background:#111b2d;
    padding:30px;
    border-radius:15px;
    transition:.3s;
    border:1px solid #2d3748;
}

.project-card:hover{
    transform:translateY(-10px);
    border-color:#8b5cf6;
}

.project-card h3{
    color:#8b5cf6;
    margin-bottom:15px;
}

.project-card p{
    color:#d0d0d0;
    line-height:28px;
}

/* =========================
   CONTACT
========================= */

.contact{
    padding:80px 8%;
    text-align:center;
    background:#ffffff;
}

.contact h2{
    color:#222;
    font-size:40px;
    margin-bottom:20px;
}

.contact p{
    color:#666;
    margin-bottom:30px;
    font-size:18px;
}

.contact a{
    display:inline-block;
    text-decoration:none;
    background:#8b5cf6;
    color:white;
    padding:15px 35px;
    border-radius:8px;
    transition:.3s;
}

.contact a:hover{
    background:#6d28d9;
}

/* =========================
   FOOTER
========================= */

footer{
    background:#050b15;
    color:#bbb;
    text-align:center;
    padding:20px;
}

/* =========================
   RESPONSIVE DESIGN
========================= */

@media(max-width:900px){

header{
    flex-direction:column;
    padding:20px;
}

nav{
    margin-top:15px;
}

nav a{
    margin:10px;
    display:inline-block;
}

.hero{
    flex-direction:column-reverse;
    text-align:center;
    padding-top:150px;
}

.hero-text{
    width:100%;
}

.hero-image img{
    width:280px;
    height:280px;
    margin-bottom:40px;
}

.hero-text h1{
    font-size:50px;
}

.hero-text h3{
    font-size:24px;
}

.about-content{
    flex-direction:column;
}

}
