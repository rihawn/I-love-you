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
      margin: 0;
      height: 100vh;
      background: linear-gradient(to bottom right, #8e44ad, #c0392b);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Segoe UI", sans-serif;
    }

    .heart {
      position: relative;
      width: 200px;
      height: 180px;
      background: red;
      transform: rotate(-45deg);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 200px;
      height: 180px;
      background: red;
      border-radius: 50%;
    }

    .heart::before {
      top: -100px;
      left: 0;
    }

    .heart::after {
      left: 100px;
      top: 0;
    }

    .text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) rotate(45deg);
      color: white;
      font-size: 16px;
      text-align: center;
      width: 120px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="heart">
    <div class="text">Volim te,<br>princezo</div>
  </div>
</body>
</html>
