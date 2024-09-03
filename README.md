
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estate Gate Access Code Application</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Estate Gate Access Code Application</h1>
        
        <div id="form-container">
            <form id="registration-form" action="/register" method="post">
                <h2>Register</h2>
                <label for="reg-username">Username:</label>
                <input type="text" id="reg-username" name="username" required>
                
                <label for="reg-password">Password:</label>
                <input type="password" id="reg-password" name="password" required>
                
                <button type="submit">Register</button>
            </form>

            <form id="login-form" action="/login" method="post">
                <h2>Login</h2>
                <label for="login-username">Username:</label>
                <input type="text" id="login-username" name="username" required>
                
                <label for="login-password">Password:</label>
                <input type="password" id="login-password" name="password" required>
                
                <button type="submit">Login</button>
            </form>

            <form id="code-form" action="/generate_code" method="post">
                <h2>Generate Access Code</h2>
                <label for="code-username">Username:</label>
                <input type="text" id="code-username" name="username" required>
                
                <button type="submit">Generate Code</button>
            </form>
        </div>
    </div>
</body>
</html>
