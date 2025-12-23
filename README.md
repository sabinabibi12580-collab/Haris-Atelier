<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haris Graphic Designing - Creative Designs, Professional Results</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Lato:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">Haris Graphic Designing</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#order">Order</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </nav>
    </header>

    <!-- Home / Hero Section -->
    <section id="home" class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1>Creative Designs, Professional Results</h1>
            <p>Transforming ideas into stunning visuals that captivate and inspire.</p>
            <a href="#portfolio" class="cta-button">Explore Portfolio</a>
        </div>
        <div class="hero-bg">
            <!-- Animated background elements -->
            <div class="floating-shape shape1"></div>
            <div class="floating-shape shape2"></div>
            <div class="floating-shape shape3"></div>
        </div>
    </section>

    <!-- Portfolio / Gallery Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="carousel-container">
                <div class="carousel-slide">
                    <div class="portfolio-item">
                        <img src="https://images.unsplash.com/photo-1558655146-364adaf1fcc9?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Logo Design">
                        <div class="overlay">
                            <h3>Logo Design</h3>
                            <p>Brand identity for a tech startup.</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="https://images.unsplash.com/photo-1586717791821-3f44a563fa4c?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Poster Design">
                        <div class="overlay">
                            <h3>Poster Design</h3>
                            <p>Event promotion for a music festival.</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="https://images.unsplash.com/photo-1559028006-448665bd7c7f?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Website Mockup">
                        <div class="overlay">
                            <h3>Website Mockup</h3>
                            <p>UI/UX design for an e-commerce site.</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="https://images.unsplash.com/photo-1561070791-2526d30994b5?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Brochure Design">
                        <div class="overlay">
                            <h3>Brochure Design</h3>
                            <p>Corporate brochure for a real estate company.</p>
                        </div>
                    </div>
                </div>
                <button class="carousel-prev">&lt;</button>
                <button class="carousel-next">&gt;</button>
            </div>
        </div>
    </section>

    <!-- Order Section -->
    <section id="order" class="order">
        <div class="container">
            <h2>Place an Order</h2>
            <form id="order-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="details" placeholder="Project Details" required></textarea>
                <input type="file" name="file" accept=".jpg,.png,.pdf,.ai,.psd">
                <button type="submit" class="cta-button">Submit Order</button>
            </form>
        </div>
    </section>

    <!-- About / Haris Details Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="about-content">
                <h2>About Haris</h2>
                <p>I’m a passionate and detail-oriented Graphic Designer with experience in creating visually compelling designs that help brands stand out. I specialize in logos, social media graphics, branding, marketing materials, and print-ready designs.<br><br>My focus is simple: clear communication, fast turnaround, and uncompromised quality. I believe good design is not just about looking good—it’s about delivering the right message effectively.<br><br>Whether you’re a startup, business owner, or content creator, I’m here to transform your ideas into professional, eye-catching visuals that get results.</p>
                <ul class="skills">
                    <li>Logos</li>
                    <li>Social Media Graphics</li>
                    <li>Branding</li>
                    <li>Marketing Materials</li>
                    <li>Print-Ready Designs</li>
                </ul>
            </div>
            <div class="about-image">
                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Haris - Graphic Designer">
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <div class="contact-info">
                <p>Email: haris@graphicdesign.com</p>
                <p>Phone: +1 (123) 456-7890</p>
                <div class="social-links">
                    <a href="#" class="social-icon">Instagram</a>
                    <a href="#" class="social-icon">LinkedIn</a>
                    <a href="#" class="social-icon">Behance</a>
                </div>
            </div>
            <form id="contact-form">
                <input type="text" name="name" placeholder="Name" required>
                <input type="email" name="email" placeholder="Email" required>
                <textarea name="message" placeholder="Message" required></textarea>
                <button type="submit" class="cta-button">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2023 Haris Graphic Designing. All rights reserved.</p>
            <ul class="footer-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="footer-social">
                <a href="#" class="social-icon">IG</a>
                <a href="#" class="social-icon">LI</a>
                <a href="#" class="social-icon">BH</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>/* Mobile-first CSS: Base styles for mobile, then media queries for larger screens */

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Lato', sans-serif;
    line-height: 1.6;
    color: #e0e0e0; /* Light text on dark bg */
    background-color: #1a1a1a; /* Dark background */
    overflow-x: hidden;
}

h1, h2, h3 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
header {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: rgba(26, 26, 26, 0.9);
    backdrop-filter: blur(10px);
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 1.5rem;
}

.logo {
    font-size: 1.2rem;
    color: #00ffff; /* Neon blue accent */
}

.nav-links {
    display: none; /* Hidden on mobile */
    list-style: none;
    flex-direction: column;
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
    background-color: #1a1a1a;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
}

.nav-links.active {
    display: flex;
}

.nav-links li {
    margin: 1rem 0;
    text-align: center;
}

.nav-links a {
    text-decoration: none;
    color: #e0e0e0;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #ff69b4; /* Pastel pink accent */
}

.hamburger {
    display: flex;
    flex-direction: column;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background-color: #e0e0e0;
    margin: 3px 0;
    transition: 0.3s;
}

/* Hero Section */
.hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 5rem 1rem 2rem;
    background: linear-gradient(135deg, #1a1a1a 0%, #333 100%);
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.3);
}

.hero-content {
    position: relative;
    z-index: 1;
}

.hero-content h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #fff;
    text-shadow: 0 0 20px #00ffff;
}

.hero-content p {
    font-size: 1.1rem;
    margin-bottom: 2rem;
    color: #e0e0e0;
}

.cta-button {
    display: inline-block;
    padding: 0.8rem 2rem;
    background: linear-gradient(45deg, #00ffff, #ff69b4);
    color: #1a1a1a;
    text-decoration: none;
    border-radius: 5px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.cta-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0, 255, 255, 0.5);
}

.hero-bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.floating-shape {
    position: absolute;
    border-radius: 50%;
    animation: float 6s ease-in-out infinite;
}

.shape1 {
    width: 100px;
    height: 100px;
    background: linear-gradient(45deg, #00ffff, #ff69b4);
    top: 20%;
    left: 10%;
    animation-delay: 0s;
}

.shape2 {
    width: 80px;
    height: 80px;
    background: linear-gradient(45deg, #ff69b4, #00ffff);
    top: 60%;
    right: 15%;
    animation-delay: 2s;
}

.shape3 {
    width: 60px;
    height: 60px;
    background: linear-gradient(45deg, #00ffff, #ff69b4);
    bottom: 20%;
    left: 50%;
    animation-delay: 4s;
}

@keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
}

/* Portfolio Section */
.portfolio {
    padding: 4rem 0;
    background-color: #262626;
}

.portfolio h2 {
    text-align: center;
    margin-bottom: 2rem;
    color: #fff;
}

.carousel-container {
    position: relative;
    overflow: hidden;
    max-width: 100%;
}

.carousel-slide {
    display: flex;
    transition: transform 0.3s;
}

.portfolio-item {
    position: relative;
    min-width: 280px;
    margin: 0 1rem;
    overflow: hidden;
    border-radius: 10px;
    transition: transform 0.3s;
}

.portfolio-item:hover {
    transform: scale(1.05);
}

.portfolio-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 255, 255, 0.8);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: opacity 0.3s;
    color: #1a1a1a;
    text-align: center;
}

.portfolio-item:hover .overlay {
    opacity: 1;
}

.carousel-prev, .carousel-next {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(0, 0, 0, 0.5);
    color: #fff;
    border: none;
    padding: 0.5rem;
    cursor: pointer;
    border-radius: 50%;
    transition: background 0.3s;
}

.carousel-prev {
    left: 10px;
}

.carousel-next {
    right: 10px;
}

.carousel-prev:hover, .carousel-next:hover {
    background: rgba(0, 255, 255, 0.8);
}

/* Order Section */
.order {
    padding: 4rem 0;
    background-color: #1a1a1a;
}

.order h2 {
    text-align: center;
    margin-bottom: 2rem;
    color: #fff;
}

#order-form {
    max-width: 500px;
    margin: 0 auto;
}

#order-form input, #order-form textarea {
    width: 100%;
    padding: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #333;
    border-radius: 5px;
    background-color: #262626;
    color: #e0e0e0;
    font-family: 'Lato', sans-serif;
}

#order-form button {
    width: 100%;
}

/* About Section */
.about {
    padding: 4rem 0;
    background-color: #262626;
}

.about .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.about-content {
    margin-bottom: 2rem;
}

.about-content h2 {
    margin-bottom: 1rem;
    color: #fff;
}

.about-content p {
    margin-bottom: 1rem;
    color: #e0e0e0;
}

.skills {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
}

.skills li {
    background: linear-gradient(45deg, #00ffff, #ff69b4);
    color: #1a1a1a;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-weight: 700;
}

.about-image img {
    width: 100%;
    max-width: 300px;
    border-radius: 50%;
    border: 5px solid #00ffff;
}

/* Contact Section */
.contact {
    padding: 4rem 0;
    background-color: #1a1a1a;
}

.contact h2 {
    text-align: center;
    margin-bottom: 2rem;
    color: #fff;
}

.contact-info {
    text-align: center;
    margin-bottom: 2rem;
}

.contact-info p {
    margin-bottom: 0.5rem;
    color
</body>
</html>
