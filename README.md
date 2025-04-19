# Medical-Card-Transaction
Login page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login Page</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="background">
    <div class="login-box">
      <h2>Login</h2>
      <form>
        <input type="text" placeholder="Username or email" required />
        <div class="password-field">
          <input type="password" placeholder="Password" required />
          <a href="#">Forgot password?</a>
        </div>
        <label class="remember">
          <input type="checkbox" />
          Remember me
        </label>
        <button type="submit" class="login-button" onclick="window.location.href='index2.html'">Login</button>
        <p class="signup-link">Don't have an account? <a href="#">Sign up</a></p>
      </form>
    </div>
  </div>
</body>
</html>
