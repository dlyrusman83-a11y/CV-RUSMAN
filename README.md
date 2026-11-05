
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV Pelajar</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #061a12;
  color: #e8fff0;
  padding: 25px;
}

.cv {
  max-width: 750px;
  margin: auto;
  padding: 35px;
  background: #10271d;
  border: 1px solid #245c40;
  border-radius: 20px;
  box-shadow: 0 0 35px #00ff6630;
  animation: muncul 1s ease;
}

header {
  text-align: center;
  padding-bottom: 25px;
  border-bottom: 1px solid #356b4d;
}

.foto {
  width: 100px;
  height: 100px;
  margin: auto auto 15px;
  border-radius: 50%;
  border: 3px solid #4ade80;
  background: #1c4932;
  display: grid;
  place-items: center;
  font-size: 40px;
}

h1 {
  color: #86efac;
  font-size: 30px;
}

header p {
  color: #b6d9c2;
  margin-top: 8px;
}

section {
  margin-top: 25px;
}

h2 {
  color: #4ade80;
  font-size: 18px;
  margin-bottom: 12px;
}

p, li {
  color: #d1e7d8;
  line-height: 1.8;
}

ul {
  padding-left: 20px;
}

.info {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}

.info div {
  background: #193b2a;
  padding: 12px;
  border-radius: 10px;
}

footer {
  margin-top: 30px;
  text-align: center;
  color: #86efac;
  font-size: 13px;
}

@keyframes muncul {
  from {
    opacity: 0;
    transform: translateY(25px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@media (max-width: 500px) {
  body { padding: 12px; }
  .cv { padding: 22px; }
  .info { grid-template-columns: 1fr; }
}
</style>
</head>

<body>
<div class="cv">

<header>
  <div class="foto">🎓</div>
  <h1>RUSMAN DLY</h1>
  <p>Curriculum Vitae | Pelajar</p>
</header>

<section>
  <h2>👤 Data Diri</h2>
  <div class="info">
    <div>Nama: RUSMAN DLY</div>
    <div>Kelas: XII</div>
    <div>Jurusan: TKJ</div>
    <div>Sekolah: Smk N 2 Panyabungan</div>
    <div>Tempat,Tgl.L:Sukamakmur:18-8-2008</div>
    <div>Alamat: Sukamakmur</div>
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
    <li>Menonton Donghua/Drama</li>
    <li>Belajar hal baru yang saya sukai</li>
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

<footer>
  CV Pelajar • 2026
</footer>

</div>
</body>
</html>
