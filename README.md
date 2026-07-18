<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Simple Website</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #333;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        nav a:hover {
            color: #4CAF50;
        }

        .hero {
            padding: 80px 20px;
            text-align: center;
            background: white;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .hero p {
            max-width: 600px;
            margin: auto;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            background: #4CAF50;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background: #45a049;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h1>My Website</h1>
        <p>Welcome to my simple website!</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <section class="hero">
        <h1>Hello, World!</h1>
        <p>
            This is a simple responsive website built with HTML and CSS.
            You can customize it however you like.
        </p>
        <a href="#" class="btn">Learn More</a>
    </section>

    <footer>
        <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>

</body>

</html>
