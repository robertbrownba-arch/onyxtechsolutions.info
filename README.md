logo.png


<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Computer Repair Waterbury CT | OnyxTech Solutions</title>

<meta name="description" content="OnyxTech Solutions L.L.C. provides computer repair, networking, POS systems, virus removal and IT services in Waterbury Connecticut.">

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&display=swap" rel="stylesheet">

<style>

/* GLOBAL */

body{
margin:0;
font-family:Arial;
background:#04070f;
color:white;
overflow-x:hidden;
}

/* animated circuit board background */

body::before{
content:"";
position:fixed;
width:200%;
height:200%;
background-image:
linear-gradient(#00ffff 1px,transparent 1px),
linear-gradient(90deg,#00ffff 1px,transparent 1px);
background-size:60px 60px;
opacity:0.05;
animation:move 40s linear infinite;
}

@keyframes move{
0%{transform:translate(0,0)}
100%{transform:translate(-600px,-600px)}
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 25px;
background:#0b1120;
position:sticky;
top:0;
z-index:999;
}

.logo{
display:flex;
align-items:center;
font-family:Orbitron;
font-size:18px;
}

.logo img{
height:40px;
margin-right:10px;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

/* HERO */

.hero{
text-align:center;
padding:110px 20px;
}

.hero h1{
font-family:Orbitron;
font-size:42px;
}

.hero p{
color:#ccc;
}

button{
background:#00ffff;
border:none;
padding:12px 20px;
border-radius:6px;
cursor:pointer;
font-weight:bold;
}

/* SECTIONS */

section{
padding:60px 20px;
max-width:1000px;
margin:auto;
}

h2{
font-family:Orbitron;
color:#00ffff;
}

/* GRID */

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#0f1629;
padding:20px;
border-radius:10px;
border:1px solid #00ffff33;
}

/* FORMS */

input,textarea,select{
width:100%;
padding:10px;
margin-top:10px;
background:#0a0f1f;
border:1px solid #00ffff33;
color:white;
border-radius:6px;
}

/* CHATBOT */

.chatbot{
position:fixed;
bottom:20px;
right:20px;
width:300px;
background:#0f1629;
border-radius:10px;
overflow:hidden;
box-shadow:0 0 15px #00ffff44;
}

.chat-header{
background:#00ffff;
color:black;
padding:10px;
font-weight:bold;
}

.chat-body{
height:200px;
overflow-y:auto;
padding:10px;
font-size:14px;
}

.chat-input{
display:flex;
}

.chat-input input{
flex:1;
border:none;
}

.chat-input button{
background:#00ffff;
}

/* FOOTER */

footer{
text-align:center;
padding:30px;
color:#aaa;
}

/* MOBILE */

@media(max-width:600px){

.hero h1{
font-size:28px;
}

}

</style>

</head>

<body>

<nav>

<div class="logo">
<img src="logo.png">
OnyxTech Solutions
</div>

<div>
<a href="#services">Services</a>
<a href="#booking">Booking</a>
<a href="#portal">Portal</a>
<a href="#contact">Contact</a>
</div>

</nav>

<section class="hero">

<h1>Computer Repair Waterbury CT</h1>

<p>Professional IT Support, Networking, POS Systems and Device Repair</p>

<button onclick="scrollToBooking()">Book Service</button>

</section>

<section>

<h2>Certifications & Memberships</h2>

<div class="grid">

<div class="card">CompTIA Network+</div>
<div class="card">CompTIA Security+</div>
<div class="card">Retail Infrastructure Field Technician Experience</div>
<div class="card">Better Business Bureau Member</div>
<div class="card">Waterbury Chamber Member</div>
<div class="card">Milford Chamber Member</div>

</div>

</section>

<section id="services">

<h2>Services</h2>

<div class="grid">

<div class="card">
<h3>Computer Repair</h3>
Break/Fix repairs, gaming systems, headphones, handheld devices, tablets and phones.
</div>

<div class="card">
<h3>POS Systems</h3>
Retail and commercial POS install, self checkout systems, Lexmark printers.
</div>

<div class="card">
<h3>Networking</h3>
Cat6 installs, access points, cradlepoint routers, MDF builds and audio servers.
</div>

<div class="card">
<h3>Hard Drive Services</h3>
Drive replacement and data recovery.
</div>

<div class="card">
<h3>Virus Removal</h3>
Malware cleanup and security optimization.
</div>

</div>

</section>

<section>

<h2>Instant Quote Calculator</h2>

<select id="service">

<option value="120">Computer Repair $120</option>
<option value="100">Virus Removal $100</option>
<option value="200">Network Setup $200</option>
<option value="150">Hard Drive Recovery $150</option>
<option value="250">POS Repair $250</option>

</select>

<button onclick="calc()">Calculate</button>

<p id="price"></p>

</section>

<section id="booking">

<h2>Book a Service</h2>

<form>

<input placeholder="Name">

<input placeholder="Phone">

<textarea placeholder="Describe the problem"></textarea>

<button type="submit">Submit Request</button>

</form>

</section>

<section id="portal">


<h2>Remote Support</h2>

<p>If a technician requested remote support download below.</p>

<a href="https://anydesk.com/en/downloads">
<button>Download Remote Support</button>
</a>

</section>

<section>

<h2>Service Area</h2>

Waterbury

<iframe 
src="https://maps.google.com/maps?q=waterbury%20ct&t=&z=11&ie=UTF8&iwloc=&output=embed"
width="100%"
height="350"
style="border:0;border-radius:10px">
</iframe>

</section>

<section id="contact">

<h2>Contact</h2>

<p>Phone: 203-800-8258</p>

<p>Email: support@onyxtechsolutions.com</p>

<p>Serving Waterbury, Milford and surrounding Connecticut areas.</p>

</section>

<footer>

© OnyxTech Solutions L.L.C.

</footer>

<div class="chatbot">

<div class="chat-header">
IT Support Chat
</div>

<div class="chat-body" id="chatBody">
Hello! Ask about computer repair, networking or POS systems.
</div>

<div class="chat-input">

<input id="chatInput" placeholder="Type message">

<button onclick="chat()">Send</button>

</div>

</div>

<script>

/* scroll */

function scrollToBooking(){
document.getElementById("booking").scrollIntoView({behavior:"smooth"})
}

/* quote */

function calc(){
let price=document.getElementById("service").value
document.getElementById("price").innerHTML="Estimated Cost: $"+price
}

/* ticket tracking */

function track(){
let id=document.getElementById("ticket").value
document.getElementById("status").innerHTML="Ticket "+id+" is currently in diagnostic stage."
}

/* chatbot */

function chat(){

let input=document.getElementById("chatInput")
let body=document.getElementById("chatBody")

body.innerHTML+="<br><b>You:</b> "+input.value

let reply="Please call 203-819-8645 for support."

if(input.value.toLowerCase().includes("virus"))
reply="Virus removal service is $100."

if(input.value.toLowerCase().includes("network"))
reply="We install Cat6 networking and business infrastructure."

body.innerHTML+="<br><b>Tech:</b> "+reply

input.value=""

}

</script>

</body>
</html>
