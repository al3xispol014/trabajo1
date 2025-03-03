<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login</title>
  <link rel="stylesheet" href="style.css">
  
</head>
<body>
  <div class="login-container">
    <h2>Iniciar Sesión</h2>
    <form id="loginForm">
      <div class="input-group">
        <label for="username">Usuario:</label>
        <input type="text" id="username" name="username" required>
      </div>
      <div class="input-group">
        <label for="password">Contraseña:</label>
        <input type="password" id="password" name="password" required>
      </div>
      <button type="submit">Entrar</button>
    </form>
    <p id="errorMsg"></p>
  </div>
  <script src="log.js"></script>
</body>
</html>
