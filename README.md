<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Home Airlines</title>

    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: Arial, sans-serif; color: #333; }

        header {
            background-color: #1a3a5c;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            display: flex;
            flex-wrap: wrap;
            list-style: none;
            padding: 0 20px;
        }

        nav ul li a {
            color: #e8f0f8;
            text-decoration: none;
            font-size: 14px;
            padding: 14px 12px;
            display: block;
        }

        nav ul li a:hover { background-color: #2a5a8c; }

        /* HOME */
        #home {
            position: relative;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background-color: #1a3a5c;
        }

        .home-video {
            position: absolute;
            top: 0; left: 0;
            width: 100%; height: 100%;
            object-fit: cover;
            opacity: 0.5;
        }

        .content {
            position: relative;
            z-index: 1;
            color: white;
        }

        .content h1 { font-size: 3rem; }
        .content p { font-size: 1.2rem; }

        section { padding: 60px 40px; }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 20px;
        }

        .card {
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            text-align: center;
        }

        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .card h3 { padding: 10px; }
    </style>
</head>

<body>

<header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#destinations">Destinations</a></li>
            <li><a href="#AboutUs">About Us</a></li>
        </ul>
    </nav>
</header>

<!-- HOME -->
<section id="home">

    <video autoplay muted loop class="home-video">
        <source src="videos/home.mp4" type="video/mp4">
    </video>

    <div class="content">
        <h1>Explore The World ✈️</h1>
        <p>Travel with us</p>
    </div>

</section>

<!-- DESTINATIONS -->
<section id="destinations">
    <h2>Destinations</h2>

    <div class="container">

        <div class="card">
            <img src="images/France.jpeg">
            <h3>France</h3>
        </div>

        <div class="card">
            <img src="images/Dubai.jpeg">
            <h3>Dubai</h3>
        </div>

        <div class="card">
            <img src="images/Italy.jpeg">
            <h3>Italy</h3>
        </div>

        <div class="card">
            <img src="images/Turkey.jpeg">
            <h3>Turkey</h3>
        </div>

        <div class="card">
            <img src="images/London.jpeg">
            <h3>London</h3>
        </div>

        <div class="card">
            <img src="images/USA.jpeg">
            <h3>USA</h3>
        </div>

        <div class="card">
            <img src="images/Egypt.jpeg">
            <h3>Egypt</h3>
        </div>

        <div class="card">
            <img src="images/Kuwait.jpeg">
            <h3>Kuwait</h3>
        </div>

        <div class="card">
            <img src="images/AbuDhabi.jpeg">
            <h3>Abu Dhabi</h3>
        </div>

        <div class="card">
            <img src="images/India.jpeg">
            <h3>India</h3>
        </div>

    </div>
</section>

<!-- ABOUT -->
<section id="AboutUs">
    <h2>About Us</h2>
    <p>We are a leading travel company offering the best trips around the world.</p>
</section>

</body>
</html>
