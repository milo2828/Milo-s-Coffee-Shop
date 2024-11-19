<!-- Navigation -->
<header>
    <nav>
        <div class="logo">
            <h1>Milo's Coffee</h1>
        </div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Home Section -->
<section id="home" class="home-section">
    <div class="hero-content">
        <h2>Welcome to Milo's Coffee</h2>
        <p>Freshly brewed coffee for every taste!</p>
        <a href="#menu" class="cta-button">Browse Our Menu</a>
    </div>
</section>

<!-- Menu Section -->
<section id="menu" class="menu-section">
    <h2>Our Menu</h2>
    <div class="menu-items">
        <div class="menu-item">
            <img src="coffee1.jpg" alt="Espresso">
            <h3>Espresso</h3>
            <p>A strong and bold coffee shot.</p>
            <span>$3.00</span>
        </div>
        <div class="menu-item">
            <img src="coffee2.jpg" alt="Latte">
            <h3>Latte</h3>
            <p>A creamy blend of espresso and steamed milk.</p>
            <span>$4.50</span>
        </div>
        <div class="menu-item">
            <img src="coffee3.jpg" alt="Cappuccino">
            <h3>Cappuccino</h3>
            <p>Espresso topped with rich frothy milk.</p>
            <span>$4.00</span>
        </div>
    </div>
</section>

<!-- About Us Section -->
<section id="about" class="about-section">
    <h2>About Us</h2>
    <p>At Milo's Coffee, we pride ourselves on providing the finest, locally sourced coffee beans. We offer a variety of delicious drinks made with love, passion, and the finest ingredients. Our goal is to make your day better with every sip!</p>
</section>

<!-- Contact Section -->
<section id="contact" class="contact-section">
    <h2>Contact Us</h2>
    <p>We'd love to hear from you! Whether you have a question or need more information, feel free to reach out.</p>
    <form action="#" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit" class="cta-button">Send Message</button>
    </form>
</section>

</body> </html>
/* Reset some basic styles */

{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: Arial, sans-serif;
}

body {
background-color: #b5651d;
color:#3d0c02;
}

/* Header and Navigation */
header {
background-color:#3d0c02;
color:white;
padding: 10px 0;
}

header nav {
display: flex;
justify-content: space-between;
align-items: center;
padding: 0 20px;
}

header .logo h1 {
font-size: 24px;
margin: 0;
}

.nav-links {
list-style: none;
display: flex;
}

.nav-links li {
margin: 0 15px;
}

.nav-links a {
color: #fff;
text-decoration: none;
font-size: 16px;
}

/* Hero Section */
.home-section {
background-image: url('coffee-hero.jpg');
background-size: cover;
background-position: center;
height: 400px;
display: flex;
justify-content: center;
align-items: center;
color: white;
text-align: center;
}

.hero-content h2 {
font-size: 48px;
margin-bottom: 10px;
}

.hero-content p {
font-size: 24px;
margin-bottom: 20px;
}

.cta-button {
background-color: #3d0c02;
color: white;
padding: 10px 20px;
font-size: 18px;
text-decoration: none;
border-radius: 5px;
}

.cta-button:hover {
background-color: #3d0c02;
}

/* Menu Section */
.menu-section {
padding: 50px 20px;
text-align: center;
background-color: #fff;
}

.menu-section h2 {
font-size: 36px;
margin-bottom: 30px;
}

.menu-items {
display: flex;
justify-content: space-around;
flex-wrap: wrap;
}

.menu-item {
background-color: #f4f4f4;
padding: 20px;
width: 250px;
margin: 15px;
border-radius: 10px;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
text-align: center;
}

.menu-item img {
width: 100%;
border-radius: 8px;
}

.menu-item h3 {
font-size: 24px;
margin-top: 15px;
}

.menu-item p {
font-size: 14px;
margin-top: 5px;
}

.menu-item span {
font-size: 18px;
font-weight: bold;
color: #d32f2f;
margin-top: 10px;
}

/* About Section */
.about-section {
padding: 50px 20px;
background-color: #eeeeee;
text-align: center;
}

.about-section h2 {
font-size: 36px;
margin-bottom: 20px;
}

.about-section p {
font-size: 18px;
max-width: 800px;
margin: 0 auto;
}

/* Contact Section */
.contact-section {
padding: 50px 20px;
background-color:;
text-align: center;
}

.contact-section h2 {
font-size: 36px;
margin-bottom: 20px;
}

.contact-section form {
max-width: 600px;
margin: 0 auto;
}

.contact-section input, .contact-section textarea {
width: 100%;
padding: 10px;
margin: 10px 0;
border: 2px solid #ccc;
border-radius: 5px;
font-size: 16px;
}

.contact-section button {
background-color:#3d0c02;
color: white;
padding: 10px 20px;
border: none;
font-size: 18px;
cursor: pointer;
border-radius: 5px;
}

.contact-section button:hover {
background-color: #3d0c02;
}

/* Footer */
footer {
background-color:#3d0c02;
color: white;
text-align: center;
padding: 10px 0;
margin-top: 50px;
}

// Add any interactive features you want here
// For example, we can add simple form validation

document.querySelector("form").addEventListener("submit", function(e) {
e.preventDefault();
alert("Thank you for your message! We'll get back to you soon.");
});
<!-- Footer -->
<footer>
    <p>&copy; 2024 Milo's Coffee. All Rights Reserved.</p>
</footer>

<script src="script.js"></script>
