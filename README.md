# COTTONCLOTHING
WE SELL COTTON CLOTHING PRODUCT ONLINE . VISIT OUR WEBSITE TO CATCH THE DEALS
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CottonClothing</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f7f7f7;
}

header{
background:#131921;
color:white;
padding:15px 5%;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:32px;
font-weight:bold;
color:#00d4ff;
}

.search{
width:40%;
padding:12px;
border:none;
border-radius:5px;
}

.hero{
height:400px;
background:linear-gradient(135deg,#0f172a,#2563eb);
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-align:center;
}

.hero h1{
font-size:55px;
}

.hero p{
margin-top:15px;
font-size:20px;
}

.shop-btn{
margin-top:20px;
padding:14px 30px;
background:white;
color:#2563eb;
text-decoration:none;
font-weight:bold;
border-radius:30px;
}

.categories{
padding:40px 5%;
}

.categories h2{
margin-bottom:20px;
}

.cat-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.cat{
background:white;
padding:25px;
text-align:center;
border-radius:12px;
box-shadow:0 4px 10px rgba(0,0,0,.1);
}

.products{
padding:40px 5%;
}

.products h2{
margin-bottom:20px;
}

.product-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:12px;
overflow:hidden;
box-shadow:0 4px 12px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:280px;
object-fit:cover;
}

.info{
padding:15px;
}

.price{
color:green;
font-size:22px;
font-weight:bold;
margin:10px 0;
}

.btn{
display:block;
text-align:center;
padding:12px;
background:#2563eb;
color:white;
text-decoration:none;
border-radius:6px;
}

footer{
background:#131921;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
</style>
</head>

<body>

<header>
<div class="logo">🧵 CottonClothing</div>
<input class="search" placeholder="Search products...">
</header>

<section class="hero">
<h1>Fashion That Feels Premium</h1>
<p>Modern Clothing • Best Prices • Fast Delivery</p>
<a href="#products" class="shop-btn">Shop Now</a>
</section>

<section class="categories">
<h2>Categories</h2>
<div class="cat-grid">
<div class="cat">👔 Shirts</div>
<div class="cat">👕 T-Shirts</div>
<div class="cat">👖 Jeans</div>
<div class="cat">🧥 Hoodies</div>
</div>
</section>

<section class="products" id="products">
<h2>Trending Products</h2>

<div class="product-grid">

<div class="card">
<img src="https://picsum.photos/400/500?1">
<div class="info">
<h3>Premium Cotton T-Shirt</h3>
<div class="price">₹499</div>
<a class="btn" href="#">Add To Cart</a>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?2">
<div class="info">
<h3>Casual Shirt</h3>
<div class="price">₹899</div>
<a class="btn" href="#">Add To Cart</a>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?3">
<div class="info">
<h3>Denim Jeans</h3>
<div class="price">₹1299</div>
<a class="btn" href="#">Add To Cart</a>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?4">
<div class="info">
<h3>Premium Hoodie</h3>
<div class="price">₹1499</div>
<a class="btn" href="#">Add To Cart</a>
</div>
</div>

</div>
</section>

<footer>
© 2026 CottonClothing | All Rights Reserved
</footer>

</body>
</html>
