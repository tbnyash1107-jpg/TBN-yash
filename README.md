
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Message</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: black;
      color: white;
      font-size: 26px;
      text-align: center;
      font-family: Arial, sans-serif;
    }

    #message {
      display: none;
    }
  </style>
</head>

<body>

  <div id="tap">TAP SCREEN 👆</div>

  <div id="message">
    kripya hamare maje naa le 🙏🙏😔
  </div>

  <script>
    document.addEventListener("click", showMessage, { once: true });
    document.addEventListener("touchstart", showMessage, { once: true });

    function showMessage() {
      document.getElementById("tap").style.display = "none";
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
