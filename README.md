<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sudheer Babu | Electrical Engineer</title>

<meta name="description" content="Sudheer Babu – Electrical Engineering Graduate specializing in Embedded Systems, IoT and Power Electronics.">
<meta name="author" content="Sudheer Babu">
<meta name="keywords" content="Electrical Engineering, Embedded Systems, IoT, Arduino, ESP32, Power Electronics">

<link rel="icon" href="favicon.png">

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Poppins:wght@600;800&display=swap" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<!-- EmailJS -->
<script src="https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js"></script>

<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'G-XXXXXXX');
</script>

<style>
:root{
--bg1:#121826;
--bg2:#1a2233;
--accent:#00f5c3;
--accent2:#00bfa5;
--text:#e5e7eb;
--muted:#9ca3af;
--fontH:'Poppins',sans-serif;
--fontB:'Inter',sans-serif;
}

body.light{
--bg1:#f9fafb;
--bg2:#ffffff;
--text:#111827;
--muted:#4b5563;
}

*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
font-family:var(--fontB);
background:var(--bg1);
color:var(--text);
line-height:1.7;
}

header{
position:fixed;
top:0;width:100%;
background:rgba(26,34,51,.9);
backdrop-filter:blur(10px);
z-index:1000;
}

nav{
max-width:1200px;
margin:auto;
display:flex;
justify-content:space-between;
align-items:center;
padding:1rem 2rem;
}

.logo{
font-family:var(--fontH);
font-size:1.5rem;
color:var(--accent);
text-decoration:none;
}

.nav-links{
display:flex;
gap:2rem;
list-style:none;
}

.nav-links a{
color:var(--text);
text-decoration:none;
font-weight:600;
}

#theme-toggle{
background:none;border:none;
color:var(--accent);
font-size:1.2rem;
cursor:pointer;
}

.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding-top:90px;
}

.hero h1{
font-family:var(--fontH);
font-size:3.5rem;
}

.hero p{color:var(--muted);margin:1rem auto;max-width:800px}

.btn{
display:inline-block;
padding:12px 30px;
margin:10px;
background:var(--accent);
color:#000;
text-decoration:none;
font-weight:700;
border-radius:5px;
}

section{
max-width:1200px;
margin:3rem auto;
padding:4rem 2rem;
background:var(--bg2);
border-radius:10px;
}

h2{
text-align:center;
color:var(--accent);
font-family:var(--fontH);
font-size:2.4rem;
margin-bottom:2rem;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:2rem;
}

.card{
background:var(--bg1);
padding:2rem;
border-radius:8px;
}

footer{
text-align:center;
padding:2rem;
color:var(--muted);
}
</style>
</head>

<body>

<header>
<nav>
<a href="#home" class="logo">Sudheer Babu</a>
<ul class="nav-links">
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#certifications">Certifications</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
<button id="theme-toggle"><i class="fas fa-moon"></i></button>
</nav>
</header>

<section class="hero" id="home">
<div>
<h1>Sudheer Babu</h1>
<p>Electrical Engineering Graduate | Embedded Systems | IoT | Power Electronics</p>
<p>
Final-year Electrical Engineering graduate with hands-on experience in Arduino, ESP32,
PCB design, and real-world automation projects. Actively seeking entry-level roles or internships.
</p>
<a href="#contact" class="btn">Contact Me</a>
<a href="Sudheer_Babu_Resume.pdf" class="btn" download>Download Resume</a>
</div>
</section>

<section id="about">
<h2>About Me</h2>
<p style="max-width:800px;margin:auto;text-align:center">
I am passionate about designing reliable electrical and embedded systems.
My interests include automation, energy monitoring, and renewable energy solutions.
</p>
</section>

<section id="skills">
<h2>Technical Skills</h2>
<div class="grid">
<div class="card">
<h3>Embedded & Programming</h3>
<p>Arduino, ESP32, ESP8266<br>C, C++, Python, MATLAB</p>
</div>
<div class="card">
<h3>Electrical & Electronics</h3>
<p>Analog & Digital Circuits<br>Power Electronics<br>Sensors</p>
</div>
<div class="card">
<h3>Tools & Practices</h3>
<p>KiCAD, Eagle, SPICE<br>AutoCAD Electrical<br>Git</p>
</div>
</div>
</section>

<section id="projects">
<h2>Projects</h2>
<div class="grid">
<div class="card">
<h3>Smart Power Monitoring System</h3>
<p>
IoT-based real-time energy monitoring system measuring voltage, current,
power factor, and energy consumption. Achieved ~15% energy optimization.
</p>
<a href="https://github.com/YOUR-USERNAME/power-monitor" class="btn" target="_blank">View Code</a>
</div>

<div class="card">
<h3>Solar Panel Tracking System</h3>
<p>
Dual-axis solar tracker using LDR sensors and servo motors.
Improved efficiency by ~40% compared to fixed panels.
</p>
<a href="https://github.com/YOUR-USERNAME/solar-tracker" class="btn" target="_blank">View Code</a>
</div>
</div>
</section>

<section id="certifications">
<h2>Certifications</h2>
<ul style="max-width:600px;margin:auto;line-height:2">
<li>Embedded Systems – NPTEL / Coursera</li>
<li>PCB Design – Udemy</li>
<li>MATLAB for Engineers</li>
<li>Industrial Electrical Safety</li>
</ul>
</section>

<section id="contact">
<h2>Contact</h2>
<form id="contact-form" style="max-width:500px;margin:auto">
<input type="text" name="name" placeholder="Name" required><br><br>
<input type="email" name="email" placeholder="Email" required><br><br>
<textarea name="message" placeholder="Message" required></textarea><br><br>
<button class="btn" type="submit">Send Message</button>
<p id="form-message"></p>
</form>
</section>

<footer>
<p>© 2025 Sudheer Babu</p>
<p>Built with HTML, CSS & JavaScript | Hosted on GitHub Pages</p>
</footer>

<script>
emailjs.init("YOUR_PUBLIC_KEY");

document.getElementById("theme-toggle").onclick=()=>{
document.body.classList.toggle("light");
};

document.getElementById("contact-form").addEventListener("submit",function(e){
e.preventDefault();
emailjs.sendForm("YOUR_SERVICE_ID","YOUR_TEMPLATE_ID",this)
.then(()=>alert("Message sent successfully!"),
()=>alert("Failed to send message"));
});
</script>

</body>
</html>
