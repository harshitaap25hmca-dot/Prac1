# Prac1
#prac1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First GitHub Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #24292e;
            color: white;
            padding: 20px;
        }

        main {
            padding: 40px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #0366d6;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #024ea2;
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #ddd;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Website</h1>
</header>

<main>
    <h2>Hello World 👋</h2>
    <p>This is my first project hosted on GitHub.</p>
    <button onclick="showMessage()">Click Me</button>
</main>

<footer>
    <p>© 2026 My Project</p>
</footer>

<script>
    function showMessage() {
        alert("Hello! Your JavaScript is working 🚀");
    }
</script>

</body>
</html>
