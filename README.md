<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Make n Event | Event Management</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Lato&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <div class="logo"><a href="#">Make n Event</a></div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <div class="hero">
            <h1>Bringing Your Events to Life</h1>
            <p>Weddings, Corporate Events, and Everything In Between</p>
            <a href="#contact" class="cta-btn">Plan Your Event</a>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Make n Event</h2>
        <p>At Make n Event, we specialize in planning and managing unforgettable events — from weddings to business conferences. Our dedicated team ensures every detail is perfect so you can focus on what matters.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Wedding Planning</h3>
            <p>From intimate ceremonies to grand celebrations, we design weddings that reflect your unique style and vision.</p>
        </div>
        <div class="service">
            <h3>Corporate Events</h3>
            <p>We create impactful corporate events that enhance brand image and foster professional relationships.</p>
        </div>
        <div class="service">
            <h3>Business Meetings</h3>
            <p>Expertly planned meetings to ensure smooth operations and successful outcomes for your business.</p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Event Gallery</h2>
        <div class="gallery-images">
            <!-- Add images of past events here -->
            <img src="wedding1.jpg" alt="Wedding Event">
            <img src="business1.jpg" alt="Business Event">
            <img src="corporate1.jpg" alt="Corporate Event">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="send_form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Make n Event. All Rights Reserved.</p>
        <ul>
            <li><a href="facebook.com">Facebook</a></li>
            <li><a href="instagram.com">Instagram</a></li>
            <li><a href="twitter.com">Twitter</a></li>
        </ul>
    </footer>
</body>
</html>


<!---
Adhi005/Adhi005 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
