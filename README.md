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
      position: relative;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 24px;
      padding: 40px 30px;
      max-width: 480px;
      width: 100%;
      text-align: center;
      backdrop-filter: blur(15px);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 10px 50px rgba(0, 0, 0, 0.5);
      overflow: hidden;
    }

    .container::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 24px;
      padding: 2px;
      background: linear-gradient(120deg, transparent 0%, #3b82f6 50%, transparent 100%);
      background-size: 300% 300%;
      z-index: 0;
      opacity: 0;
      transition: opacity 0.4s ease;
      animation: glowSweep 1s linear forwards;
      pointer-events: none;
    }

    .container:hover::before {
      opacity: 1;
      animation: glowSweep 1s linear forwards;
    }

    @keyframes glowSweep {
      0% {
        background-position: 0% 50%;
        opacity: 0;
      }
      30% {
        opacity: 1;
      }
      100% {
        background-position: 200% 50%;
        opacity: 1;
      }
    }

    .container:hover {
      transform: scale(1.01);
      box-shadow:
        0 0 0 3px #3b82f6,
        0 0 20px 6px rgba(96, 165, 250, 0.8),
        0 12px 60px rgba(0, 0, 0, 0.55);
    }

    h1 {
      font-size: 1.8rem;
      color: #ef4444;
      margin-bottom: 16px;
      text-shadow: 0 0 8px rgba(255, 0, 0, 0.3);
      position: relative;
      z-index: 1;
    }

    h2 {
      font-size: 1.4rem;
      color: #60a5fa;
      margin-bottom: 6px;
      position: relative;
      z-index: 1;
    }

    p {
      font-size: 1rem;
      color: #94a3b8;
      margin-bottom: 24px;
      position: relative;
      z-index: 1;
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
      box-shadow: 0 6px 24px rgba(96, 165, 250, 0.6);
      position: relative;
      z-index: 1;
    }

    button:hover {
      background: linear-gradient(to right, #60a5fa, #3b82f6);
      box-shadow:
        0 0 0 2px #3b82f6,
        0 0 20px 8px rgba(96, 165, 250, 0.8),
        0 10px 60px rgba(0, 0, 0, 0.55);
      transform: translateY(-2px);
    }

    .logo {
      margin-top: 32px;
      width: 100%;
      max-width: 360px;
      height: auto;
      border-radius: 16px;
      box-shadow:
        0 10px 30px rgba(30, 58, 138, 0.5),
        0 6px 16px rgba(0, 0, 0, 0.25);
      position: relative;
      z-index: 1;
    }

    @media (max-width: 500px) {
      .container {
        padding: 30px 20px;
      }

      .logo {
        max-width: 100%;
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

    <img
      src="https://cdn.discordapp.com/attachments/1220824376123850752/1380312327806521415/NEXORA_SCRIPTS.png?ex=68436b87&is=68421a07&hm=75511ffd508259721d6878428d9e02059d0e3a937b29747089e999d58be8d8e4&"
      alt="NEXORA SCRIPTS Logo"
      class="logo"
    />
  </div>
</body>
</html>
