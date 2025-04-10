# Nebula.net
Proxy and game unblocker
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nebula</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #000;
      color: #ffa500;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      width: 100%;
      padding: 1rem;
      background-color: #111;
      text-align: center;
      box-shadow: 0 2px 5px rgba(255, 165, 0, 0.2);
    }

    header h1 {
      color: #ffa500;
      font-size: 2.5rem;
    }

    .search-bar {
      margin: 2rem 0;
    }

    input[type="text"] {
      padding: 0.75rem;
      border: none;
      border-radius: 8px;
      width: 300px;
      font-size: 1rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
      padding: 1rem;
      width: 90%;
      max-width: 1000px;
    }

    .tile {
      background-color: #222;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      color: #ffa500;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .tile:hover {
      transform: scale(1.05);
      background-color: #333;
    }

    footer {
      margin-top: auto;
      padding: 1rem;
      text-align: center;
      background-color: #111;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nebula</h1>
  </header>
  <div class="search-bar">
    <input type="text" placeholder="Search games or tools..." />
  </div>
  <div class="grid">
    <div class="tile">Game 1</div>
    <div class="tile">Game 2</div>
    <div class="tile">Game 3</div>
    <div class="tile">Calculator</div>
    <div class="tile">Notepad</div>
    <div class="tile">Game 4</div>
    <div class="tile">Game 5</div>
    <div class="tile">Proxy</div>
    <div class="tile">Weather App</div>
    <div class="tile">Random Tool</div>
  </div>
  <footer>
    <p>&copy; 2025 Nebula. All rights reserved.</p>
  </footer>
</body>
</html>
