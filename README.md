HEY IM MAYUR GRADUATE FROM RAISONI COLLEGE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sample PR Project</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
      background: #f4f4f4;
    }

    button {
      padding: 10px 20px;
      background: #2563eb;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>

<body>
  <h1>My GitHub Project</h1>
  <p id="message">Welcome to my frontend!</p>

  <button onclick="changeMessage()">
    Click Me
  </button>

  <script>
    function changeMessage() {
      document.getElementById("message").textContent =
        "This change came from a Pull Request!";
    }
  </script>
</body>
</html>
