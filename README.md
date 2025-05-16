<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>To My Girl Crush 💖</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Nunito:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Nunito', sans-serif;
      background: #ffe6eb;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 40px 20px;
      color: #b30059;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      color: #ff4d88;
      margin-bottom: 20px;
    }

    p {
      max-width: 600px;
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .heart {
      font-size: 50px;
      color: #ff4d88;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }

    button {
      background: #ff66a3;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 30px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #e60073;
    }

    .letter {
      display: none;
      background: white;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      margin-top: 30px;
      max-width: 500px;
      color: #800040;
    }

    .show {
      display: block;
    }

    @media (max-width: 600px) {
      h1 { font-size: 2.2rem; }
      p { font-size: 1rem; }
    }
  </style>
</head>
<body>

  <h1>To My Beautiful Girl Crush 💖</h1>
  <div class="heart">❤️</div>
  <p>
    You’re the sparkle in my day, the song in my head, and the reason I smile for no reason.
    I made this little website just for you — because you deserve something beautiful. ✨
  </p>

  <button onclick="document.getElementById('letter').classList.toggle('show')">Read a Secret Letter 💌</button>

  <div id="letter" class="letter">
    <p>
      Hey Rennee!
     🥰,<br><br>
      I don’t know if you’ve noticed, but I really admire you. You’re kind, funny, and effortlessly beautiful. Every time I see you, it makes my day better.<br><br>
      This is just my little way of saying I think you’re wonderful — and maybe, just maybe, I’ve got a bit of a crush on you. 💕<br><br>
      – From someone who thinks you're amazing 💌
    </p>
  </div>

</body>
</html>
