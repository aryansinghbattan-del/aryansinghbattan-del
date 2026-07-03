<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aryan Singh | GitHub Dashboard</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{

background:linear-gradient(135deg,#050816,#0d1117,#111827);
color:white;

}

/* Scroll Bar */

::-webkit-scrollbar{
width:10px;
}

::-webkit-scrollbar-thumb{
background:#00f5d4;
border-radius:20px;
}

/* Header */

header{

height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
flex-direction:column;

background:
linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.7)),
url("https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1500&q=80");

background-size:cover;
background-position:center;

}

header h1{

font-size:70px;
letter-spacing:2px;
color:#00f5d4;
text-shadow:0 0 20px cyan;

animation:fade 2s;

}

header h2{

font-size:30px;
margin-top:15px;
font-weight:300;

}

header p{

margin-top:25px;
max-width:800px;
line-height:1.8;
font-size:18px;

}

.btn{

margin-top:35px;
padding:15px 35px;
border:none;
border-radius:40px;
background:#00f5d4;
font-size:18px;
font-weight:bold;
cursor:pointer;
transition:.4s;

}

.btn:hover{

transform:scale(1.08);
box-shadow:0 0 30px cyan;

}

/* Section */

section{

padding:80px 8%;

}

.title{

font-size:40px;
color:#00f5d4;
margin-bottom:50px;
text-align:center;

}

/* Cards */

.grid{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;

}

.card{

background:#161b22;
padding:30px;
border-radius:20px;
transition:.5s;
border:1px solid rgba(255,255,255,.08);

}

.card:hover{

transform:translateY(-10px);
box-shadow:0 0 25px cyan;

}

.card h3{

margin-bottom:15px;
color:#00f5d4;

}

.card ul{

padding-left:20px;

}

.card li{

margin:10px 0;

}

/* Skills */

.skills{

display:flex;
flex-wrap:wrap;
justify-content:center;
gap:15px;

}

.skill{

padding:12px 25px;
background:#1f2937;
border-radius:30px;
transition:.4s;
font-weight:bold;

}

.skill:hover{

background:#00f5d4;
color:black;
transform:scale(1.1);

}

/* Stats */

.stats{

display:flex;
justify-content:center;
flex-wrap:wrap;
gap:30px;

}

.stats img{

width:450px;
max-width:100%;
border-radius:15px;
transition:.4s;

}

.stats img:hover{

transform:scale(1.05);

}

/* Footer */

footer{

text-align:center;
padding:30px;
background:#0d1117;
margin-top:50px;

}

footer a{

color:#00f5d4;
text-decoration:none;

}

/* Animation */

@keyframes fade{

from{
opacity:0;
transform:translateY(50px);
}

to{
opacity:1;
transform:translateY(0px);
}

}

</style>

</head>

<body>

<header>

<h1>Aryan Singh</h1>

<h2>Cloud Engineer | DevOps Enthusiast | Full Stack Developer</h2>

<p>

Passionate technology enthusiast with strong expertise in Cloud Computing,
Linux Administration, DevOps, Networking, Web Development,
Git & GitHub, Containerization, and Programming Languages.
Always learning modern technologies and building scalable solutions.

</p>

<button class="btn">Welcome to My GitHub Dashboard</button>

</header>

<!-- ABOUT -->

<section>

<h1 class="title">About Me</h1>

<div class="grid">

<div class="card">

<h3>Professional Summary</h3>

<p>

I am Aryan Singh, an aspiring Cloud & DevOps Engineer with a strong
foundation in Linux, Networking, Cloud Computing, Git, GitHub,
Docker, Kubernetes, Nginx, Apache, CI/CD, and Infrastructure Automation.

I enjoy solving real-world problems using modern technologies and continuously
improving my technical skills.

</p>

</div>

<div class="card">

<h3>Career Goal</h3>

<p>

To become an Expert Cloud Solutions Architect and DevOps Engineer by mastering
AWS, Azure, Google Cloud Platform, Kubernetes, Terraform,
Ansible, Jenkins, Linux Administration and modern software development.

</p>

</div>

</div>

</section>

<!-- Programming -->

<section>

<h1 class="title">Programming Languages</h1>

<div class="skills">

<div class="skill">C</div>
<div class="skill">C++</div>
<div class="skill">Python</div>
<div class="skill">Java</div>
<div class="skill">JavaScript</div>
<div class="skill">TypeScript</div>
<div class="skill">HTML5</div>
<div class="skill">CSS3</div>
<div class="skill">PHP</div>
<div class="skill">SQL</div>
<div class="skill">Bash</div>
<div class="skill">PowerShell</div>
<div class="skill">Go</div>
<div class="skill">Rust</div>

</div>

</section>

<!-- Cloud -->

<section>

<h1 class="title">Cloud & DevOps Expertise</h1>

<div class="grid">

<div class="card">

<h3>Cloud Platforms</h3>

<ul>

<li>AWS</li>
<li>Microsoft Azure</li>
<li>Google Cloud Platform</li>
<li>Oracle Cloud</li>
<li>DigitalOcean</li>

</ul>

</div>

<div class="card">

<h3>DevOps Tools</h3>

<ul>

<li>Docker</li>
<li>Kubernetes</li>
<li>Jenkins</li>
<li>Terraform</li>
<li>Ansible</li>
<li>GitHub Actions</li>

</ul>

</div>

<div class="card">

<h3>Linux & Web Servers</h3>

<ul>

<li>Ubuntu</li>
<li>CentOS</li>
<li>RedHat</li>
<li>Nginx</li>
<li>Apache</li>
<li>SSH</li>

</ul>

</div>

<div class="card">

<h3>Networking</h3>

<ul>

<li>DNS</li>
<li>TCP/IP</li>
<li>HTTP/HTTPS</li>
<li>Load Balancer</li>
<li>Reverse Proxy</li>
<li>Firewall</li>

</ul>

</div>

</div>

</section>

<!-- GitHub -->

<section>

<h1 class="title">GitHub Statistics</h1>

<div class="stats">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=tokyonight">

</div>

</section>

<!-- Contact -->

<section>

<h1 class="title">Contact</h1>

<div class="grid">

<div class="card">

<h3>Email</h3>

<p>aryan@example.com</p>

</div>

<div class="card">

<h3>GitHub</h3>

<p>github.com/yourusername</p>

</div>

<div class="card">

<h3>LinkedIn</h3>

<p>linkedin.com/in/aryansingh</p>

</div>

</div>

</section>

<footer>

<h2>Designed & Developed by Aryan Singh</h2>

<p>

Cloud Engineer • DevOps • Linux • Programming • GitHub

</p>

</footer>

</body>
</html>
