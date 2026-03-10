<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        /* Reset default margin/padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        header h1 {
            margin-bottom: 10px;
        }

        /* Navigation bar */
        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: #575757;
        }

        /* Main content */
        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        main h2 {
            margin-bottom: 10px;
            color: #333;
        }

        main p, main ul {
            margin-bottom: 15px;
            color: #555;
        }

        main ul {
            list-style: disc;
            padding-left: 20px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 10px;
            position: relative;
            margin-top: 20px;
        }

        /* Responsive adjustments */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
            }

            nav a {
                text-align: center;
                border-top: 1px solid #444;
            }

            main {
                margin: 10px;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>Designed using HTML & CSS</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <h2>About This Website</h2>
        <p>This is a clean and modern HTML template with responsive design. You can add your own content, images, and links here to create a complete website.</p>

        <h2>Features</h2>
        <ul>
            <li>Responsive design for mobile and desktop</li>
            <li>Clean layout with shadowed cards</li>
            <li>Navigation bar with hover effect</li>
        </ul>
    </main>

    <footer>
        &copy; 2026 My First Website
    </footer>

</body>
</html>
