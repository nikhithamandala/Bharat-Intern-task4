HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Homepage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="netflix_logo.png" alt="Netflix Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>
    </header>

    <div class="hero-section">
        <h1>Welcome to Netflix</h1>
        <p>Watch unlimited TV shows and movies anytime, anywhere. Cancel anytime.</p>
        <button>Sign In</button>
    </div>

    <footer>
        <p>&copy; 2024 Netflix Clone</p>
    </footer>
</body>
</html>
```

CSS (styles.css):
```css
/* Resetting some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #000;
    padding: 20px;
    color: #fff;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-right: 20px;
}

.nav-links a {
    text-decoration: none;
    color: #fff;
}

.hero-section {
    background-image: url('netflix_hero_bg.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.hero-section h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero-section p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.hero-section button {
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #e50914;
    border: none;
    color: #fff;
    cursor: pointer;
}

footer {
    background-color: #000;
    color: #fff;
    padding: 20px;
    text-align: center;
}

