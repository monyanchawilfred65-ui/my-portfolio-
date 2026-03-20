<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wilfred Monyancha | Premium Virtual Assistant</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#0b1c2c;color:#fff;scroll-behavior:smooth}
header{padding:80px 20px;text-align:center;background:linear-gradient(135deg,#0b1c2c,#132f4c)}
h1{font-size:3rem}
p{opacity:0.9}
.btn{padding:12px 25px;border:none;border-radius:30px;margin:10px;cursor:pointer;font-weight:600}
.primary{background:#1e90ff;color:#fff}
.secondary{background:#fff;color:#0b1c2c}
.section{padding:60px 20px;max-width:1100px;margin:auto}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{background:#132f4c;padding:25px;border-radius:15px;transition:0.3s}
.card:hover{transform:translateY(-10px);box-shadow:0 10px 20px rgba(0,0,0,0.3)}
.pricing{display:flex;flex-wrap:wrap;gap:20px}
.price-card{flex:1;background:#132f4c;padding:30px;border-radius:15px;text-align:center}
.price-card h3{margin-bottom:10px}
.price{font-size:2rem;margin:15px 0}
.skills .bar{background:#1e90ff;height:10px;border-radius:10px;margin:10px 0}
.testimonial{background:#132f4c;padding:20px;border-radius:10px;margin:10px 0}
.whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:15px;border-radius:50%;font-size:20px;text-decoration:none}
footer{text-align:center;padding:20px;background:#08121c}
</style>
</head>
<body>

<header>
<h1>Wilfred Monyancha</h1>
<p>Helping Busy Entrepreneurs Save Time & Grow Faster 🚀</p>
<button class="btn primary">Hire Me</button>
<button class="btn secondary" onclick="scrollToContact()">Contact Me</button>
</header>

<section class="section">
<h2>About Me</h2>
<p>I am a results-driven Virtual Assistant dedicated to helping businesses streamline operations, increase productivity, and stay organized. With strong communication skills and attention to detail, I deliver reliable and efficient support.</p>
</section>

<section class="section">
<h2>Services</h2>
<div class="cards">
<div class="card">📧 Email Management</div>
<div class="card">📊 Data Entry</div>
<div class="card">📅 Scheduling</div>
<div class="card">📱 Social Media Management</div>
<div class="card">💬 Customer Support</div>
<div class="card">🔍 Research</div>
</div>
</section>

<section class="section">
<h2>Pricing Packages</h2>
<div class="pricing">
<div class="price-card">
<h3>Basic</h3>
<p class="price">$10</p>
<p>Simple tasks & data entry</p>
<button class="btn primary">Order Now</button>
</div>
<div class="price-card">
<h3>Standard</h3>
<p class="price">$25</p>
<p>Email & scheduling support</p>
<button class="btn primary">Order Now</button>
</div>
<div class="price-card">
<h3>Premium</h3>
<p class="price">$50</p>
<p>Full VA support package</p>
<button class="btn primary">Order Now</button>
</div>
</div>
</section>

<section class="section skills">
<h2>Skills</h2>
<p>Communication</p><div class="bar" style="width:90%"></div>
<p>Time Management</p><div class="bar" style="width:85%"></div>
<p>Data Entry</p><div class="bar" style="width:95%"></div>
<p>Tech Skills</p><div class="bar" style="width:80%"></div>
</section>

<section class="section">
<h2>Testimonials ⭐⭐⭐⭐⭐</h2>
<div class="testimonial">"Wilfred is incredibly reliable and efficient. Highly recommend!"</div>
<div class="testimonial">"Excellent communication and fast delivery!"</div>
</section>

<section id="contact" class="section">
<h2>Contact Me</h2>
<p>Phone: 0736146988</p>
<p>Email: wilfredmercor@gmail.com</p>
<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea placeholder="Your Message" required></textarea>
<button class="btn primary">Send Message</button>
</form>
</section>

<a class="whatsapp" href="https://wa.me/254736146988" target="_blank">💬</a>

<footer>
<p>© 2026 Wilfred Monyancha | Virtual Assistant</p>
</footer>

<script>
function scrollToContact(){
document.getElementById('contact').scrollIntoView({behavior:'smooth'});
}
</script>

</body>
</html>
