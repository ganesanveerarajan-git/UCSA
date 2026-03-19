<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }

        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #555;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            padding: 20px;
        }

        .card {
            background: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        button {
            padding: 10px 15px;
            background: blue;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Unique Carrom, Socical and Cultural Association</h1>
    <p>This is UCSCA official site 🚀</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    You will find complete entertainment here.
    <a href="#">Contact</a>
    Contact Mr.Rajkumar Secretary for details Cell No. ##########
</nav>

<div class="container">
    <div class="card">
        <h2>About Me</h2>
        <p>Welcome!</p>
        <button onclick="showMessage()">Click Me</button>
    </div>

    <div class="card">
        <h2>My Goal</h2>
        <p>To become a full-stack developer.</p>
    </div>
</div>

<footer>
    <p>© 2026 My Website</p>
</footer>

<script>
    function showMessage() {
        alert("You clicked the button!");
    }
</script>

</body>
</html>
