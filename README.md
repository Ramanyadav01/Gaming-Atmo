<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title></title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #0d0d1a;
      color: #fff;
    }
    header {
      background: linear-gradient(to right, #6a00ff, #00c3ff);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
      flex-wrap: wrap;
    }
    header h1 {
      font-size: 1.5rem;
    }
    .search-bar {
      margin-top: 10px;
      flex: 1 1 100%;
      display: flex;
      justify-content: flex-end;
    }
    .search-bar input {
      padding: 8px 12px;
      border-radius: 20px;
      border: none;
      background-color: #d2e4ff;
      color: #000;
      width: 100%;
      max-width: 200px;
    }
    .hero {
      text-align: center;
      padding: 40px 15px;
      background-color: #1a1a2e;
    }
    .hero h2 {
      font-size: 1.8rem;
      color: #00eaff;
    }
    .hero p {
      font-size: 1rem;
      color: #ccc;
      margin-top: 10px;
    }
    .cta-button {
      margin-top: 20px;
      padding: 10px 25px;
      font-size: 1rem;
      background: #00eaff;
      color: #000;
      border: none;
      border-radius: 30px;
      cursor: pointer;
    }
    .games-section {
      display: grid;
      grid-template-columns: 1fr;
      gap: 20px;
      padding: 20px;
    }
    @media (min-width: 600px) {
      .games-section {
        grid-template-columns: repeat(2, 1fr);
      }
    }
    @media (min-width: 900px) {
      .games-section {
        grid-template-columns: repeat(3, 1fr);
      }
    }
    .game-card {
      background: #222233;
      border: 2px solid #6a00ff;
      border-radius: 15px;
      padding: 20px;
      text-align: center;
    }
    .game-card h3 {
      margin-bottom: 10px;
    }
    .game-card p {
      font-size: 0.9rem;
      color: #aaa;
    }
    footer {
      text-align: center;
      padding: 15px;
      font-size: 0.8rem;
      background-color: #0d0d1a;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1></h1>
    <div class="search-bar">
      <input type="text" placeholder="Search games..." />
    </div>
  </header>

  <section class="hero">
    <h2>Play the Coolest Games</h2>
    <p>Dive into action, neon visuals, and thrilling adventures!</p>
    <button class="cta-button">Browse Games</button>
  </section>

  <section class="games-section">
    <div class="game-card">
      <h3>Action Games</h3>
      <p>Show Your Action On Bed</p>
    </div>
    <div class="game-card">
      <h3>Open world Games</h3>
      <p>Open Everything in the World.</p>
    </div>
    <div class="game-card">
      <h3>Shooting Games</h3>
      <p>Shoot with right angle with right position</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Gaming Atmosphere. All rights reserved.
  </footer>
</body>
</html>
