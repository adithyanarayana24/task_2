# task_3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Library - Your Gateway to Knowledge</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f4f6;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 0 20px;
        }

        /* Header Styles */
        header {
            background-color: #34495e;
            color: #ecf0f1;
            padding: 20px 0;
            text-align: center;
            border-bottom: 5px solid #2980b9;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
            padding: 0;
            margin-top: 10px;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #ecf0f1;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #bdc3c7;
        }

        /* Hero Section Styles */
        .hero {
            background: url('https://images.unsplash.com/photo-1512820790803-83ca734da794') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h2 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        .hero .btn {
            background-color: #2980b9;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 1.2rem;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .hero .btn:hover {
            background-color: #1f618d;
        }

        /* Features Section Styles */
        .features {
            padding: 50px 0;
            text-align: center;
            background-color: #ecf0f1;
        }
        .features h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        .feature-item {
            display: inline-block;
            width: 30%;
            margin: 0 1.5%;
            background-color: #ffffff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: left;
        }
        .feature-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 15px;
        }
        .feature-item h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: #2980b9;
        }
        .feature-item p {
            font-size: 1rem;
            line-height: 1.5;
            color: #666;
        }

        /* Contact Section Styles */
        .contact {
            background-color: #f3f4f6;
            padding: 50px 0;
            text-align: center;
        }
        .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        .contact form {
            max-width: 600px;
            margin: auto;
        }
        .contact form input, 
        .contact form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact form button {
            background-color: #2980b9;
            color: #fff;
            padding: 15px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2rem;
            transition: background 0.3s;
        }
        .contact form button:hover {
            background-color: #1f618d;
        }

        /* Footer Styles */
        footer {
            background-color: #34495e;
            color: #ecf0f1;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
        footer p {
            margin: 0;
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Online Library</h1>
            <nav>
                <ul>
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="hero">
        <div class="container">
            <h2>Your Gateway to Knowledge</h2>
            <p>Access thousands of books, journals, and more, right from your home. Discover the world of online reading.</p>
            <a href="#features" class="btn">Explore Our Collection</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <div class="container">
            <h2>Why Choose Our Library?</h2>
            <div class="feature-item">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="Vast Collection">
                <h3>Vast Collection</h3>
                <p>Explore a wide variety of books and journals across different genres and subjects. Our collection is constantly updated to meet your needs.</p>
            </div>
            <div class="feature-item">
                <img src="https://images.unsplash.com/photo-1496104679561-38b3b4d6ef6b" alt="Easy Access">
                <h3>Easy Access</h3>
                <p>Our user-friendly platform allows you to easily search, borrow, and read your favorite books online anytime, anywhere.</p>
            </div>
            <div class="feature-item">
                <img src="https://images.unsplash.com/photo-1581322924803-4c15c5076b5e" alt="Personalized Recommendations">
                <h3>Personalized Recommendations</h3>
                <p>Get personalized book recommendations based on your reading preferences and interests.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Online Library. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
