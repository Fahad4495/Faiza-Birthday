<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Faiza!</title>
  <style>
    body {
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 40px;
      overflow-x: hidden;
      animation: backgroundShift 10s infinite alternate;
    }

    @keyframes backgroundShift {
      0% { background-position: left; }
      100% { background-position: right; }
    }

    .card {
      background: rgba(255, 255, 255, 0.95);
      border-radius: 20px;
      padding: 40px;
      margin: auto;
      max-width: 700px;
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
      animation: popIn 1s ease-out;
    }

    @keyframes popIn {
      0% { transform: scale(0.8); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }

    h1 {
      font-size: 3rem;
      color: #ff69b4;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.5rem;
      color: #333;
    }

    .anime-nurse {
      margin: 30px 0;
    }

    .anime-nurse img {
      width: 250px;
      border-radius: 15px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <div class="card">
    <h1>Happy Birthday, Faiza!</h1>
    <div class="anime-nurse">
      <img src="https://media.tenor.com/1vxR-jEYT7MAAAAi/anime-nurse.gif" alt="Cute Anime Nurse" />
    </div>
    <p>Sending you warm wishes, smiles, and a nurse's touch of kindness!</p>
    <p>May this year bring you lots of love, health, and sweet memories!</p>
  </div>
</body>
</html>
