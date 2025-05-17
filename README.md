<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CUBIC - Motore di Ricerca</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #0f0f2f, #1a1a40);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #fff;
    }

    .search-container {
      background: rgba(255, 255, 255, 0.05);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 0 25px rgba(0, 255, 255, 0.2);
      text-align: center;
      width: 90%;
      max-width: 600px;
      backdrop-filter: blur(8px);
    }

    .search-container h1 {
      font-size: 32px;
      margin-bottom: 30px;
      letter-spacing: 2px;
      color: #00ffe7;
    }

    .search-box {
      display: flex;
      align-items: center;
      justify-content: center;
    }

    input[type="text"] {
      width: 70%;
      padding: 14px 20px;
      border: none;
      border-radius: 50px 0 0 50px;
      font-size: 18px;
      background-color: rgba(255, 255, 255, 0.1);
      color: #fff;
      outline: none;
    }

    input::placeholder {
      color: #aaa;
    }

    button {
      padding: 14px 25px;
      border: none;
      background: linear-gradient(135deg, #00ffc3, #0077ff);
      color: white;
      font-size: 18px;
      border-radius: 0 50px 50px 0;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: linear-gradient(135deg, #00bfa5, #005fcc);
    }

    .footer {
      margin-top: 20px;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="search-container">
    <h1>CUBIC</h1>
    <form action="https://www.google.com/search" method="GET" target="_blank" class="search-box">
      <input type="text" name="q" placeholder="Cerca su CUBIC..." required />
      <button type="submit">Cerca</button>
    </form>
    <div class="footer">
      Ricerca alimentata da Google
    </div>
  </div>
</body>
</html>
