<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>dıbesquality</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      color: #222;
    }

    header {
      background: #111;
      color: white;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .topbar {
      max-width: 1200px;
      margin: auto;
      padding: 16px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .search {
      flex: 1;
      min-width: 220px;
    }

    .search input {
      width: 100%;
      padding: 12px 14px;
      border: none;
      border-radius: 8px;
    }

    .actions {
      display: flex;
      gap: 18px;
      font-size: 15px;
    }

    .actions a,
    nav a {
      color: white;
      text-decoration: none;
    }

    nav {
      background: #1d1d1d;
      text-align: center;
      padding: 12px;
    }

    nav a {
      margin: 0 12px;
      font-size: 15px;
    }

    .hero {
      height: 420px;
      background: url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?q=80&w=1200') center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }

    .hero-content {
      background: rgba(0,0,0,0.45);
      padding: 28px;
      border-radius: 12px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 18px;
    }

    .btn {
      display: inline-block;
      background: #111;
      color: white;
      text-decoration: none;
      padding: 12px 22px;
      border-radius: 8px;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 50px 20px;
    }

    .section-title {
      font-size: 32px;
      margin-bottom: 30px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
    }

    .card {
      background: white;
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 4px 14px rgba(0,0,0,0.08);
      transition: 0.25s;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card img {
      width: 100%;
      height: 320px;
      object-fit: cover;
    }

    .card-body {
      padding: 18px;
    }

    .card h3 {
      font-size: 20px;
      margin-bottom: 8px;
    }

    .desc {
      color: #666;
      font-size: 14px;
      margin-bottom: 12px;
    }

    .price {
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 14px;
    }

    .card-buttons {
      display: flex;
      gap: 10px;
    }

    .outline-btn {
      display: inline-block;
      padding: 11px 16px;
      border: 1px solid #111;
      color: #111;
      text-decoration: none;
      border-radius: 8px;
      font-size: 14px;
    }

    footer {
      background: #111;
      color: white;
      margin-top: 40px;
      padding: 30px 20px;
      text-align: center;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 34px;
      }

      .actions {
        width: 100%;
        justify-content: center;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="topbar">
    <div class="logo">DIBESQUALITY</div>

    <div class="search">
      <input type="text" placeholder="Ürün ara...">
    </div>

    <div class="actions">
      <a href="#">Hesabım</a>
      <a href="#">Favoriler</a>
      <a href="#">Sepet (2)</a>
    </div>
  </div>

  <nav>
    <a href="#">Yeni Gelenler</a>
    <a href="#">Kadın</a>
    <a href="#">Erkek</a>
    <a href="#">Ayakkabı</a>
    <a href="#">Aksesuar</a>
    <a href="#">İndirim</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-content">
    <h1>Yeni Sezon Koleksiyonu</h1>
    <p>Tarzını yansıtan ürünleri keşfet.</p>
    <a href="#" class="btn">Alışverişe Başla</a>
  </div>
</section>

<section class="container">
  <h2 class="section-title">Öne Çıkan Ürünler</h2>

  <div class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?q=80&w=800" alt="Siyah Tişört">
      <div class="card-body">
        <h3>Siyah Basic Tişört</h3>
        <p class="desc">Günlük kullanıma uygun rahat kesim.</p>
        <div class="price">₺499</div>
        <div class="card-buttons">
          <a href="#" class="btn">Sepete Ekle</a>
          <a href="#" class="outline-btn">Detay</a>
        </div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?q=80&w=800" alt="Kadın Kombin">
      <div class="card-body">
        <h3>Modern Kadın Kombin</h3>
        <p class="desc">Yeni sezon trend parçalar.</p>
        <div class="price">₺899</div>
        <div class="card-buttons">
          <a href="#" class="btn">Sepete Ekle</a>
          <a href="#" class="outline-btn">Detay</a>
        </div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?q=80&w=800" alt="Yeni Koleksiyon">
      <div class="card-body">
        <h3>Yeni Koleksiyon Elbise</h3>
        <p class="desc">2026 sezonunun öne çıkan modeli.</p>
        <div class="price">₺1.249</div>
        <div class="card-buttons">
          <a href="#" class="btn">Sepete Ekle</a>
          <a href="#" class="outline-btn">Detay</a>
        </div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=800" alt="Ayakkabı">
      <div class="card-body">
        <h3>Spor Ayakkabı</h3>
        <p class="desc">Konfor ve modern görünüm bir arada.</p>
        <div class="price">₺1.499</div>
        <div class="card-buttons">
          <a href="#" class="btn">Sepete Ekle</a>
          <a href="#" class="outline-btn">Detay</a>
        </div>
      </div>
    </div>

  </div>
</section>

<footer>
  <p>© 2026 dıbesquality | Güvenli Alışveriş | Tüm Hakları Saklıdır</p>
</footer>

</body>
</html>
