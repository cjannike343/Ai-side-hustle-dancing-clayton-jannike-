<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SboNdaba Dance Company</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
body { margin:0; font-family:'Montserrat',sans-serif; background:#f0f0f0; color:#333; scroll-behavior:smooth;}
a { text-decoration:none; }
header, section, footer { position:relative; z-index:1; }
.hero { 
  background: url('https://images.ctfassets.net/adaoj5ok2j3t/4jQuyR4r7jRQH9c5rCjDHS/f9a7243c4cdeeb5beeb00fc595d7971e/carlvanderlinde-wepresent13.jpg?fm=webp&q=75&w=3000') center/cover no-repeat; 
  height:90vh; display:flex; flex-direction:column; justify-content:center; align-items:center; color:white; text-align:center;
}
.hero h1 { font-size:3rem; margin:0; animation: fadeInDown 1s ease-out; }
.hero p { font-size:1.3rem; margin:10px 0 0; animation: fadeInUp 1s ease-out; }
.hero .cta { margin-top:20px; padding:15px 35px; background:#ff4757; border-radius:50px; font-weight:bold; animation: fadeIn 2s ease-out; }
nav { display:flex; justify-content:center; gap:25px; background:#222; padding:15px; position:sticky; top:0; z-index:1000;}
nav a { color:white; font-weight:bold; }
section { padding:70px 20px; max-width:1000px; margin:0 auto; }
section h2 { color:#ff4757; margin-bottom:25px; font-size:2rem; text-align:center; }
section p { line-height:1.6; margin-bottom:20px; text-align:center; }
.section-img { max-width:100%; border-radius:10px; margin:20px 0; }
.slider { display:flex; overflow-x:auto; scroll-snap-type:x mandatory; gap:15px; padding:20px 0; }
.slider img { width:300px; height:200px; object-fit:cover; border-radius:10px; scroll-snap-align:start; }
.cta { display:inline-block; background:#ff4757; color:white; padding:12px 25px; border-radius:50px; font-weight:bold; }
footer { background:#222; color:white; text-align:center; padding:30px; }
@keyframes fadeInDown { from {opacity:0; transform:translateY(-30px);} to {opacity:1; transform:translateY(0);} }
@keyframes fadeInUp { from {opacity:0; transform:translateY(30px);} to {opacity:1; transform:translateY(0);} }
@keyframes fadeIn { from {opacity:0;} to {opacity:1;} }
@media(max-width:600px){ .hero h1{ font-size:2rem; } .hero p{ font-size:1rem; } .slider img{ width:250px; height:160px;} }
</style>
</head>
<body>

<header class="hero">
<h1>SboNdaba Dance Company</h1>
<p>Empowering performing artists from Cape Town & beyond</p>
<a href="#programmes" class="cta">Explore Programmes</a>
</header>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#programmes">Programmes</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>

<section id="home">
<h2>Welcome to SboNdaba</h2>
<p>SboNdaba Dance, founded by Sbonakaliso Ndaba, is a non-profit company creating opportunities for township performers in Cape Town. Our work includes professional performances, community outreach, and youth development.</p>
<img class="section-img" src="https://images.ctfassets.net/adaoj5ok2j3t/66F7sLqpZ22VpESjGFTBd7/21b4fda7a6572c4509dbcb175c7df47c/carlvanderlinde-wepresent11.jpg" alt="Performance">
</section>

<section id="about">
<h2>About Us</h2>
<p>We empower artists by providing professional platforms, workshops, and mentorship programs. Our vision is to uplift the arts community and create sustainable careers for dancers from all backgrounds.</p>
<img class="section-img" src="https://images.ctfassets.net/adaoj5ok2j3t/76aosQ4tIcfWxSGzZnFAoy/ccbc1ef90dacb6915e94b5fcd290edb0/carlvanderlinde-wepresent7.jpg" alt="Rehearsal">
</section>

<section id="programmes">
<h2>Our Programmes</h2>
<p>We offer:</p>
<ul style="text-align:center;">
<li>Professional dance company performances</li>
<li>Community and youth outreach workshops</li>
<li>Training for aspiring dancers & teachers</li>
</ul>
<a class="cta" href="#contact">Join Us / Contact Us</a>
</section>

<section id="gallery">
<h2>Gallery</h2>
<div class="slider">
<img src="https://images.ctfassets.net/adaoj5ok2j3t/4jQuyR4r7jRQH9c5rCjDHS/f9a7243c4cdeeb5beeb00fc595d7971e/carlvanderlinde-wepresent13.jpg?fm=webp&q=75&w=3000" alt="Gallery 1">
<img src="https://images.ctfassets.net/adaoj5ok2j3t/6zmMK5UtxvknL5Bnet7kjy/2b1b26e509a5dc3300179fc9369d1e98/carlvanderlinde-wepresent12.jpg?fm=webp&q=75&w=3000" alt="Gallery 2">
<img src="https://images.ctfassets.net/adaoj5ok2j3t/76aosQ4tIcfWxSGzZnFAoy/ccbc1ef90dacb6915e94b5fcd290edb0/carlvanderlinde-wepresent7.jpg?fm=webp&q=75&w=3000" alt="Gallery 3">
<img src="https://images.ctfassets.net/adaoj5ok2j3t/2kUIMZYwJE4z4Fh4xiT580/cd8dacb3766737c5ec6ca8e119a0d12a/carlvanderlinde-wepresent8.jpg?fm=webp&q=75&w=3000" alt="Gallery 4">
</div>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>Email: <a href="mailto:info@sbondabadance.co.za">info@sbondabadance.co.za</a></p>
<p>Phone: +27 83 267 3029</p>
<p>Instagram: <a href="https://www.instagram.com/sbondabadance/" target="_blank">@SboNdabaDance</a></p>
<a class="cta" href="https://www.instagram.com/sbondabadance/" target="_blank">Visit Instagram</a>
</section>

<footer>
&copy; 2025 SboNdaba Dance Company. All rights reserved.
</footer>

</body>
</html>
