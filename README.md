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
