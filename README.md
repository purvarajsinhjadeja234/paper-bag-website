<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GreenCraft Paper Bags</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{

background:#2e7d32;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
position:sticky;
top:0;
}

nav a{
color:white;
margin-left:20px;
text-decoration:none;
font-weight:500;
}

.hero{

height:90vh;
background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url("https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?auto=format&fit=crop&w=1400&q=80");
background-size:cover;
background-position:center;

display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero h1{
font-size:55px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:35px;
}

.btn{

background:#4caf50;
padding:15px 35px;
color:white;
text-decoration:none;
border-radius:50px;
font-weight:bold;
transition:.3s;
}

.btn:hover{

background:#1b5e20;

}

section{

padding:70px 10%;

}

.title{

font-size:36px;
margin-bottom:20px;
color:#2e7d32;
text-align:center;

}

.about{

display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;

}

.about img{

width:100%;
border-radius:15px;

}

.products{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;

}

.card{

background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 10px 25px rgba(0,0,0,.08);

}

.card img{

width:100%;
height:250px;
object-fit:cover;

}

.card h3{

padding:15px;

}

.card p{

padding:0 15px 20px;

}

.features{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;

}

.feature{

background:white;
padding:30px;
text-align:center;
border-radius:10px;

}

.contact{

background:#2e7d32;
color:white;
text-align:center;

}

.contact input,
.contact textarea{

width:80%;
padding:15px;
margin:10px;
border:none;
border-radius:8px;

}

.contact button{

padding:15px 40px;
background:white;
color:#2e7d32;
border:none;
font-size:18px;
cursor:pointer;
border-radius:40px;

}

footer{

background:#1b5e20;
color:white;
text-align:center;
padding:20px;

}

@media(max-width:800px){

.about{

grid-template-columns:1fr;

}

.hero h1{

font-size:38px;

}

}

</style>

</head>

<body>

<header>

<h2>🌿 GreenCraft Paper Bags</h2>

<nav>

<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Products</a>
<a href="#">Contact</a>

</nav>

</header>

<div class="hero">

<div>

<h1>Handmade Eco-Friendly Paper Bags</h1>

<p>Strong • Recyclable • Handmade with Care</p>

<a class="btn" href="#products">View Products</a>

</div>

</div>

<section>

<h2 class="title">About Us</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1607082350899-7e105aa886ae?auto=format&fit=crop&w=900&q=80">

<div>

<h3>Handmade Paper Bag Manufacturer</h3>

<br>

<p>

We create handmade paper bags using quality kraft paper. Our bags are ideal for grocery stores, gift shops, bakeries, pharmacies, clothing stores, and local businesses looking for eco-friendly packaging.

</p>

<br>

<p>

✔ Handmade Quality<br>

✔ Eco-Friendly<br>

✔ Recyclable Materials<br>

✔ Bulk Orders Welcome

</p>

</div>

</div>

</section>

<section id="products">

<h2 class="title">Our Products</h2>

<div class="products">

<div class="card">

<img src="https://images.unsplash.com/photo-1586075010923-2dd4570fb338?auto=format&fit=crop&w=700&q=80">

<h3>Small Paper Bags</h3>

<p>Perfect for medicines, gifts and small products.</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1514996937319-344454492b37?auto=format&fit=crop&w=700&q=80">

<h3>Medium Paper Bags</h3>

<p>Ideal for clothing stores and grocery shops.</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=700&q=80">

<h3>Large Paper Bags</h3>

<p>Suitable for restaurants and supermarkets.</p>

</div>

</div>

</section>

<section>

<h2 class="title">Why Choose Us</h2>

<div class="features">

<div class="feature">

<h3>🌱 Eco Friendly</h3>

<p>Made from recyclable kraft paper.</p>

</div>

<div class="feature">

<h3>✋ Handmade</h3>

<p>Every bag is crafted carefully by hand.</p>

</div>

<div class="feature">

<h3>💪 Strong</h3>

<p>Durable and reliable for daily use.</p>

</div>

<div class="feature">

<h3>🚚 Bulk Supply</h3>

<p>Available for wholesale orders.</p>

</div>

</div>

</section>

<section class="contact">

<h2>Contact Us</h2>

<br>

<input placeholder="Your Name">

<br>

<input placeholder="Phone Number">

<br>

<textarea rows="5" placeholder="Your Requirement"></textarea>

<br>

<button>Send Inquiry</button>

</section>

<footer>

© 2026 GreenCraft Paper Bags | Handmade | Eco-Friendly

</footer>

</body>
</html>
