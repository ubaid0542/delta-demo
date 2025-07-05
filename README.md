# delta-demo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bouncing Ball Animation</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      background-color: #f0f0f0;
      overflow: hidden;
    }

    .ball {
      width: 50px;
      height: 50px;
      background-color: #3498db;
      border-radius: 50%;
      position: relative;
      animation: bounce 1s infinite ease-in-out;
    }

    @keyframes bounce {
      0%, 100% {
        top: 0;
      }
      50% {
        top: 300px;
      }
    }
  </style>
</head>
<body>
  <div class="ball"></div>
</body>
</html>
