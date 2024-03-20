# ANIGAMI--THE-ANIME-WEBSITE
Our project aims to transform anime streaming by creating a user-friendly website with an AI bot companion. The AI bot acts as a personalized assistant, providing smart recommendations and engaging chat features. With a focus on user-centered design, we're enhancing connections between fans and their favorite anime.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>AniGami</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Anime List</a></li>
                <li><a href="#">Genres</a></li>
                <li><a href="#">About Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h2>Welcome to AniGami!</h2>
            <p>Your ultimate destination for everything anime.</p>
        </section>
        <section class="featured">
            <h2>Featured Anime</h2>
            <!-- Include featured anime here -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 AniGami. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

.hero {
    background-image: url('anime_background.jpg');
    background-size: cover;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.featured {
    margin-top: 50px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
