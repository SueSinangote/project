<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Our School</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#announcements">Announcements</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Our School</h2>
        <p>Our school is dedicated to providing quality education and fostering a community of lifelong learners.</p>
    </section>

    <section id="announcements">
        <h2>Announcements</h2>
        <p>Stay tuned for the latest updates and school news.</p>
        <div class="widget">
            <p><strong>Latest Update:</strong> No classes on Friday due to maintenance.</p>
        </div>
    </section>

    <section id="events">
        <h2>Upcoming Events</h2>
        <div class="widget">
            <p><strong>Sports Day:</strong> November 20</p>
            <p><strong>Parent-Teacher Meeting:</strong> December 5</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Our School. All rights reserved.</p>
    </footer>
</body>
</html>
