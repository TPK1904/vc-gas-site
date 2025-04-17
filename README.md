<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VC GAS - Marcas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ff6600;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .intro-title {
      text-align: center;
      font-size: 36px;
      font-weight: bold;
      margin-top: 40px;
      color: #333;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 30px;
      gap: 20px;
    }
    .brand-card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 200px;
      text-align: center;
      padding: 20px;
      transition: transform 0.2s;
    }
    .brand-card:hover {
      transform: scale(1.05);
    }
    .brand-card a {
      text-decoration: none;
      color: #ff6600;
      font-weight: bold;
      font-size: 18px;
    }
    .options {
      text-align: center;
      margin-top: 50px;
    }
    .options a {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      background-color: #ff6600;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    .options a:hover {
      background-color: #cc5200;
    }
  </style>
</head>
<body>
  <header>
    <h1>VC GÁS</h1>
    <p>Morada: São Pedro de Martins - Cascais</p>
    <p>Horário: 8:00 - 12:00 / 14:00 - 18:00</p>
    <p>Contacto: 935 432 562 / 214 765 835</p>
  </header>

  <div class="intro-title">Escolhe a tua marca de gás</div>

  <div class="container">
    <div class="brand-card">
      <a href="marca.html?marca=cepsa">
        <img src="cepsa.png">
        <div>Cepsa</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=prio">
        <img src="prio.png">
        <div>Prio</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=galp">
        <img src="galp.jpg">
        <div>Galp</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=rubis-gas">
      <img src="rubis.png">
    <div>Rubis Gas</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=repsol">
        <img src="repsol.jpg">
        <div>Repsol</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=ozenergia">
        <img src="Ozenergia.png">
        <div>OZenergia</div>
      </a>
    </div>
    <div class="brand-card">
      <a href="marca.html?marca=tutigas">
        <img src="tutigas.jpg">
        <div>Tutigas</div>
      </a>
    </div>
  </div>
  

