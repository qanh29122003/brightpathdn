<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BrightPath - Building Skills, Shaping Future</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #FF6F00;
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header .logo {
            font-size: 1.5em;
            font-weight: bold;
        }
        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
        header nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #FFCC80;
            color: #333;
        }
        .hero h1 {
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2em;
        }
        .register-section {
            padding: 40px 20px;
            background-color: white;
            text-align: center;
        }
        .register-section h2 {
            margin-bottom: 20px;
        }
        .register-section form {
            max-width: 400px;
            margin: 0 auto;
            text-align: left;
        }
        .register-section form label {
            display: block;
            margin: 10px 0 5px;
        }
        .register-section form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .register-section form button {
            width: 100%;
            padding: 10px;
            background-color: #FF6F00;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .register-section form button:hover {
            background-color: #E65100;
        }
        footer {
            background-color: #FF6F00;
            color: white;
            text-align: center;
            padding: 10px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">BrightPath</div>
    <nav>
        <a href="#about">About</a>
        <a href="#register">Register</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>Welcome to BrightPath</h1>
    <p>Building Skills, Shaping Future</p>
</section>

<section class="register-section" id="register">
    <h2>Register Now</h2>
    <form action="/submit" method="post">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Enter your email address" required>

        <label for="phone">Phone Number</label>
        <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

        <button type="submit">Register</button>
    </form>
</section>

<footer>
    &copy; 2024 BrightPath. All Rights Reserved.
</footer>

</body>
</html>
