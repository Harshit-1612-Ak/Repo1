<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Anniversary, Akankshya!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle, #ffe0e9, #ffb3c6);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      color: #fff;
    }

    .card {
      background: rgba(255, 105, 180, 0.9);
      padding: 40px;
      border-radius: 25px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
      text-align: center;
      animation: slideIn 2s ease-out;
    }

    h1 {
      font-size: 2.8em;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.5em;
      margin: 10px 0;
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .hearts {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      z-index: -1;
    }

    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: pink;
      transform: rotate(45deg);
      animation: floatUp 8s linear infinite;
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: pink;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes floatUp {
      0% {
        bottom: -10%;
        opacity: 1;
      }
      100% {
        bottom: 100%;
        left: calc(100% * var(--x));
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <div class="hearts">
    <!-- Random floating hearts -->
    <script>
      for (let i = 0; i < 30; i++) {
        let heart = document.createElement("div");
        heart.className = "heart";
        heart.style.left = Math.random() * 100 + "%";
        heart.style.animationDuration = 5 + Math.random() * 5 + "s";
        heart.style.setProperty('--x', Math.random());
        document.body.appendChild(heart);
      }
    </script>
  </div>

  <div class="card">
    <h1>Happy 143 Days, Akankshya!</h1>
    <p>Every moment with you has been magical.</p>
    <p>Here’s to our 143 days of love, laughter, and memories!</p>
    <p>Looking forward to a forever with you.</p>
    <p>With love, always.</p>
  </div>
</body>
</html>
