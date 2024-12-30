<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gamers Paradise Entertainment</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
        }
        header {
            background-color: #1e88e5;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0d47a1;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('gaming-background.jpg') no-repeat center center/cover;
        }
        .hero h2 {
            font-size: 2.5em;
            margin: 0;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
        }
        .section h3 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background-color: #1e1e1e;
            border: 1px solid #333;
            padding: 20px;
            border-radius: 10px;
        }
        .card img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #0d47a1;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gamers Paradise Entertainment</h1>
    </header>
    <nav>
        <a href="#gaming">Gaming Sessions</a>
        <a href="#sales">Posters & Games</a>
        <a href="#accessories">Accessories</a>
        <a href="#party">Party Bookings</a>
    </nav>
    <section class="hero">
        <h2>Your One-Stop Hub for Gaming, Entertainment & More!</h2>
    </section>
    <section id="gaming" class="section">
        <h3>Gaming Sessions</h3>
        <p>Immerse yourself in thrilling gaming experiences with our state-of-the-art gaming consoles and VR setups.</p>
        <div class="cards">
            <div class="card">
                <img src="vr-session.jpg" alt="VR Session">
                <h4>VR Sessions</h4>
                <p>Experience the future of gaming with our Oculus Quest 2 and PSVR.</p>
            </div>
            <div class="card">
                <img src="console-gaming.jpg" alt="Console Gaming">
                <h4>Console Gaming</h4>
                <p>Play your favorite games on PS4, PS3, Xbox 360, and more!</p>
            </div>
        </div>
    </section>
    <section id="sales" class="section">
        <h3>Posters & Video Game Sales</h3>
        <p>Explore our collection of movies, series, original posters, and the latest video games.</p>
    </section>
    <section id="accessories" class="section">
        <h3>Gaming Accessories</h3>
        <p>Shop for gaming fashion, controllers, and other essential gaming gear.</p>
        <div class="cards">
            <div class="card">
                <img src="controller.jpg" alt="Gaming Controller">
                <h4>Controllers</h4>
                <p>High-quality controllers for an unbeatable gaming experience.</p>
            </div>
            <div class="card">
                <img src="gaming-fashion.jpg" alt="Gaming Fashion">
                <h4>Gaming Fashion</h4>
                <p>Trendy clothing and accessories for gamers.</p>
            </div>
        </div>
    </section>
    <section id="party" class="section">
        <h3>Party Bookings</h3>
        <p>Celebrate birthdays and special occasions with our gaming-themed party packages!</p>
    </section>
    <footer>
        <p>&copy; 2024 Gamers Paradise Entertainment. All Rights Reserved.</p>
    </footer>
</body>
</html>
