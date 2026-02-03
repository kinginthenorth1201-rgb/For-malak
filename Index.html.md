<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>  
  <title>For Malak ❤️</title>  
  
  <!-- Google Fonts -->  
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">  
  
  <style>  
    body {  
      margin: 0;  
      font-family: 'Playfair Display', serif;  
      background: linear-gradient(to bottom, #fff0f5, #fde2e4);  
      color: #4a2c2a;  
      text-align: center;  
      overflow-x: hidden;  
    }  
  
    .container {  
      max-width: 800px;  
      margin: auto;  
      padding: 80px 20px;  
      position: relative;  
      z-index: 2;  
    }  
  
    h1 {  
      font-family: 'Great Vibes', cursive;  
      font-size: 4rem;  
      color: #c9184a;  
      margin-bottom: 10px;  
      animation: fadeIn 2s ease;  
    }  
  
    h2 {  
      font-size: 1.4rem;  
      font-weight: 400;  
      margin-bottom: 40px;  
      animation: fadeIn 3s ease;  
    }  
  
    p {  
      font-size: 1.2rem;  
      line-height: 1.8;  
      margin-bottom: 25px;  
      animation: fadeIn 4s ease;  
    }  
  
    .flowers {  
      margin-top: 40px;  
      font-size: 2.2rem;  
      animation: fadeIn 5s ease;  
    }  
  
    footer {  
      margin-top: 70px;  
      font-size: 0.9rem;  
      opacity: 0.7;  
      animation: fadeIn 6s ease;  
    }  
  
    /* Floating hearts */  
    .heart {  
      position: fixed;  
      bottom: -20px;  
      font-size: 1.5rem;  
      animation: floatUp linear infinite;  
      opacity: 0.8;  
    }  
  
    @keyframes floatUp {  
      from {  
        transform: translateY(0);  
        opacity: 1;  
      }  
      to {  
        transform: translateY(-110vh);  
        opacity: 0;  
      }  
    }  
  
    @keyframes fadeIn {  
      from { opacity: 0; transform: translateY(10px); }  
      to { opacity: 1; transform: translateY(0); }  
    }  
  </style>  
</head>  
<body>  
  
  <div class="container">  
    <h1>Malak</h1>  
    <h2>My heart chose you 🤍</h2>  
  
    <p>  
      In a world that never slows down,<br>  
      you are my calm, my peace, my home.  
    </p>  
  
    <p>  
      Every smile of yours softens my days,<br>  
      every word from you stays with me longer than time.  
    </p>  
  
    <p>  
      This page is simple,<br>  
      but my love for you is endless.  
    </p>  
  
    <div class="flowers">🌸 🌷 🌹 🌺</div>  
  
    <footer>  
      Forever yours ❤️  
    </footer>  
  </div>  
  
  <!-- Floating hearts generator -->  
  <script>  
    function createHeart() {  
      const heart = document.createElement("div");  
      heart.classList.add("heart");  
      heart.innerHTML = "❤️";  
      heart.style.left = Math.random() * 100 + "vw";  
      heart.style.animationDuration = (3 + Math.random() * 4) + "s";  
      document.body.appendChild(heart);  
  
      setTimeout(() => {  
        heart.remove();  
      }, 7000);  
    }  
  
    setInterval(createHeart, 400);  
  </script>  
  
</body>  
</html>  
