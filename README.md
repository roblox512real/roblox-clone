<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Roblox Clone - Découvrir</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #e7e7e7;
      display: flex;
    }

    /* Sidebar */
    .sidebar {
      width: 200px;
      background-color: #232527;
      color: white;
      height: 100vh;
      padding: 20px 0;
    }

    .sidebar h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 20px;
    }

    .sidebar a {
      display: block;
      padding: 12px 20px;
      color: white;
      text-decoration: none;
    }

    .sidebar a:hover {
      background-color: #393b3d;
    }

    /* Main content */
    .main {
      flex: 1;
      padding: 20px;
    }

    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .game-card {
      background-color: white;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }

    .game-card:hover {
      transform: translateY(-4px);
    }

    .game-card img {
      width: 100%;
      height: 120px;
      object-fit: cover;
    }

    .game-card h3 {
      font-size: 16px;
      margin: 10px;
    }

    .game-card button {
      margin: 10px;
      padding: 8px 12px;
      background-color: #00b06e;
      border: none;
      border-radius: 4px;
      color: white;
      cursor: pointer;
    }

    .game-card button:hover {
      background-color: #008f5a;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <h2>BloxxSite</h2>
    <a href="#">🏠 Accueil</a>
    <a href="#">🎮 Jeux</a>
    <a href="#">🧍 Avatar</a>
    <a href="#">⚙️ Paramètres</a>
  </div>

  <div class="main">
    <h1>Découvrir des jeux</h1>
    <div class="game-grid">
      <!-- Jeu 1 -->
      <div class="game-card">
        <img src="https://tr.rbxcdn.com/ab1efb6f6546e24ae1d29b9ae508f348/420/420/GameThumbnail.jpg" alt="Brookhaven">
        <h3>Brookhaven 🏡RP</h3>
        <a href="https://www.roblox.com/games/4924922222/Brookhaven-RP" target="_blank">
          <button>Jouer</button>
        </a>
      </div>

      <!-- Jeu 2 -->
      <div class="game-card">
        <img src="https://tr.rbxcdn.com/9efdd0c5b7a3fd0f4d301a243aa57a46/420/420/GameThumbnail.jpg" alt="Blox Fruits">
        <h3>Blox Fruits</h3>
        <a href="https://www.roblox.com/games/2753915549/Blox-Fruits" target="_blank">
          <button>Jouer</button>
        </a>
      </div>

      <!-- Jeu 3 -->
      <div class="game-card">
        <img src="https://tr.rbxcdn.com/f3d6581c01c83f5eb5a33e8f4df9e786/420/420/GameThumbnail.jpg" alt="Doors">
        <h3>DOORS 🚪</h3>
        <a href="https://www.roblox.com/games/6516141723/DOORS" target="_blank">
          <button>Jouer</button>
        </a>
      </div>
    </div>
  </div>
</body>
</html>
