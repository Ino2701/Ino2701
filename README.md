<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My GitHub Page</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ff7e5f, #feb47b);
      font-family: sans-serif;
      color: white;
      overflow: hidden;
    }

    h1 {
      font-size: 3rem;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    }

    /* Hiệu ứng bong bóng */
    .bubble {
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
      animation: float 10s infinite;
    }

    @keyframes float {
      0% { transform: translateY(100vh) scale(0.5); opacity: 0.5; }
      50% { opacity: 1; }
      100% { transform: translateY(-10vh) scale(1); opacity: 0; }
    }
  </style>
</head>
<body>
  <h1>Welcome to My GitHub!</h1>
  <div class="bubble" style="width:50px; height:50px; left:10%; animation-duration:12s;"></div>
  <div class="bubble" style="width:30px; height:30px; left:50%; animation-duration:8s;"></div>
  <div class="bubble" style="width:70px; height:70px; left:80%; animation-duration:15s;"></div>
</body>
</html>
