<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Minecraft Server</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0e0e0e;
      color: #fff;
    }
    header {
      background: url('https://i.imgur.com/0rVx1bF.jpeg') center/cover no-repeat;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      text-shadow: 3px 3px 8px #000;
    }
    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.4);
      margin-bottom: 20px;
    }
    .ip-box {
      background: #222;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      font-size: 1.2rem;
      margin-top: 10px;
      border: 1px solid #555;
      user-select: all;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      margin-top: 20px;
    }
    /* Smooth fade-in animation */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Smooth floating header text */
    @keyframes floatText {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    body {
      animation: fadeIn 1s ease-in-out;
    }

    header h1 {
      animation: floatText 4s ease-in-out infinite;
    }

    .card {
      animation: fadeIn 1.2s ease-in-out;
    }

      /* Smooth page transition */
    .fade-page {
      opacity: 0;
      transition: opacity 0.8s ease;
    }

    body.fade-in {
      opacity: 1 !important;
      transition: opacity 0.8s ease;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Nexthrix SMP</h1>
  </header>

  <div class="section">
    <div class="card">
      <h2>Server IP</h2>
      <div class="ip-box">nexthrixsmp\.fun</div>
    </div>

    <div class="card">
      <h2>About the Server</h2>
      <p>
        Welcome to our Minecraft world! We offer survival, events, custom builds, and a friendly community.
        Play, explore, and enjoy endless adventures.
      </p>
    </div>

    <div class="card">
      <h2>Features</h2>
      <ul>
        <li>✔ 24/7 Uptime</li>
        <li>✔ No Lag</li>
        <li>✔ Friendly Staff</li>
        <li>✔ Survival + Mini-games</li>
      </ul>
    </div>
  </div>

  <footer>© 2025 Minecraft Server. All Rights Reserved.</footer>
  <script>
    // Smooth page fade-in
    document.body.classList.add('fade-page');
    window.addEventListener('load', () => {
      document.body.classList.add('fade-in');
    });
  </script>
</body>
</html>
