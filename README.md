<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #1f1c2c, #928dab);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 20px;
            border-radius: 20px;
            width: 90%;
            max-width: 600px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-size: 2.5em;
            text-transform: uppercase;
        }
        .social-icons a {
            margin: 10px;
            text-decoration: none;
            color: #fff;
            font-size: 1.5em;
            transition: 0.3s;
        }
        .social-icons a:hover {
            color: #ffcc00;
        }
        .button {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            border-radius: 10px;
            background: linear-gradient(45deg, #ffcc00, #ff6699);
            color: #000;
            font-weight: bold;
            text-decoration: none;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }
        .button:hover {
            transform: translateY(-3px);
            box-shadow: 10px 10px 25px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hello, I'm <span style="color: #ffcc00;">Your Name</span> 👋</h1>
        <p>A passionate Full Stack Developer specializing in modern web technologies.</p>
        
        <div class="social-icons">
            <a href="https://github.com/yourusername" target="_blank">🔗 GitHub</a>
            <a href="https://www.linkedin.com/in/yourprofile/" target="_blank">🔗 LinkedIn</a>
            <a href="https://yourportfolio.com" target="_blank">🌐 Portfolio</a>
        </div>
        
        <a href="https://github.com/yourusername" class="button">Explore My Work</a>
    </div>
</body>
</html>
