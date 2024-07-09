<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>My Website</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Welcome to My Website</h1>
        <p>Explore our content and services!</p>
    </main>

    <footer>
        © 2024 My Website
    </footer>
</body>
</html>


/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Basic styling for the menu bar */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav li {
    margin-right: 1rem;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Style the main content area */
main {
    padding: 2rem;
    text-align: center;
}

/* Footer styles */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}
