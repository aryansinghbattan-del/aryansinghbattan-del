<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aryan Singh | GitHub Dashboard</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

</head>

<body>

<div class="container">

<header>

<img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" class="profile">

<h1>Aryan Singh</h1>

<h3>Cloud Computing Engineer | DevOps Enthusiast | Full Stack Developer</h3>

<p>
Passionate Cloud Computing Professional with expertise in Linux,
Networking, DevOps, Programming, Web Development and Cloud Infrastructure.
Focused on building scalable, secure and high-performance applications.
</p>

</header>

<section class="cards">

<div class="card">
<i class="fa-solid fa-code"></i>
<h2>Programming Languages</h2>

<ul>

<li>Python</li>
<li>Java</li>
<li>C</li>
<li>C++</li>
<li>JavaScript</li>
<li>TypeScript</li>
<li>PHP</li>
<li>Go</li>
<li>Rust</li>
<li>Kotlin</li>
<li>Swift</li>
<li>SQL</li>
<li>HTML5</li>
<li>CSS3</li>
<li>Bash</li>

</ul>

</div>

<div class="card">

<i class="fa-solid fa-cloud"></i>

<h2>Cloud Computing</h2>

<ul>

<li>AWS</li>
<li>Microsoft Azure</li>
<li>Google Cloud Platform</li>
<li>Cloud Security</li>
<li>Virtualization</li>
<li>Linux Administration</li>
<li>Load Balancing</li>
<li>Auto Scaling</li>
<li>Cloud Storage</li>
<li>Monitoring</li>

</ul>

</div>

<div class="card">

<i class="fa-solid fa-server"></i>

<h2>DevOps Tools</h2>

<ul>

<li>Docker</li>
<li>Kubernetes</li>
<li>Jenkins</li>
<li>Git</li>
<li>GitHub</li>
<li>GitHub Actions</li>
<li>Ansible</li>
<li>Terraform</li>
<li>Nginx</li>
<li>Apache</li>

</ul>

</div>

<div class="card">

<i class="fa-solid fa-network-wired"></i>

<h2>Networking</h2>

<ul>

<li>TCP/IP</li>
<li>DNS</li>
<li>HTTP / HTTPS</li>
<li>SSH</li>
<li>FTP</li>
<li>VPN</li>
<li>Firewalls</li>
<li>Subnetting</li>
<li>Routing</li>

</ul>

</div>

</section>

<section class="skills">

<h2>Professional Skills</h2>

<div class="skill">

<span>Cloud Computing</span>

<div class="bar">
<div class="fill ninety"></div>
</div>

</div>

<div class="skill">

<span>Linux</span>

<div class="bar">
<div class="fill ninetyfive"></div>
</div>

</div>

<div class="skill">

<span>Programming</span>

<div class="bar">
<div class="fill eightyfive"></div>
</div>

</div>

<div class="skill">

<span>DevOps</span>

<div class="bar">
<div class="fill eighty"></div>
</div>

</div>

<div class="skill">

<span>Networking</span>

<div class="bar">
<div class="fill ninety"></div>
</div>

</div>

</section>

<section class="achievement">

<h2>Career Objective</h2>

<p>

Dedicated Cloud Computing and DevOps professional passionate about designing,
deploying, and managing scalable cloud infrastructures. Skilled in Linux,
Automation, CI/CD, Docker, Kubernetes, Networking, and Web Technologies.
Continuously learning emerging technologies to deliver secure and efficient
solutions.

</p>

</section>

<footer>

<h3>Made with ❤️ by Aryan Singh</h3>

<p>GitHub Portfolio Dashboard</p>

</footer>

</div>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{

background:linear-gradient(135deg,#050816,#0f172a,#1e293b);
color:white;
padding:40px;
}

.container{

max-width:1300px;
margin:auto;
}

header{

text-align:center;
padding:40px;
background:rgba(255,255,255,.08);
backdrop-filter:blur(15px);
border-radius:20px;
box-shadow:0 0 40px cyan;

animation:fade 1s;

}

.profile{

width:170px;
height:170px;
border-radius:50%;
border:5px solid cyan;
margin-bottom:20px;
transition:.5s;
}

.profile:hover{

transform:scale(1.08) rotate(5deg);

box-shadow:0 0 30px cyan;

}

header h1{

font-size:55px;

color:#00ffff;

}

header h3{

margin:15px;

color:#7dd3fc;

}

header p{

max-width:900px;

margin:auto;

line-height:30px;

font-size:18px;

}

.cards{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(270px,1fr));

gap:30px;

margin-top:50px;

}

.card{

background:rgba(255,255,255,.08);

padding:30px;

border-radius:20px;

transition:.4s;

backdrop-filter:blur(12px);

}

.card:hover{

transform:translateY(-15px);

box-shadow:0 0 35px cyan;

}

.card i{

font-size:45px;

color:#00ffff;

margin-bottom:20px;

}

.card h2{

margin-bottom:20px;

}

.card ul{

list-style:none;

}

.card ul li{

padding:8px;

border-bottom:1px solid rgba(255,255,255,.15);

}

.skills{

margin-top:60px;

background:rgba(255,255,255,.08);

padding:30px;

border-radius:20px;

}

.skills h2{

margin-bottom:30px;

}

.skill{

margin-bottom:25px;

}

.bar{

width:100%;

height:18px;

background:#222;

border-radius:30px;

overflow:hidden;

margin-top:8px;

}

.fill{

height:100%;

background:linear-gradient(90deg,#00ffff,#00ff99);

}

.ninety{

width:90%;

}

.ninetyfive{

width:95%;

}

.eightyfive{

width:85%;

}

.eighty{

width:80%;

}

.achievement{

margin-top:50px;

padding:30px;

background:rgba(255,255,255,.08);

border-radius:20px;

text-align:center;

line-height:35px;

}

footer{

text-align:center;

margin-top:50px;

padding:30px;

font-size:18px;

}

@keyframes fade{

from{

opacity:0;

transform:translateY(-30px);

}

to{

opacity:1;

transform:translateY(0);

}

}

@media(max-width:768px){

header h1{

font-size:38px;

}

}

