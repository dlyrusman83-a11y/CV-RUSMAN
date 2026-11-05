
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV Rusman Dly</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #031b12;
  color: #e4f5ec;
  line-height: 1.7;
  padding: 20px;
}

.container {
  max-width: 800px;
  margin: auto;
  background: #09251a;
  border: 1px solid #245b42;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 10px 35px #0005;
}

header {
  text-align: center;
  padding: 35px 20px;
  background: linear-gradient(135deg, #0d3927, #071e15);
  border-bottom: 1px solid #245b42;
}

.foto {
  width: 125px;
  height: 125px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #53e69b;
  margin-bottom: 15px;
}

h1 {
  color: #53e69b;
  font-size: clamp(25px, 6vw, 36px);
  overflow-wrap: anywhere;
}

header p {
  color: #b6d8c6;
  margin-top: 5px;
}

main {
  padding: 25px;
}

section {
  margin-bottom: 30px;
}

h2 {
  color: #53e69b;
  font-size: 23px;
  margin-bottom: 15px;
  border-bottom: 1px solid #245b42;
  padding-bottom: 8px;
}

.data {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 10px;
}

.item {
  background: #143d2b;
  border: 1px solid #245b42;
  border-radius: 10px;
  padding: 12px;
  overflow-wrap: anywhere;
}

.item strong {
  display: block;
  color: #53e69b;
  font-size: 14px;
  margin-bottom: 4px;
}

p, li {
  overflow-wrap: anywhere;
}

ul {
  padding-left: 25px;
}

li {
  margin-bottom: 8px;
}

footer {
  text-align: center;
  padding: 20px;
  color: #8bb9a0;
  border-top: 1px solid #245b42;
  font-size: 13px;
}

@media (max-width: 480px) {
  body {
    padding: 12px;
  }

  main {
    padding: 18px;
  }

  .data {
    grid-template-columns: 1fr;
  }

  h2 {
    font-size: 21px;
  }
}
</style>
</head>

<body>
<div class="container">

<header>
  <img src="foto.jpg" alt="Foto Rusman Dly" class="foto">

  <h1>RUSMAN DLY</h1>
  <p>Curriculum Vitae | Pelajar</p>
</header>

<main>

<section>
  <h2>👤 Data Diri</h2>

  <div class="data">
    <div class="item">
      <strong>Nama</strong>
      Rusman Dly
    </div>

    <div class="item">
      <strong>Kelas</strong>
      XII
    </div>

    <div class="item">
      <strong>Jurusan</strong>
      Teknik Komputer dan Jaringan (TKJ)
    </div>

    <div class="item">
      <strong>Sekolah</strong>
      SMK Negeri 2 Panyabungan
    </div>

    <div class="item">
      <strong>Tempat, Tanggal Lahir</strong>
      Sukamakmur, 18 Agustus 2008
    </div>

    <div class="item">
      <strong>Alamat</strong>
      Sukamakmur
    </div>
  </div>
</section>

<section>
  <h2>🎒 Tentang Saya</h2>
  <p>
    Saya adalah seorang pelajar yang memiliki semangat
    belajar tinggi, bertanggung jawab, dan senang
    mengembangkan kemampuan diri.
  </p>
</section>

<section>
  <h2>⭐ Hobi</h2>
  <ul>
    <li>Olahraga</li>
    <li>Menonton donghua dan drama</li>
    <li>Memancing</li>
    <li>Belajar Hal Baru Yang Saya Sukai</li>
  </ul>
</section>

<section>
  <h2>💡 Kemampuan</h2>
  <ul>
    <li>Mampu bekerja sama dalam kelompok</li>
    <li>Disiplin dan bertanggung jawab</li>
    <li>Mengoperasikan komputer</li>
  </ul>
</section>

</main>

<footer>
  Curriculum Vitae — Rusman Dly
</footer>

</div>
</body>
</html>
