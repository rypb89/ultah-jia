# ultah-jia
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Selamat Ulang Tahun, Jia!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
      text-align: center;
      overflow: hidden;
    }
    h1 {
      font-size: 3em;
      margin-top: 50px;
    }
    p {
      font-size: 1.5em;
      max-width: 90%;
      margin: 20px auto;
    }
    .heart {
      position: absolute;
      width: 100px;
      height: 90px;
      background-color: red;
      transform: rotate(-45deg);
      animation: float 6s infinite ease-in-out;
    }
    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 100px;
      height: 90px;
      background-color: red;
      border-radius: 50%;
    }
    .heart::before {
      top: -50px;
      left: 0;
    }
    .heart::after {
      left: 50px;
      top: 0;
    }
    @keyframes float {
      0% { transform: translateY(0) rotate(-45deg); }
      50% { transform: translateY(-20px) rotate(-45deg); }
      100% { transform: translateY(0) rotate(-45deg); }
    }
    audio {
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <h1>Selamat Ulang Tahun, Jia! 🎉</h1>
  <p>
    Makasih udah bertahan sampai sekarang.<br>
    Syarif bangga sama kamu.<br>
    Di hari spesial ini, semoga kamu sadar akan usia dan tanggung jawabmu.<br>
    Tak apa banyak ujian sekarang, Syarif yakin kamu bisa lewatin semuanya.<br>
    Jaga kesehatan yaa. Semoga hari-harimu selalu bahagia.<br>
    Kamu sangat spesial dan berharga buatku. Tetap bareng-bareng terus yaa.<br>
    Dari Sasa yang sayang banget sama kamu 💖
  </p>
  <audio controls autoplay loop>
    <source src="ultah_video_final.mp3" type="audio/mp3">
    Browser kamu tidak mendukung audio.
  </audio>

  <div class="heart" style="top: 20%; left: 10%;"></div>
  <div class="heart" style="top: 50%; left: 80%; animation-delay: 1s;"></div>
  <div class="heart" style="top: 70%; left: 30%; animation-delay: 2s;"></div>
</body>
</html>
