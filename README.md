<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 50%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        form {
            background: #fff;
            padding: 20px;
            margin-top: 30px;
        }
       , form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        form button {
            background: #333;
            color: #fff;
            padding: 10px;
            border: 0;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Contact Me</h1>
        </div>
    </header>
    <div class="container">
        <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</body>
</html>
