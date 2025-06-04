<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portofolio - Rhosa Thatia Anista</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #ffe4ec;
      color: #4a004d;
    }

    header {
      background: #ff9acb;
      padding: 1.5rem 2rem;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 2.5rem;
      color: white;
      letter-spacing: 2px;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #4a004d;
    }

    .hero {
      padding: 3rem 2rem;
      text-align: center;
      background: linear-gradient(to right, #ffc1da, #ffe4ec);
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.1rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .projects {
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: white;
      border-radius: 15px;
      padding: 1.5rem;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      color: #ff5ca1;
      margin-bottom: 0.5rem;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #ff9acb;
      color: white;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      .hero h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Portofolio Saya</h1>
    <nav>
      <a href="#tentang">Tentang</a>
      <a href="#proyek">Proyek</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <section class="hero" id="tentang">
    <h2>Hai, saya Rhosa Thatia Anista 👋</h2>
    <p>Seorang Mahasiswa di Universitas Lampung</p>
  </section>

  <section class="projects" id="proyek">
    <div class="card">
      <h3>Proyek 1</h3>
      <p>Tugas Tokoh Grafika Komputer</p>
      <p><strong>Link Video:</strong> 
        <a href="https://drive.google.com/file/d/1XkTPW2UbQEzGfr-AMVpR-_45DLIu4kIb/view?usp=drivesdk" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
      </p>
      <p><strong>Dokumen PDF:</strong> 
        <a href="dokumen/tugas1_tokoh.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
      </p>
    </div>
    <div class="card">
      <h3>Proyek 2</h3>
      <p>Tugas Algoritma Garis</p>
      <p><strong>Link Video:</strong> 
        <a href=" https://drive.google.com/drive/folders/1blDj9ShWzNiqAxA76qEX7hMqSgaHwPrn" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
      </p>
      <p><strong>Dokumen PDF:</strong> 
        <a href="dokumen/algoritma_garis.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
      </p>
    </div>
    <div class="card">
      <h3>Proyek 3</h3>
      <p>Tugas Algoritma Lingkaran</p>
      <p><strong>Link Video:</strong> 
        <a href=" https://drive.google.com/file/d/1bFB8KHFVcwSmJbB0Je74qDn3rCvMjzZ2/view?usp=sharing" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
      </p>
      <p><strong>Dokumen PDF:</strong> 
        <a href="dokumen/algoritma_lingkaran.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
      </p>
    </div>
    <div class="card">
      <h3>Proyek 4</h3>
      <p>Tugas Algoritma Kurva</p>
      <p><strong>Link Video:</strong> 
        <a href="https://drive.google.com/file/d/1AsY_1AP-8PUqU2KMxrRpb9W7nZT1vH-I/view?usp=sharing" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
      </p>
      <p><strong>Dokumen PDF:</strong> 
        <a href="dokumen/algoritma_kurva.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
      </p>
    </div>
     <div class="card">
  <h3>Proyek 5</h3>
  <p>Kuis 1 - Persamaan Misteri</p>
  <p><strong>Dokumen PDF:</strong> 
    <a href="dokumen/Kuis1_PersamaanMisteri.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
  </p>
</div>

<div class="card">
  <h3>Proyek 6</h3>
  <p>Tugas Transformasi 2D</p>
  <p><strong>Link Video:</strong> 
    <a href=" https://drive.google.com/file/d/1Z3HD7bMcIc4HB34pdGSZJxZ0sPVE9Yf4/view?usp=drive_link
" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
  </p>
  <p><strong>Dokumen PDF:</strong> 
    <a href="dokumen/Kuis2_transformasi2d.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
  </p>
   <p><strong>Spreadsheet:</strong> 
    <a href="https://docs.google.com/spreadsheets/d/1hUWhcExJkQ9zyy__idtgLU53PvWPRhjwfJEM9fEPIa8/edit?usp=sharing" target="_blank" style="color:#ffdd00;">Lihat Spreadsheet</a>
  </p>
</div>

<div class="card">
  <h3>Proyek 7</h3>
  <p>Tugas Line clipping</p>
  <p><strong>Link Video:</strong> 
    <a href=" https://drive.google.com/file/d/1TZwzXGlAInzdxvUTxZP0gioQAUCaFBO6/view?usp=sharing
" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
  </p>
  <p><strong>Dokumen PDF:</strong> 
    <a href="dokumen/Kuis3_lineclipping.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
  </p>
  <p><strong>Spreadsheet:</strong> 
    <a href="https://docs.google.com/spreadsheets/d/1PfbgILQ6gI8cnAnp9BoD5X7PSJ_lnRxMFT6pjMK5Fjg/edit?usp=sharing
" target="_blank" style="color:#ffdd00;">Lihat Spreadsheet</a>
  </p>
</div>

<div class="card">
  <h3>Proyek 8</h3>
  <p>Tugas Polygon clipping</p>
  <p><strong>Link Video:</strong> 
    <a href="https://drive.google.com/file/d/your_link_uas/view?usp=sharing" target="_blank" style="color:#ffdd00;">Lihat Video Drive</a>
  </p>
  <p><strong>Dokumen PDF:</strong> 
    <a href="dokumen/Kuis4_polygonclipping.pdf" target="_blank" style="color:#ffdd00;">Lihat PDF</a>
  </p>
</div>

  </section>

  <footer id="kontak">
    <p>Hubungi saya di @rhosathatiaanista@gmail.com | Tiktok :imrosse </p>
  </footer>

</body>
</html>
