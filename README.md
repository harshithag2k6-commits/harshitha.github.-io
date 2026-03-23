# harshitha.github.-io
My first website 🌸
<!DOCTYPE html>
<html>
<head>
  <title>Harshitha's Website 🌸</title>
  <style>
    body {
      text-align: center;
      font-family: Arial;
      background: linear-gradient(to right, pink, lightblue);
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: purple;
      color: white;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>Welcome Harshitha 💖</h1>
  <p>Click below for a surprise 🎁</p>

  <button onclick="showMessage()">Click Me</button>

  <h2 id="msg"></h2>

  <script>
    function showMessage() {
      document.getElementById("msg").innerHTML = "🌸 You are amazing! 💐";
    }
  </script>

</body>
</html>
