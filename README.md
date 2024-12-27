<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bikes Showcase</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem 1.5rem;
            display: block;
        }

        nav a:hover {
            background-color: #555;
        }

        section {
            padding: 2rem;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .bike-info {
            margin-top: 0.5rem;
            font-size: 1rem;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 600px) {
            nav {
                flex-wrap: wrap;
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
                <img src="mountain-bike1-1.jpg" alt="Mountain Bike 1 View 1">
                <img src="mountain-bike1-2.jpg" alt="Mountain Bike 1 View 2">
                <img src="mountain-bike1-3.jpg" alt="Mountain Bike 1 View 3">
                <p class="bike-info">Durable bike for off-road trails. Ideal for adventure enthusiasts.</p>
            </div>
            <div>
                <img src="mountain-bike2-1.jpg" alt="Mountain Bike 2 View 1">
                <img src="mountain-bike2-2.jpg" alt="Mountain Bike 2 View 2">
                <img src="mountain-bike2-3.jpg" alt="Mountain Bike 2 View 3">
                <p class="bike-info">Equipped with powerful suspension for rugged terrain.</p>
            </div>
        </div>
    </section>

    <section id="road">
        <h2>Road Bikes</h2>
        <div class="gallery">
            <div>
                <img src="road-bike1-1.jpg" alt="Road Bike 1 View 1">
                <img src="road-bike1-2.jpg" alt="Road Bike 1 View 2">
                <img src="road-bike1-3.jpg" alt="Road Bike 1 View 3">
                <p class="bike-info">Lightweight and aerodynamic for smooth pavement rides.</p>
            </div>
            <div>
                <img src="road-bike2-1.jpg" alt="Road Bike 2 View 1">
                <img src="road-bike2-2.jpg" alt="Road Bike 2 View 2">
                <img src="road-bike2-3.jpg" alt="Road Bike 2 View 3">
                <p class="bike-info">Engineered for speed and long-distance cycling.</p>
            </div>
        </div>
    </section>

    <section id="hybrid">
        <h2>Hybrid Bikes</h2>
        <div class="gallery">
            <div>
                <img src="hybrid-bike1-1.jpg" alt="Hybrid Bike 1 View 1">
                <img src="hybrid-bike1-2.jpg" alt="Hybrid Bike 1 View 2">
                <img src="hybrid-bike1-3.jpg" alt="Hybrid Bike 1 View 3">
                <p class="bike-info">Combines the features of road and mountain bikes for versatility.</p>
            </div>
            <div>
                <img src="hybrid-bike2-1.jpg" alt="Hybrid Bike 2 View 1">
                <img src="hybrid-bike2-2.jpg" alt="Hybrid Bike 2 View 2">
                <img src="hybrid-bike2-3.jpg" alt="Hybrid Bike 2 View 3">
                <p class="bike-info">Comfortable design for urban commuting and leisure rides.</p>
            </div>
        </div>
    </section>

    <section id="electric">
        <h2>Electric Bikes</h2>
        <div class="gallery">
            <div>
                <img src="electric-bike1-1.jpg" alt="Electric Bike 1 View 1">
                <img src="electric-bike1-2.jpg" alt="Electric Bike 1 View 2">
                <img src="electric-bike1-3.jpg" alt="Electric Bike 1 View 3">
                <p class="bike-info">Eco-friendly bike with pedal assist for effortless rides.</p>
            </div>
            <div>
                <img src="electric-bike2-1.jpg" alt="Electric Bike 2 View 1">
                <img src="electric-bike2-2.jpg" alt="Electric Bike 2 View 2">
                <img src="electric-bike2-3.jpg" alt="Electric Bike 2 View 3">
                <p class="bike-info">High-performance battery and sleek design.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Bikes Showcase. All rights reserved.</p>
    </footer>

    <script>
        // Add interactivity if needed
        console.log('Welcome to Bikes Showcase!');
    </script>
</body>
</html>
