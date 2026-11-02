<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: #293238;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #e8491d;
        }
        .container {
            width: 80%;
            max-width: 900px;
            margin: 20px auto;
            background: #ffffff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #35424a;
            color: #ffffff;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>This is a basic HTML and CSS template. You can use it as a starting point for your own personal page or project.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>Write a brief intro about yourself, your business, or your project
