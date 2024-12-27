<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bikes Showcase</title>
    <style>
        /* General Body Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212; /* Deep Black Background */
            color: #e0e0e0; /* Light Gray Text for Contrast */
            line-height: 1.6;
        }

        /* Header Styling */
        header {
            background: linear-gradient(90deg, #1f1f1f, #333333); /* Gradient Effect */
            color: #f5f5f5; /* Soft White Text */
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.3); /* Subtle Shadow */
            font-size: 2rem;
        }

        /* Navigation Menu */
        nav {
            background-color: #1a1a1a;
            display: flex;
            justify-content: center;
            border-bottom: 2px solid #333;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.5);
        }

        nav a {
            color: #9e9e9e;
            text-decoration: none;
            padding: 1rem 2rem;
            display: block;
            font-size: 1.1rem;
            transition: color 0.3s, background-color 0.3s;
        }

        nav a:hover {
            background-color: #333;
            color: #ffffff;
        }

        /* Section Styling */
        section {
            padding: 3rem 2rem;
        }

        section h2 {
            font-size: 2rem;
            color: #f5f5f5;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Text Shadow for Header */
        }

        section p {
            color: #bdbdbd; /* Slightly Muted Text */
        }

        /* Gallery Styling */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.5); /* Stronger Shadow for Images */
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05); /* Zoom Effect */
            box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.8);
        }

        .bike-info {
            margin-top: 0.8rem;
            font-size: 1rem;
            color: #a0a0a0;
        }

        /* Footer Styling */
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #1a1a1a;
            color: #9e9e9e;
            border-top: 2px solid #333;
            font-size: 0.9rem;
        }

        footer p:hover {
            color: #ffffff; /* Footer Text Hover Effect */
        }

        /* Responsive Styling */
        @media (max-width: 600px) {
            nav {
                flex-wrap: wrap;
            }

            nav a {
                padding: 1rem;
            }

            section {
                padding: 2rem 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Explore the World of Bikes</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#mountain">Mountain Bikes</a>
        <a href="#road">Road Bikes</a>
        <a href="#hybrid">Hybrid Bikes</a>
        <a href="#electric">Electric Bikes</a>
    </nav>

    <section id="home">
        <h2>Welcome</h2>
        <p>Discover the best bikes for every terrain and purpose. Navigate through our sections to learn more about different bike types and their unique features.</p>
    </section>

    <section id="mountain">
        <h2>Mountain Bikes</h2>
        <div class="gallery">
            <div>
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v1.jpg" alt="Mountain Bike 1 View 1">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v2.jpg" alt="Mountain Bike 1 View 2">
                <img src="https://raw.githubusercontent.com/charan-2028/BikeHub.GITHUB.1OQ/d371e3dd7b11df2dfb62a6013797b68c6a723e98/v3.jpg" alt="Mountain Bike 1 View 3">
                <p class="bike-info">
                    The Triumph Tiger 900 is a versatile, middleweight adventure motorcycle designed for both on-road and off-road performance. It is part of Triumph’s iconic Tiger series and offers a perfect balance of power, technology, and comfort, making it a favorite among adventure bike enthusiasts.
                </p>
            </div>
        </div>
    </section>

    <!-- Road Bikes Section -->
    <!-- Hybrid Bikes Section -->
    <!-- Electric Bikes Section -->

    <footer>
        <p>&copy; 2024 Bikes Showcase. All rights reserved.</p>
    </footer>
</body>
</html>
