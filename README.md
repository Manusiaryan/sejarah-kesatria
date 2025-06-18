<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sejarah Ksatria Dunia</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px 40px;
      text-align: center;
    }
    main {
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }
    section {
      background-color: #fff;
      margin-bottom: 40px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    section img {
      max-width: 100%;
      border-radius: 6px;
      margin-top: 10px;
    }
    h2 {
      color: #2e3b4e;
    }
    .interactive {
      background-color: #e3f2fd;
      padding: 20px;
      border-radius: 8px;
    }
    .interactive h3 {
      margin-top: 0;
    }
    input, select {
      padding: 8px;
      margin: 10px 0;
      width: 100%;
      box-sizing: border-box;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sejarah Ksatria dari Berbagai Negara</h1>
    <p>Menelusuri jejak para pejuang pemberani dari seluruh penjuru dunia dan era yang berbeda</p>
  </header>
  <main>
    <section>
      <h2>1. Ksatria Eropa – Abad Pertengahan & Renaisans</h2>
      <p>Ksatria Eropa berasal dari era Abad Pertengahan dan Renaisans, terutama antara abad ke-9 hingga ke-16. Mereka menggunakan zirah mulai dari chainmail hingga full plate armor. Senjata utama berupa pedang, tombak, dan panah. Kuda perang disebut destrier yang dilengkapi armor pelindung.</p>
      <img src="https://cdn.pixabay.com/photo/2015/10/31/12/39/armor-1015238_1280.jpg" alt="Ksatria Eropa" />
    </section>

    <section>
      <h2>2. Samurai Jepang</h2>
      <p>Samurai adalah prajurit elit Jepang yang hidup dari abad ke-12 hingga 19. Mereka memegang kode Bushidō yang menjunjung tinggi kesetiaan, kehormatan, dan keberanian. Zirah samurai terdiri dari lamellar armor, katana, wakizashi, serta helm kabuto. Mereka juga mengikuti ritual spiritual seperti seppuku.</p>
      <img src="https://cdn.pixabay.com/photo/2018/04/15/16/32/samurai-3325984_1280.jpg" alt="Samurai Jepang" />
    </section>

    <section>
      <h2>3. Mamluk Mesir</h2>
      <p>Mamluk adalah budak militer yang menjadi penguasa Mesir dari abad ke-13 hingga 16. Mereka dibeli dari Asia Tengah, dilatih secara militer, dan menjadi pemimpin elit. Mereka memenangkan pertempuran melawan Mongol di Ain Jalut (1260) dan dikenal dengan peralatan militer yang elegan dan fungsional.</p>
      <img src="https://cdn.pixabay.com/photo/2019/10/21/11/18/arabian-4564469_1280.jpg" alt="Mamluk Mesir" />
    </section>

    <section>
      <h2>4. Prajurit Zulu</h2>
      <p>Pasukan Zulu dibentuk oleh Shaka Zulu pada abad ke-19. Mereka menggunakan formasi "buffalo horns" untuk mengepung musuh dan menggunakan iklwa (tombak pendek) untuk pertempuran jarak dekat. Pelatihan fisik mereka sangat keras dan efektif dalam memperluas wilayah Zulu.</p>
      <img src="https://cdn.pixabay.com/photo/2022/07/17/07/39/zulu-7326089_1280.jpg" alt="Prajurit Zulu" />
    </section>

    <section>
      <h2>5. Ksatria Mongolia</h2>
      <p>Di bawah pimpinan Genghis Khan, pasukan berkuda Mongolia menguasai wilayah luas pada abad ke-13. Mereka mengandalkan mobilitas tinggi, pemanah berkuda, dan strategi serangan kilat. Mereka terkenal karena disiplin tinggi dan jaringan komunikasi yang luas.</p>
      <img src="https://cdn.pixabay.com/photo/2016/04/07/18/10/horseman-1314141_1280.jpg" alt="Prajurit Mongolia" />
    </section>

    <section class="interactive">
      <h3>Eksplorasi Interaktif</h3>
      <label for="filter">Filter Berdasarkan Negara/Asal:</label>
      <select id="filter">
        <option>Semua</option>
        <option>Europa</option>
        <option>Jepang</option>
        <option>Mesir</option>
        <option>Afrika</option>
        <option>Mongolia</option>
      </select>

      <label for="search">Cari Ksatria:</label>
      <input type="text" id="search" placeholder="Contoh: Samurai, Knight..." />

      <label for="timeline">Pilih Era:</label>
      <input type="range" id="timeline" min="900" max="1900" step="100" />
    </section>
