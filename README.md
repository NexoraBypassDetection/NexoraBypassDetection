<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Need Help?</title>
  <style>
    body {
      margin: 0;
      padding: 40px 20px;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(145deg, #0a0f2c, #1e2a50);
      color: #f0f0f0;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      box-sizing: border-box;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      padding: 30px;
      max-width: 420px;
      width: 100%;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      backdrop-filter: blur(12px);
      text-align: center;
    }

    h1 {
      color: #ff4e4e;
      font-size: 2rem;
      margin-bottom: 20px;
      text-shadow: 0 0 6px rgba(255, 0, 0, 0.4);
    }

    h2 {
      font-size: 1.5rem;
      margin-bottom: 0;
    }

    p {
      font-size: 1rem;
      color: #bbb;
      margin-top: 5px;
      margin-bottom: 20px;
    }

    button {
      background: #7289da;
      border: none;
      color: white;
      padding: 14px 28px;
      font-size: 1rem;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s ease;
      box-shadow: 0 4px 12px rgba(114, 137, 218, 0.4);
    }

    button:hover {
      background: #5b6eae;
      box-shadow: 0 4px 18px rgba(114, 137, 218, 0.6);
    }

    iframe {
      margin-top: 30px;
      border-radius: 15px;
      border: none;
      width: 100%;
      height: 500px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>DO NOT TRY TO BYPASS THE KEY SYSTEM!</h1>
    <h2>Need assistance?</h2>
    <p>Join Our Discord Server Below!</p>

    <button onclick="window.location.href='https://discord.gg/YOUR_INVITE_CODE'">
      Help
    </button>

    <iframe
      src="https://discord.com/widget?id=1378394208427049071&theme=dark"
      allowtransparency="true"
      frameborder="0"
      sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts">
    </iframe>
  </div>
</body>
</html>
