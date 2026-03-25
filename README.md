<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Beverages Co.</title>
    <style>
        /* Base Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            color: #333;
        }

        /* Navigation Bar */
        header {
            background-color: #004B93; /* Corporate Blue */
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            letter-spacing: 1px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 1.5rem;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #ffc425; /* Accent yellow */
        }

        /* Hero Section */
        .hero {
            background-color: #f4f4f9;
            text-align: center;
            padding: 6rem 2rem;
            border-bottom: 4px solid #004B93;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            color: #004B93;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem auto;
            color: #555;
        }

        .btn {
            background-color: #004B93;
            color: white;
            padding: 10px 24px;
            text-decoration: none;
            border-radius: 25px;
            font-size: 1.1rem;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #003366;
        }

        /* Brand Showcase Grid */
        .brands-section {
            padding: 4rem 2rem;
            text-align: center;
        }

        .brands-section h2 {
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #004B93;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .brand-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }

        .brand-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        }

        .brand-card h3 {
            color: #004B93;
            margin-top: 0;
        }

        /* Footer */
        footer {
            background-color: #1a1a1a;
            color: #f1f1f1;
            padding: 3rem 2rem;
            text-align: center;
        }

        .footer-links {
            margin-bottom: 1.5rem;
        }

        .footer-links a {
            color: #f1f1f1;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 0.9rem;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">GLOBAL BEVERAGES</div>
        <nav>
            <a href="#brands">Our Brands</a>
            <a href="#sustainability">Sustainability</a>
            <a href="#investors">Investors</a>
            <a href="#careers">Careers</a>
            <a href="#about">About Us</a>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Refreshing the World</h1>
            <p>Creating smiles with every sip and every bite. Discover our portfolio of iconic brands designed for every moment of your day.</p>
            <a href="#brands" class="btn">Explore Our Products</a>
        </section>

        <section id="brands" class="brands-section">
            <h2>Our Signature Brands</h2>
            <div class="grid-container">
                <div class="brand-card">
                    <h3>Classic Cola</h3>
                    <p>The original, bold flavor that started it all. Perfect for any occasion.</p>
                </div>
                <div class="brand-card">
                    <h3>Citrus Splash</h3>
                    <p>A crisp, refreshing lemon-lime burst to keep you energized.</p>
                </div>
                <div class="brand-card">
                    <h3>Pure Springs</h3>
                    <p>100% natural mountain spring water. Stay hydrated naturally.</p>
                </div>
                <div class="brand-card">
                    <h3>Energy Max</h3>
                    <p>When you need that extra push to get through your workday or workout.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-links">
            <a href="#">Contact Us</a>
            <a href="#">Terms of Use</a>
            <a href="#">Privacy Policy</a>
            <a href="#">Accessibility</a>
        </div>
        <p>&copy; 2026 Global Beverages Co. All rights reserved.</p>
    </footer>

</body>
</html>
