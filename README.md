Hi 👋, I'm Matias D'Andrea
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pentesting Lab</title>

  <style>
    body {
      margin: 0;
      background: #0d1117;
      color: #00ff9f;
      font-family: monospace;
    }

    header {
      padding: 20px;
      text-align: center;
      border-bottom: 1px solid #00ff9f;
    }

    h1 {
      margin: 0;
    }

    .container {
      padding: 40px;
      text-align: center;
    }

    input {
      display: block;
      margin: 10px auto;
      padding: 10px;
      width: 250px;
      background: black;
      color: #00ff9f;
      border: 1px solid #00ff9f;
    }

    button {
      padding: 10px 20px;
      background: #00ff9f;
      border: none;
      cursor: pointer;
      font-weight: bold;
    }

    .hint {
      margin-top: 20px;
      font-size: 14px;
      opacity: 0.6;
    }

    footer {
      margin-top: 50px;
      text-align: center;
      font-size: 12px;
      opacity: 0.5;
    }
  </style>
</head>

<body>

<header>
  <h1>🔐 Pentesting Lab</h1>
  <p>Practice Web Vulnerabilities</p>
</header>

<div class="container">

  <h2>Login Panel</h2>

  <form method="GET">
    <input type="text" name="username" placeholder="Username">
    <input type="password" name="password" placeholder="Password">
    <button>Login</button>
  </form>

  <p class="hint">💡 Hint: Try SQL Injection...</p>

</div>

<footer>
  ⚠️ For educational purposes only
</footer>

</body>
</html>
