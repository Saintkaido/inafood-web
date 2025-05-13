# inafood-web
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Inafood - Makanan Ringan Berkualitas</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #fffdf9;
      color: #333;
    }
    header {
      background-color: #e63946;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background-color: #ffe6e1;
      padding: 15px;
      text-align: center;
    }
    nav a {
      margin: 0 20px;
      text-decoration: none;
      color: #e63946;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #b51f2e;
      text-decoration: underline;
    }
    .hero {
      background: url('https://inafood.com/storage/slider/November2022/M6tXrrIdk85UroCgEqcI.jpg') no-repeat center center/cover;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .products {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .products img {
      width: 180px;
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .products img:hover {
      transform: scale(1.1);
      box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    }
    footer {
      background: #e63946;
      color: white;
      text-align: center;
      padding: 20px;
    }
    ul {
      list-style: disc;
      padding-left: 20px;
    }
    .cta-button {
      background-color: #e63946;
      color: white;
      padding: 10px 20px;
      font-size: 1em;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .cta-button:hover {
      background-color: #b51f2e;
    }

    .slider-container {
      position: relative;
      overflow: hidden;
      max-width: 800px;
      margin: 40px auto;
    }
    .slider {
      display: flex;
      animation: slide 12s infinite;
    }
    .slide {
      min-width: 100%;
      box-sizing: border-box;
      text-align: center;
    }
    .slide img {
      width: 100%;
      max-width: 300px;
      height: auto;
      border-radius: 10px;
    }
    @keyframes slide {
      0%   { transform: translateX(0); }
      33%  { transform: translateX(-100%); }
      66%  { transform: translateX(-200%); }
      100% { transform: translateX(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>INAFOOD</h1>
    <p>Membawa Kelezatan ke Setiap Gigitan Sejak 1997</p>
  </header>
  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#produk">Produk</a>
    <a href="#keunikan">Keunikan</a>
    <a href="#prestasi">Prestasi</a>
    <a href="#ekspor">Ekspor</a>
    <a href="#kontak">Kontak</a>
  </nav>
  <div class="hero" id="beranda">
    Produk Unggulan Kami
  </div>
  <section class="section" id="tentang">
    <h2>Tentang Kami</h2>
    <p>PT Intim Harmonis Foods Industri (INAFOOD) adalah perusahaan manufaktur makanan ringan yang berdiri sejak 1997 dan berlokasi di Pasuruan, Jawa Timur. Kami memproduksi berbagai jenis biskuit, wafer, dan makanan ringan lainnya.</p>
    <ul>
      <li><strong>Visi:</strong> Menjadi pemimpin industri makanan ringan yang inovatif dan berkualitas.</li>
      <li><strong>Misi:</strong>
        <ul>
          <li>Menghasilkan produk berkualitas tinggi sesuai standar internasional.</li>
          <li>Memenuhi kebutuhan konsumen dengan inovasi berkelanjutan.</li>
          <li>Menjaga kepuasan pelanggan sebagai prioritas utama.</li>
        </ul>
      </li>
    </ul>
  </section>

  <section class="section" id="produk">
    <h2>Produk Kami</h2>
    <p>Kami menawarkan berbagai produk makanan ringan dalam kategori:</p>
    <ul>
      <li>Biskuit: Okebis, Goodbis</li>
      <li>Wafer: Hitamanis, Fortius</li>
      <li>Crackers dan Permen</li>
    </ul>
    <div class="products">
      <img src="https://inafood.com/storage/products/yXJlU4S0r9M8kNoyfMHL.jpg" alt="Goodbis">
      <img src="https://inafood.com/storage/products/Fq5V1RmqzjEDUeG7kRx3.jpg" alt="Fortius">
    </div>
    <div style="text-align:center; margin-top: 20px;">
      <button class="cta-button" onclick="alert('Terima kasih telah tertarik! Silakan hubungi kami untuk kerja sama.')">Hubungi Kami</button>
    </div>
  </section>

  <section class="section" id="keunikan">
    <h2>Keunikan Brand Inafood</h2>
    <ul>
      <li><strong>Produk berkualitas ekspor:</strong> Memenuhi standar internasional dan telah dipasarkan ke berbagai negara di Asia, Afrika, hingga Eropa.</li>
      <li><strong>Sertifikasi lengkap:</strong> Telah memperoleh ISO 22000 (Keamanan Pangan), Halal MUI, dan BPOM.</li>
      <li><strong>Diversifikasi merek:</strong> Berbagai varian seperti Okebis, Goodbis, Hitamanis, Fortius untuk semua kalangan.</li>
      <li><strong>Inovasi berkelanjutan:</strong> Terus mengembangkan produk baru sesuai dengan selera dan kebutuhan pasar global.</li>
      <li><strong>Nilai perusahaan yang kuat:</strong> Mengutamakan integritas, kerja sama tim, tanggung jawab sosial dan kepuasan pelanggan.</li>
    </ul>
  </section>

  <section class="section" id="prestasi">
    <h2>Prestasi Kami</h2>
    <ul>
      <li>🏆 ISO 22000 Sertifikasi Sistem Manajemen Keamanan Pangan</li>
      <li>✅ Top Brand untuk kategori biskuit dan wafer</li>
      <li>🌍 Ekspor ke lebih dari 20 negara besar</li>
    </ul>
  </section>

  <section class="section" id="ekspor">
    <h2>Negara Tujuan Ekspor</h2>
    <p style="text-align:center; max-width:800px; margin: auto;">
      Saat ini biskuit Inafood telah dipasarkan ke berbagai negara di Asia dan Afrika. Kami terus meningkatkan jalur pemasaran internasional hingga ke seluruh dunia karena kami selalu menghadirkan produk yang terbaik, berkualitas, dan kompetitif untuk jutaan konsumen di mancanegara.
    </p>
    <div class="slider-container">
      <div class="slider">
        <div class="slide">
          <img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/Map-China.png" alt="China" />
          <p>China</p>
        </div>
        <div class="slide">
          <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Timor-Leste_map_flag.png" alt="Timor Leste" />
          <p>Timor Leste</p>
        </div>
        <div class="slide">
          <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Brunei_map_flag.png" alt="Brunei Darussalam" />
          <p>Brunei Darussalam</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section" id="kontak">
    <h2>Kontak Kami</h2>
    <p>Email: info@inafood.com</p>
    <p>Telepon: +62 343 634835</p>
    <p>Alamat: Jl. Raya Jombor Bawah KM 53, Sukorejo, Pasuruan, Jawa Timur 67161</p>
  </section>

  <footer>
    &copy; 2025 INAFOOD. Seluruh hak cipta dilindungi undang-undang.
  </footer>
</body>
</html>
