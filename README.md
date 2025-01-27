# c
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>足球之神选择</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f4f4f9;
    }
    .container {
      text-align: center;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    button {
      padding: 15px 30px;
      margin: 10px;
      font-size: 18px;
      cursor: pointer;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>请选择你的足球之神</h1>
    <button onclick="showMessage('cr7')">C罗</button>
    <button onclick="showMessage('messi')">梅西</button>
  </div>

  <script>
    function showMessage(player) {
      if (player === 'cr7') {
        alert("Siiiiuuuu!");
      } else if (player === 'messi') {
        alert("C罗才是真正的GOAT！");
      }
    }
  </script>
</body>
</html>
