<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gaming Atmosphere</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d0d1a;
      color: #f0f0f0;
    }
    header {
      background: linear-gradient(90deg, #6a00ff, #00c3ff);
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      font-size: 1.8rem;
      color: #ffffff;
    }
    .search-bar {
      margin-top: 10px;
      width: 100%;
    }
    @media(min-width: 600px) {
      .search-bar {
        width: auto;
        margin-top: 0;
      }
    }
    .search-bar input[type="text"] {
      padding: 8px 12px;
      border: none;
      border-radius: 20px;
      outline: none;
      font-size: 1rem;
      background: #d2e4ff;
      color: #000;
      width: 100%;
      max-width: 200px;
    }
    .hero {
      text-align: center;
      padding: 40px 15px;
      background: #1a1a2e;
    }
    .hero h2 {
      font-size: 1.8rem;
      color: #00eaff;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1rem;
      color: #ccc;
    }
    .games-section {
      display: flex;
      flex-direction: column;
      gap: 20px;
      padding: 30px 15px;
    }
    @media(min-width: 600px) {
      .games-section {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
      }
    }
    .game-card {
      background-color: #222233;
      border: 2px solid #6a00ff;
      border-radius: 15px;
      padding: 20px;
      text-align: center;
      width: 100%;
    }
    @media(min-width: 600px) {
      .game-card {
        width: 250px;
      }
    }
    .game-card h3 {
      color: #ffffff;
      margin: 10px 0;
    }
    .game-card p {
      color: #aaaaaa;
      font-size: 0.9rem;
    }
    .cta-button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 25px;
      font-size: 1rem;
      background: #00eaff;
      color: #000;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: 0.3s;
    }
    .cta-button:hover {
      background: #6a00ff;
      color: #fff;
    }
    footer {
      background-color: #0d0d1a;
      text-align: center;
      padding: 15px;
      font-size: 0.8rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gaming Atmosphere</h1>
    <div class="search-bar">
      <input type="text" placeholder="Search games...">
    </div>
  </header>

  <section class="hero">
    <h2>Play the Coolest Games</h2>
    <p>Dive into a world of thrilling action, neon visuals, and epic adventures!</p>
    <a href="#games"><button class="cta-button">Browse Games</button></a>
  </section>

  <section class="games-section" id="games">
    <div class="game-card">
      <h3>Galaxy Racer</h3>
      <p>Race through the stars in a futuristic galaxy arena.</p>
    </div>
    <div class="game-card">
      <h3>Neon Clash</h3>
      <p>Battle with glowing weapons in cyberpunk city streets.</p>
    </div>
    <div class="game-card">
      <h3>Puzzle Glow</h3>
      <p>Relax and solve puzzles under neon light effects.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Gaming Atmosphere. All rights reserved.
  </footer>
</body>
</html>
