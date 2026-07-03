<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Aryan Singh | Cloud Engineer</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">

</head>

<body>

<div class="bg-animation">
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
</div>

<header>

<div class="profile">

<img src="https://avatars.githubusercontent.com/u/9919?s=280&v=4">

<h1>Aryan Singh</h1>

<h3>Cloud Engineer | DevOps Enthusiast | Full Stack Developer</h3>

<p>
Passionate Cloud Computing learner with expertise in Linux Administration,
Networking, Web Development, DevOps and Programming. Dedicated to building
high-performance cloud applications and scalable infrastructures.
</p>

<a href="#skills" class="btn">Explore Skills</a>

</div>

</header>

<section id="about">

<h2>About Me</h2>

<div class="card">

<p>

I'm Aryan Singh, an aspiring Cloud Engineer and Software Developer with
strong knowledge of Cloud Computing, Linux, Networking, DevOps and Modern
Programming Languages.

I enjoy building websites, deploying applications on cloud platforms,
automating infrastructure and solving real-world problems through technology.

Currently mastering Cloud Technologies, Docker, Kubernetes,
AWS, Azure, Linux Administration, Git and DevOps.

</p>

</div>

</section>

<section id="skills">

<h2>Programming Languages</h2>

<div class="grid">

<div class="box">C</div>

<div class="box">C++</div>

<div class="box">Java</div>

<div class="box">Python</div>

<div class="box">JavaScript</div>

<div class="box">TypeScript</div>

<div class="box">PHP</div>

<div class="box">Go</div>

<div class="box">Rust</div>

<div class="box">SQL</div>

<div class="box">Bash</div>

<div class="box">HTML5</div>

<div class="box">CSS3</div>

</div>

</section>

<section>

<h2>Cloud Computing</h2>

<div class="grid">

<div class="box">AWS</div>

<div class="box">Microsoft Azure</div>

<div class="box">Google Cloud</div>

<div class="box">Cloud Security</div>

<div class="box">Virtualization</div>

<div class="box">Cloud Storage</div>

<div class="box">Cloud Migration</div>

<div class="box">Load Balancing</div>

<div class="box">Auto Scaling</div>

<div class="box">Cloud Monitoring</div>

</div>

</section>

<section>

<h2>DevOps</h2>

<div class="grid">

<div class="box">Git</div>

<div class="box">GitHub</div>

<div class="box">Docker</div>

<div class="box">Kubernetes</div>

<div class="box">Jenkins</div>

<div class="box">Terraform</div>

<div class="box">Ansible</div>

<div class="box">CI/CD</div>

<div class="box">Maven</div>

<div class="box">Gradle</div>

<div class="box">NPM</div>

<div class="box">PIP</div>

</div>

</section>

<section>

<h2>Linux & Networking</h2>

<div class="grid">

<div class="box">Linux</div>

<div class="box">Ubuntu</div>

<div class="box">RedHat</div>

<div class="box">CentOS</div>

<div class="box">SSH</div>

<div class="box">Apache</div>

<div class="box">Nginx</div>

<div class="box">DNS</div>

<div class="box">TCP/IP</div>

<div class="box">HTTP</div>

<div class="box">HTTPS</div>

<div class="box">Reverse Proxy</div>

<div class="box">Load Balancer</div>

<div class="box">Firewall</div>

</div>

</section>

<section>

<h2>Database</h2>

<div class="grid">

<div class="box">MySQL</div>

<div class="box">PostgreSQL</div>

<div class="box">MongoDB</div>

<div class="box">Oracle SQL</div>

</div>

</section>

<section>

<h2>GitHub Goals</h2>

<div class="card">

<ul>

<li>✔ Master Cloud Computing</li>

<li>✔ Become DevOps Engineer</li>

<li>✔ Learn Kubernetes</li>

<li>✔ Build Full Stack Projects</li>

<li>✔ Master Linux Administration</li>

<li>✔ Open Source Contributor</li>

<li>✔ AWS Solutions Architect</li>

<li>✔ Azure Administrator</li>

<li>✔ Google Cloud Engineer</li>

</ul>

</div>

</section>

<footer>

<h3>Designed by Aryan Singh</h3>

<p>Cloud Engineer • DevOps • Programmer</p>

</footer>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
scroll-behavior:smooth;
}

body{

background:#050816;
color:white;

}

.bg-animation span{

position:fixed;
width:20px;
height:20px;
background:#00f7ff;
border-radius:50%;
animation:move 20s linear infinite;
opacity:.2;

}

.bg-animation span:nth-child(1){
left:10%;
animation-duration:12s;
}

.bg-animation span:nth-child(2){
left:30%;
animation-duration:15s;
}

.bg-animation span:nth-child(3){
left:55%;
animation-duration:18s;
}

.bg-animation span:nth-child(4){
left:75%;
animation-duration:13s;
}

.bg-animation span:nth-child(5){
left:90%;
animation-duration:20s;
}

@keyframes move{

0%{
transform:translateY(100vh) scale(.5);
}

100%{
transform:translateY(-100vh) scale(2);
}

}

header{

height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;

}

.profile{

width:900px;

padding:50px;

background:rgba(255,255,255,.05);

backdrop-filter:blur(20px);

border-radius:20px;

box-shadow:0 0 40px cyan;

animation:fade 2s;

}

@keyframes fade{

from{

opacity:0;
transform:translateY(80px);

}

to{

opacity:1;

transform:translateY(0);

}

}

.profile img{

width:170px;

border-radius:50%;

border:5px solid cyan;

margin-bottom:20px;

transition:.5s;

}

.profile img:hover{

transform:rotate(360deg) scale(1.1);

}

h1{

font-size:55px;

color:#00f7ff;

margin-bottom:10px;

}

h2{

text-align:center;

margin:70px;

font-size:40px;

color:#00f7ff;

}

h3{

margin:20px;

}

p{

font-size:18px;

line-height:30px;

}

.btn{

display:inline-block;

margin-top:30px;

padding:15px 40px;

background:cyan;

color:black;

font-weight:bold;

border-radius:30px;

text-decoration:none;

transition:.4s;

}

.btn:hover{

transform:scale(1.1);

box-shadow:0 0 30px cyan;

}

.card{

width:85%;

margin:auto;

padding:40px;

background:rgba(255,255,255,.05);

backdrop-filter:blur(20px);

border-radius:20px;

transition:.5s;

}

.card:hover{

transform:translateY(-10px);

box-shadow:0 0 30px cyan;

}

.grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(180px,1fr));

gap:25px;

width:90%;

margin:auto;

}

.box{

padding:30px;

background:#111827;

border-radius:15px;

text-align:center;

font-size:20px;

transition:.4s;

cursor:pointer;

border:1px solid rgba(255,255,255,.1);

}

.box:hover{

background:cyan;

color:black;

transform:translateY(-10px) scale(1.05);

box-shadow:0 0 30px cyan;

}

ul{

line-height:45px;

font-size:20px;

}

footer{

margin-top:100px;

padding:40px;

text-align:center;

background:#0a0f25;

}
