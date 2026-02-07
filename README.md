<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tbazar Company</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:Arial, Helvetica, sans-serif;background:#f5f6fa;}

header{
    background:white;
    padding:15px 20px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:22px;
    font-weight:bold;
    color:#0d6efd;
}

nav a{
    margin-left:15px;
    text-decoration:none;
    color:#333;
    font-weight:bold;
}

.hero{
    background:#0d6efd;
    color:white;
    padding:70px 20px;
    text-align:center;
}

.section{
    padding:40px 20px;
    max-width:1100px;
    margin:auto;
}

.section h2{
    text-align:center;
    margin-bottom:20px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:10px;
    padding:15px;
    text-align:center;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
}

.card img{
    width:100%;
    height:150px;
    object-fit:cover;
    border-radius:8px;
}

.price{
    font-weight:bold;
    margin:10px 0;
}

.btn{
    display:inline-block;
    background:#25D366;
    color:white;
    padding:10px 15px;
    border-radius:5px;
    text-decoration:none;
    font-size:14px;
}

.contact{
    text-align:center;
    line-height:1.8;
}

footer{
    margin-top:30px;
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
<div class="logo">🛒 Tbazar Company</div>
<nav>
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero">
<h1>Welcome to Tbazar</h1>
<p>Quality products • Best price • Easy WhatsApp order</p>
</div>

<div id="products" class="section">
<h2>Featured Products</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300x200" alt="">
<h3>Product Name</h3>
<div class="price">₹ 500</div>
<a class="btn" href="https://wa.me/919101756298">Order Now</a>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x200" alt="">
<h3>Product Name</h3>
<div class="price">₹ 700</div>
<a class="btn" href="https://wa.me/919101756298">Order Now</a>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x200" alt="">
<h3>Product Name</h3>
<div class="price">₹ 900</div>
<a class="btn" href="https://wa.me/919101756298">Order Now</a>
</div>

</div>
</div>

<div id="contact" class="section contact">
<h2>Contact Us</h2>
<p>Phone: +91 9101756298</p>
<p>Email: coming soon</p>
</div>

<footer>
<p>© 2026 Tbazar Company. All rights reserved.</p>
</footer>

</body>
</html>
