<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: pink;
            color: white;
            padding: 1em;
            text-align: center;
        }

        nav {
            background-color: #555;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
        }
    </style>
    <title>Your Portfolio</title>
</head>
<body>

    <header>
        <h1>TIMOTHY WIRE - Portfolio</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
    </nav>

    <section id="home">
        <h2>TIMOTHY WIRE PORTFOLIO</h2>
        <p>This is the home section of my portfolio. Feel free to explore!</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a software developer courtesy of power learn project.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Project 1:</strong>connecting all students countrywide</li>
            <li><strong>Project 2:</strong> Description of Project 2</li>
            <li><strong>Project 3:</strong> Description of Project 3</li>
        </ul>
    </section>

</body>
</html>
