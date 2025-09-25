<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Arunika 🎉</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(270deg, #ff9a9e, #fad0c4, #fbc2eb, #a1c4fd, #c2e9fb);
      background-size: 1000% 1000%;
      animation: gradientBG 20s ease infinite;
      overflow: hidden;
      color: white;
      text-align: center;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    h1 {
      font-size: 3em;
      animation: fadeInUp 2s ease forwards;
    }

    p {
      font-size: 1.5em;
      opacity: 0;
      animation: fadeInUp 3s ease forwards 2s;
    }

    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    .balloon {
      position: absolute;
      bottom: -150px;
      width: 80px;
      height: 100px;
      background: radial-gradient(circle at 30% 30%, #fff, #ff4081);
      border-radius: 50%;
      animation: float 6s ease-in-out infinite;
    }

    .balloon:nth-child(2) {
      left: 20%;
      background: radial-gradient(circle at 30% 30%, #fff, #2196f3);
      animation-duration: 7s;
    }
    .balloon:nth-child(3) {
      left: 50%;
      background: radial-gradient(circle at 30% 30%, #fff, #4caf50);
      animation-duration: 5s;
    }
    .balloon:nth-child(4) {
      left: 75%;
      background: radial-gradient(circle at 30% 30%, #fff, #ff9800);
      animation-duration: 8s;
    }

    @keyframes float {
      0% { transform: translateY(0); opacity: 0; }
      20% { opacity: 1; }
      100% { transform: translateY(-120vh); opacity: 0; }
    }
  </style>
</head>
<body>
  <div>
    <h1>🎂 Happy Birthday, Arunika! 🎂</h1>
    <p>Semoga harimu penuh warna, kebahagiaan, dan cinta 💖</p>
  </div>

  <!-- Balon animasi -->
  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>

  <!-- Musik latar -->
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" type="audio/mpeg">
    Browsermu tidak mendukung audio.
  </audio>
</body>
</html>
