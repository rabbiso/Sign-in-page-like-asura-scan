# Sign-in-page-like-asura-scan        
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <div class="logo">
                <!-- Placeholder for logo -->
                <img src="your-logo.png" alt="Logo">
            </div>
            <h2>Asura Scans</h2>
            <p>Login to your account</p>
            <form action="/login" method="POST">
                <div class="input-group">
                    <label for="email">Enter your Email</label>
                    <input type="email" id="email" name="email" placeholder="Email">
                </div>
                <div class="input-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" placeholder="Password">
                </div>
                <div class="options">
                    <label>
                        <input type="checkbox" name="remember"> Remember me
                    </label>
                    <a href="#">Forgot Password?</a>
                </div>
                <button type="submit" class="login-btn">Login</button>
            </form>
            <p>Not a member? <a href="/register">Create New Account</a></p>
            <div class="divider">Or continue with</div>
            <button class="google-btn">Continue with Google</button>
        </div>
    </div>
</body>
</html> 
for css part
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #1f1f1f;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.login-container {
    width: 100%;
    max-width: 400px;
    padding: 20px;
}

.login-box {
    background-color: #2c2c2c;
    padding: 40px;
    border-radius: 8px;
    text-align: center;
}

.logo img {
    width: 80px;
    margin-bottom: 10px;
}

h2 {
    color: white;
    margin-bottom: 10px;
}

p {
    margin-bottom: 20px;
}

.input-group {
    margin-bottom: 15px;
    text-align: left;
}

.input-group label {
    display: block;
    margin-bottom: 5px;
    color: #aaa;
}

.input-group input {
    width: 100%;
    padding: 10px;
    background-color: #333;
    border: none;
    border-radius: 5px;
    color: white;
}

.options {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
    font-size: 14px;
}

.options a {
    color: #aaa;
    text-decoration: none;
}

.login-btn {
    width: 100%;
    padding: 10px;
    background-color: #7e33ff;
    border: none;
    border-radius: 5px;
    color: white;
    font-size: 16px;
    cursor: pointer;
    margin-bottom: 15px;
}

.google-btn {
    width: 100%;
    padding: 10px;
    background-color: white;
    color: black;
    border-radius: 5px;
    border: 1px solid #ddd;
    font-size: 16px;
    cursor: pointer;
}

.divider {
    margin: 20px 0;
    color: #aaa;
}

