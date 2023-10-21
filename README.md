### Hi there 👋

<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
    }
    .container {
      position: relative;
      text-align: center;
      color: white;
    }
    .centered {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    .bg-image {
      animation: gradient 10s ease infinite;
      background-image: linear-gradient(45deg, #F06, #678);
      height: 100%;
      filter: blur(5px);
      z-index: -1;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
    }
    @keyframes gradient {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
  </style>
</head>
<body>
  <div class="bg-image"></div>
  <div class="container">
    <div class="centered">
      <h1>Привет, это мой проект на GitHub!</h1>
      <p>Здесь вы найдете мой код и документацию.</p>
    </div>
  </div>
</body>
</html>

