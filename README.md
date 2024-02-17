<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Name</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Website Heading</h1>
            <p>This is a brief description of the website and its purpose.</p>
            <img src="images/hero-image.jpg" alt="Hero image">
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Describe your company, team, or mission here.</p>
            <img src="images/about-image.jpg" alt="About image">
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Provide contact information and a form if needed.</p>
            <a href="https://www.google.com" target="_blank">Visit Google</a>
            <img src="images/contact-image.jpg" alt="Contact image">
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Copyright - Your Name/Company</p>
    </footer>

</body>
</html>
/* Overall styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    background-color: #f1f1f1;
    padding: 20px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav li {
    display: inline-block;
    margin: 0 10px;
}

nav a {
    text-decoration: none;
    color: #333;
}

nav a:hover {
    color: #007bff;
}

/* Main */
main {
    padding: 30px;
}

section {
    margin-bottom: 30px;
}

h1, h2 {
    text-align: center;
}

img {
    max-width: 100%;
    display: block;
    margin: 0 auto;
}

/* Contact form (replace with your preferred form code) */
form {
    /* Your form styles here */
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: #f1f1f1;
}

/* Responsive styles (add more as needed) */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
    }
}
