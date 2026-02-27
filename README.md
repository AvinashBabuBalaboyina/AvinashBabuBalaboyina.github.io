<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Avinash Babu | UI Developer</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

/* ===== Animated Background ===== */
body{
margin:0;
font-family:'Segoe UI',sans-serif;
color:white;
background: linear-gradient(-45deg,#0f2027,#203a43,#2c5364,#1c1c1c);
background-size:400% 400%;
animation:gradientBG 12s ease infinite;
overflow-x:hidden;
}

@keyframes gradientBG{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

/* ===== Navbar ===== */
.navbar{
background:rgba(0,0,0,0.6);
backdrop-filter:blur(12px);
box-shadow:0 5px 25px rgba(0,0,0,0.7);
}

/* ===== Hero ===== */
.hero{
padding:120px 20px 60px;
text-align:center;
animation:fadeIn 1.5s ease;
}

.hero h1{
font-size:42px;
font-weight:bold;
background:linear-gradient(90deg,#00f5ff,#00ff99);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.hero h4{
color:#00f5ff;
margin-bottom:20px;
}

.contact a{
color:#00f5ff;
text-decoration:none;
transition:0.4s;
}

.contact a:hover{
color:white;
text-shadow:0 0 10px #00f5ff;
}

/* ===== Cards ===== */
.section{
padding:50px 0;
}

.resume-card{
background:rgba(255,255,255,0.08);
border-radius:20px;
padding:25px;
border:1px solid rgba(255,255,255,0.2);
backdrop-filter:blur(12px);
transition:0.5s;
cursor:pointer;
}

.resume-card:hover{
transform:translateY(-15px) scale(1.05);
box-shadow:0 25px 50px rgba(0,255,255,0.6);
background:rgba(0,255,255,0.15);
}

.card-content{
display:none;
margin-top:15px;
font-size:14px;
line-height:1.6;
}

.resume-card.active .card-content{
display:block;
animation:slideDown 0.6s ease;
}

@keyframes slideDown{
from{opacity:0;transform:translateY(-20px);}
to{opacity:1;transform:translateY(0);}
}

@keyframes fadeIn{
from{opacity:0;transform:translateY(-40px);}
to{opacity:1;transform:translateY(0);}
}

/* ===== Download Button ===== */
.download-btn{
background:#00f5ff;
color:black;
font-weight:bold;
border:none;
padding:10px 30px;
border-radius:30px;
transition:0.4s;
}

.download-btn:hover{
background:white;
box-shadow:0 0 20px #00f5ff;
transform:scale(1.1);
}

/* ===== Popup ===== */
.popup{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.85);
display:flex;
justify-content:center;
align-items:center;
opacity:0;
visibility:hidden;
transition:0.5s;
}

.popup.active{
opacity:1;
visibility:visible;
}

.popup-content{
background:linear-gradient(135deg,#203a43,#2c5364);
padding:40px;
border-radius:20px;
text-align:center;
box-shadow:0 0 40px #00f5ff;
animation:popScale 0.5s ease;
}

@keyframes popScale{
from{transform:scale(0.5);opacity:0;}
to{transform:scale(1);opacity:1;}
}

.popup-content button{
margin-top:20px;
padding:8px 25px;
border:none;
background:#00f5ff;
border-radius:25px;
font-weight:bold;
}

@media(max-width:768px){
.hero h1{font-size:28px;}
}

</style>
</head>

<body>

<nav class="navbar fixed-top">
<div class="container">
<span class="navbar-brand text-white fw-bold">AVINASH BABU .B</span>
</div>
</nav>

<section class="hero container">
<h1>AVINASH BABU .B</h1>
<h4>UI WEB DEVELOPER / SOFTWARE ENGINEER UI - LEVEL I / PROJECT MANAGER UI</h4>

<div class="contact">
📧 <a href="mailto:Prince.avi10@gmail.com">Prince.avi10@gmail.com</a> |
<a href="mailto:avibabu510@gmail.com">avibabu510@gmail.com</a><br>
📞 7032122805 | Telangana <br>
🔗 <a href="https://www.linkedin.com/in/avinash-balaboyina-337b2a32b" target="_blank">
LinkedIn Profile
</a>
</div>
</section>

<section class="container section">
<div class="row g-4">

<div class="col-md-6">
<div class="resume-card">
<h4>Objective</h4>
<div class="card-content">
Innovative and detail-oriented Web Developer with strong foundation in HTML, CSS, JavaScript and modern frameworks. Passionate about building responsive, user-focused applications.
</div>
</div>
</div>

<div class="col-md-6">
<div class="resume-card">
<h4>Skills & Abilities</h4>
<div class="card-content">
React.js, Bootstrap, JavaScript, HTML5, CSS3, Angular. Experience developing modern responsive web applications.
</div>
</div>
</div>

<div class="col-md-6">
<div class="resume-card">
<h4>Software Engineer UI -1</h4>
<div class="card-content">
SOFTPATH SYSTEM LLC (Jan 2022 – Dec 2022). Developed Angular components, improved performance, GitHub workflow handling.
</div>
</div>
</div>

<div class="col-md-6">
<div class="resume-card">
<h4>Asst. Professor (Engineering College)</h4>
<div class="card-content">
Jan 2023 – July 2024. Handled CSE, ECE, EEE subjects and lab responsibilities.
</div>
</div>
</div>

<div class="col-md-6">
<div class="resume-card">
<h4>Asst. Professor – MRU</h4>
<div class="card-content">
July 2024 – 2026. Teaching MERN/MEAN Stack, React projects and examination duties.
</div>
</div>
</div>

<div class="col-md-6">
<div class="resume-card">
<h4>Education</h4>
<div class="card-content">
MSCS – Northwestern Polytechnic University (USA)<br>
B.Tech – JNTU Telangana (India)
</div>
</div>
</div>

</div>
</section>

<div class="text-center pb-5">
<button class="download-btn" onclick="downloadResume()">📄 Download Resume</button>
</div>

<!-- Popup -->
<div id="popup" class="popup">
<div class="popup-content">
<h4>🎉 Resume Download Completed!</h4>
<p>Thank you for downloading the resume.</p>
<button onclick="closePopup()">Close</button>
</div>
</div>

<script>

/* Card Toggle */
document.querySelectorAll(".resume-card").forEach(card=>{
card.addEventListener("click",()=>{
card.classList.toggle("active");
});
});

/* Download Resume */
function downloadResume(){
const link=document.createElement('a');
link.href="Avinash_Babu_Resume.docx";  // Place file in same folder
link.download="Avinash_Babu_Resume.docx";
link.click();

document.getElementById("popup").classList.add("active");
}

/* Close Popup */
function closePopup(){
document.getElementById("popup").classList.remove("active");
}

</script>

</body>
</html>
