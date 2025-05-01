<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tampilan Link dengan Foto</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom right, #1e90ff, #00ced1);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: start;
      height: 100vh;
      padding-top: 100px;
    }

    .circle {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      overflow: hidden;
      border: 3px solid #000;
      margin-bottom: 40px;
    }

    .circle img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .button {
      width: 300px;
      padding: 20px;
      margin: 10px 0;
      background: linear-gradient(to right, #4169e1, #00ced1);
      border: 2px solid #000;
      border-radius: 15px;
      color: white;
      font-size: 18px;
      font-weight: bold;
      text-align: center;
      text-decoration: none;
      box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.3);
      transition: transform 0.2s;
      display: block;
    }

    .button:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <!-- Ganti URL gambar di src dengan tautan gambar kamu -->
  <div class="circle">
    <img src="https://i.postimg.cc/cHB8pF9N/bcef2017f4a8db83d1eb13d5067b60dc.jpg" alt="Foto Profil">
  </div>
  
  <!-- Tulisan di bawah foto -->
  <div class="caption">WAHYU ANAK BAIK</div>

  <a href="https://whatsapp.com/channel/0029Vb5kqefDzgT7qg5q8A1f" class="button">Link Saluran</a>
  <a href="https://www.tiktok.com/@wahyuks399?_t=ZS-8w095Ok22EM&_r=1" class="button">Tiktok</a>
  <a href="https://www.instagram.com/wahyuks399?igsh=MXh3Z3FnamJoaWRiMw==" class="button">Instagram</a>
  <a href="https://www.tiktok.com/@manusi4.biasa_?_t=ZS-8w0BJFbUGTC&_r=1" class="button">Akun Tiktok Pertama</a>
  <a href="https://wa.me/62882008855215" class="button">wa atmin“</a>

</body>
</html>