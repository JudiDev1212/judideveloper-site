# judideveloper-site<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JudiDeveloper</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background: linear-gradient(120deg, #0f0f0f, #1c1c1c);
      color: #f2f2f2;
      line-height: 1.6;
    }
    header {
      background-color: #121212;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }
    header h1 {
      font-size: 28px;
      color: #00ffff;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #f2f2f2;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #00ffff;
    }
    .section {
      padding: 60px 40px;
    }
    .hero {
      text-align: center;
    }
    .hero img {
      max-width: 200px;
      margin-bottom: 20px;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 18px;
      color: #ccc;
    }
    .about {
      background-color: #1a1a1a;
      border-top: 2px solid #00ffff;
    }
    .about h2 {
      font-size: 28px;
      margin-bottom: 15px;
      color: #00ffff;
    }
    .about p {
      max-width: 800px;
      margin: auto;
      font-size: 16px;
      color: #ddd;
    }
    .discord {
      text-align: center;
      margin-top: 30px;
    }
    .discord a {
      background-color: #5865F2;
      color: white;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      margin-top: 10px;
      transition: background-color 0.3s;
    }
    .discord a:hover {
      background-color: #4752c4;
    }
    .scripts {
      background-color: #121212;
      padding: 60px 40px;
      border-top: 2px solid #00ffff;
    }
    .scripts h2 {
      font-size: 28px;
      margin-bottom: 20px;
      text-align: center;
      color: #00ffff;
    }
    .script-item {
      background-color: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.5);
      transition: transform 0.2s;
    }
    .script-item:hover {
      transform: translateY(-5px);
    }
    .script-item h3 {
      color: #00ff99;
      margin-bottom: 10px;
    }
    .script-item p {
      color: #ccc;
    }
    .script-item a {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 16px;
      background-color: #00ffff;
      color: #121212;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    .script-item a:hover {
      background-color: #00bbbb;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #888;
      background-color: #121212;
    }
  </style>
</head>
<body>
  <header>
    <h1>JudiDeveloper</h1>
    <nav>
      <a href="#">Ana Sayfa</a>
      <a href="#about">Hakkımda</a>
      <a href="#scripts">Scriptler</a>
    </nav>
  </header>

  <section class="section hero">
    <img src="/mnt/data/Judi.png" alt="JudiDeveloper Logo">
    <h2>FiveM Script Geliştirme ve Paylaşım Platformu</h2>
    <p>Özel sistemler, performanslı scriptler ve developer çözümleri için doğru yerdesin.</p>
    <div class="discord">
      <p>Topluluğumuza katıl:</p>
      <a href="https://discord.gg/qe3hUBvN" target="_blank">Discord Sunucuma Katıl</a>
    </div>
  </section>

  <section class="section about" id="about">
    <h2>Hakkımda</h2>
    <p>
      Merhaba! Ben JudiDeveloper. Uzun süredir FiveM için özel scriptler geliştiriyorum. Amacım, hem kendi projelerimde kullanabileceğim performanslı sistemler üretmek hem de topluluğa katkı sağlamak. Bu sitede, kendi yazdığım scriptleri tanıtacak ve isteyenlerle paylaşacağım.
    </p>
  </section>

  <section class="scripts" id="scripts">
    <h2>Scriptler</h2>

    <div class="script-item">
      <h3>QBCore Sistemleri</h3>
      <p>Özelleştirilmiş QBCore scriptleri: görev sistemleri, market, polis sistemi, banka, telefon modülü ve çok daha fazlası.</p>
      <a href="#">Demo İndir</a>
    </div>

    <div class="script-item">
      <h3>Lua Scriptleri</h3>
      <p>Temiz ve optimize edilmiş Lua kodları ile sunucunuza özel sistemler geliştirin. Event sistemleri, UI entegrasyonları, trigger yapıları ve performanslı çözümler.</p>
      <a href="#">Detaylı Bilgi</a>
    </div>

    <div class="script-item">
      <h3>Discord Botları</h3>
      <p>Rol verme, whitelist kontrolü, sunucu logları ve entegrasyon sistemleri ile özel Discord botları.</p>
      <a href="#">GitHub Repo</a>
    </div>
  </section>

  <footer>
    © 2025 JudiDeveloper | Tüm Hakları Saklıdır
  </footer>
</body>
</html>
