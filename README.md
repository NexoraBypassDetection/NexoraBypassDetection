<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Need Help?</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #0f172a, #1e293b);
      color: #e2e8f0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 30px;
    }

    .container {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 24px;
      padding: 40px 30px;
      max-width: 480px;
      width: 100%;
      text-align: center;
      backdrop-filter: blur(15px);
      box-shadow: 0 8px 40px rgba(0, 0, 0, 0.4);
      transition: 0.3s ease;
      position: relative;
    }

    .container:hover {
      transform: scale(1.01);
      box-shadow:
        0 0 0 3px #3b82f6,
        0 0 12px 4px rgba(96, 165, 250, 0.6),
        0 8px 40px rgba(0, 0, 0, 0.4);
    }

    h1 {
      font-size: 1.8rem;
      color: #ef4444;
      margin-bottom: 16px;
      text-shadow: 0 0 8px rgba(255, 0, 0, 0.3);
    }

    h2 {
      font-size: 1.4rem;
      color: #60a5fa;
      margin-bottom: 6px;
    }

    p {
      font-size: 1rem;
      color: #94a3b8;
      margin-bottom: 24px;
    }

    button {
      background: linear-gradient(to right, #3b82f6, #60a5fa);
      color: white;
      border: none;
      padding: 14px 28px;
      font-size: 1rem;
      border-radius: 16px;
      cursor: pointer;
      transition: all 0.25s ease;
      box-shadow: 0 4px 18px rgba(96, 165, 250, 0.5);
    }

    button:hover {
      background: linear-gradient(to right, #60a5fa, #3b82f6);
      box-shadow: 0 6px 24px rgba(96, 165, 250, 0.7);
      transform: translateY(-2px);
    }

    iframe {
      margin-top: 32px;
      width: 100%;
      height: 500px;
      border-radius: 16px;
      border: none;
      box-shadow: 0 4px 18px rgba(0, 0, 0, 0.2);
    }

    @media (max-width: 500px) {
      .container {
        padding: 30px 20px;
      }

      iframe {
        height: 400px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>DO NOT TRY TO BYPASS THE KEY SYSTEM!</h1>
    <h2>Need assistance?</h2>
    <p>Join our verified Discord support server below</p>

    <button onclick="window.location.href='https://discord.gg/YOUR_INVITE_CODE'">
      Join Support Server
    </button>

    <iframe
      src="https://discord.com/widget?id=1378394208427049071&theme=dark"
      allowtransparency="true"
      sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts">
    </iframe>
  </div>
</body>
</html>
