<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Perpustakaan Digital</title>

<style>
body{
    font-family:Arial,sans-serif;
    background:#f5f7fa;
    margin:0;
}

header{
    background:#1e293b;
    color:white;
    text-align:center;
    padding:30px;
}

.container{
    max-width:1200px;
    margin:auto;
    padding:20px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fill,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,.1);
}

.card img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.card h3{
    padding:10px;
    margin:0;
}

.btn{
    display:block;
    text-align:center;
    padding:12px;
    text-decoration:none;
    background:#2563eb;
    color:white;
}
</style>
</head>

<body>

<header>
<h1>📚 Perpustakaan Digital</h1>
<p>Koleksi e-book untuk pembelajaran dan rujukan</p>
</header>

<div class="container">

<div class="grid">

<div class="card">
<img src="https://via.placeholder.com/300x400">
<h3>E-Book Marketing</h3>
<a class="btn" href="#">Baca Sekarang</a>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x400">
<h3>E-Book AI</h3>
<a class="btn" href="#">Baca Sekarang</a>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x400">
<h3>E-Book Bisnes</h3>
<a class="btn" href="#">Baca Sekarang</a>
</div>

</div>

</div>

</body>
</html>
