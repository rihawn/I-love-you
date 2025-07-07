---
layout: none
title: "Volim te, princezo"
---

<!DOCTYPE html>
<html lang="sr">
<head>
  <meta charset="UTF-8">
  <title>Volim te, princezo</title>
  <style>
    body {
      background-color: #1b1b1b;
      color: white;
      font-family: 'Arial', sans-serif;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    .pixel-heart {
      position: relative;
      width: 140px;
      height: 125px;
      background: red;
      clip-path: polygon(
        35% 0%,
        50% 15%,
        65% 0%,
        100% 35%,
        50% 100%,
        0% 35%
      );
      image-rendering: pixelated;
      box-shadow:
        0 0 0 3px #000,
        2px 2px 0 3px #00000088;
    }

    .text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      font-size: 12px;
      font-weight: bold;
      color: white;
      line-height: 1.2;
    }

    h1 {
      font-family: 'Courier New', monospace;
      font-size: 18px;
      margin-bottom: 20px;
      color: #00ff00;
      text-shadow: 0 0 5px #00ff00;
    }
  </style>
</head>
<body>
  <h1>Minecraft Love</h1>
  <div class="pixel-heart">
    <div class="text">Volim te,<br>princezo</div>
  </div>
</body>
</html>
