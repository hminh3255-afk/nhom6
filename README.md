<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fashion Store - Nhóm 6 RM29.04</title>
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}
body{
    background:#f5f5f5;
}
header{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
nav{
    background:#444;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}
.hero{
    background:url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?w=1200') center/cover;
    height:400px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-shadow:2px 2px 5px black;
}
.hero h1{
    font-size:50px;
}
.container{
    width:90%;
    margin:auto;
    padding:40px 0;
}
.section-title{
    text-align:center;
    margin-bottom:30px;
    color:#333;
}
.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}
.product{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
    text-align:center;
}
.product img{
    width:100%;
    height:300px;
    object-fit:cover;
}
.product h3{
    margin:15px 0;
}
.price{
    color:red;
    font-weight:bold;
    margin-bottom:10px;
}
button{
    background:#222;
    color:white;
    border:none;
    padding:10px 20px;
    margin-bottom:20px;
    cursor:pointer;
    border-radius:5px;
}
.members{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}
.member{
    background:white;
    padding:20px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}
</style>
</head>
<body>
<header>
    <h1>FASHION STORE</h1>
    <p>Website bán quần áo - Nhóm 6 - Lớp RM29.04</p>
</header>
<nav>
    <a href="#home">Trang chủ</a>
    <a href="#products">Sản phẩm</a>
    <a href="#members">Thành viên</a>
    <a href="#contact">Liên hệ</a>
</nav>
<section class="hero" id="home">
    <h1>THỜI TRANG HIỆN ĐẠI</h1>
</section>
<div class="container">
<h2 class="section-title" id="products">Sản Phẩm Nổi Bật</h2>
<div class="products">
    <div class="product">
        <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?w=600">
        <h3>Áo Thun Basic</h3>
        <p class="price">199.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://images.unsplash.com/photo-1603252109303-2751441dd157?w=600">
        <h3>Áo Hoodie</h3>
        <p class="price">459.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://images.unsplash.com/photo-1542272604-787c3835535d?w=600">
        <h3>Quần Jean Nam</h3>
        <p class="price">349.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
    <div class="product">
        <img src="https://images.unsplash.com/photo-1581044777550-4cfa60707c03?w=600">
        <h3>Váy Thời Trang</h3>
        <p class="price">399.000 VNĐ</p>
        <button>Mua ngay</button>
    </div>
</div>
</div>
<div class="container">
<h2 class="section-title" id="members">Thành Viên Nhóm 6</h2>
<div class="members">
    <div class="member">
        <h3>Cao Xuân Hải Minh</h3>
        <p>Thành viên nhóm</p>
    </div>
    <div class="member">
        <h3>Lã Ngọc Khải</h3>
        <p>Thành viên nhóm</p>
    </div>
    <div class="member">
        <h3>Trần Tuấn Hưng</h3>
        <p>Thành viên nhóm</p>
    </div>
    <div class="member">
        <h3>Ngô Trường Sơn</h3>
        <p>Thành viên nhóm</p>
    </div>
</div>
</div>
<div class="container" id="contact">
    <h2 class="section-title">Liên Hệ</h2>
    <p style="text-align:center;">
        Fashion Store - Nhóm 6 RM29.04<br>
        Email: nhom6rm2904@gmail.com<br>
        Hotline: 0123 456 789
    </p>
</div>
<footer>
    <p>© 2026 Fashion Store | Nhóm 6 - RM29.04</p>
</footer>
</body>
</html>
