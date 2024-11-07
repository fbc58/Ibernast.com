<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibernast - Iberic Dinasty</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo.png" alt="Ibernast Logo" class="logo">
            <nav>
                <a href="#home">Home</a>
                <a href="#products">Products</a>
                <a href="#about">About Us</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-text">
            <h2>Welcome to Ibernast</h2>
            <p>We produce and export the finest Iberian pork ham to the Chinese market.</p>
        </div>
    </section>

    <section id="products" class="section-padding">
        <h2>Our Products</h2>
        <div class="product-container">
            <div class="product-item">
                <img src="iberian_ham_leg.jpg" alt="Iberian Ham Leg">
                <h3>Iberian Ham Leg</h3>
                <p>High-quality whole Iberian ham, meticulously cured to perfection.</p>
            </div>
            <div class="product-item">
                <img src="sliced_ham.jpg" alt="Sliced Iberian Ham">
                <h3>100g Sliced Iberian Ham</h3>
                <p>Conveniently packaged slices of premium Iberian ham, ideal for export.</p>
            </div>
        </div>
    </section>

    <section id="about" class="section-padding">
        <h2>About Us</h2>
        <div class="about-content">
            <h3>Our Mission</h3>
            <p>To produce and export the highest quality Iberian pork ham to China, ensuring an ethical and sustainable process from transformation to exportation.</p>
            
            <h3>Our Vision</h3>
            <p>To become a global leader in Iberian ham production and exportation, preserving authenticity and exceptional quality in the next four years while sustainably expanding in international markets.</p>
            
            <h3>Our Values</h3>
            <ul>
                <li>Quality</li>
                <li>Sustainability</li>
                <li>Commitment</li>
                <li>Social Responsibility</li>
                <li>Adaptability</li>
            </ul>
            
            <h3>Our Policies</h3>
            <ul>
                <li>Conduct thorough quality checks at all production stages to ensure product excellence.</li>
                <li>Provide mandatory training courses for all new employees.</li>
                <li>Maintain rigorous quality control with our suppliers.</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="section-padding">
        <h2>Contact Us</h2>
        <p>For inquiries and partnerships, reach out via our contact form below.</p>
        <!-- Contact form or contact details could be added here -->
    </section>

    <footer>
        <p>&copy; 2024 Ibernast - Iberic Dinasty. All rights reserved.</p>
    </footer>
</body>
</html>
/* Global styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #1a1a1a;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    width: 100px;
}

nav a {
    color: #fff;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-image: url('hero_image.jpg');
    background-size: cover;
    background-position: center;
    padding: 50px 0;
    color: #fff;
    text-align: center;
}

.hero-text h2 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.hero-text p {
    font-size: 1.2rem;
}

/* Product Section */
.section-padding {
    padding: 2rem;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 30px;
}

.product-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 45%;
}

.product-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.product-item h3 {
    margin-top: 10px;
    font-size: 1.5rem;
}

/* About Section */
.about-content {
    text-align: left;
    max-width: 800px;
    margin: 0 auto;
}

.about-content ul {
    list-style-type: none;
    padding-left: 20px;
}

.about-content ul li {
    margin-bottom: 8px;
}

/* Footer */
footer {
    background-color: #1a1a1a;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}
