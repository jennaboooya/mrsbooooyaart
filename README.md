# mrsbooooyaart
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>mrsboooyaart</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000; /* Black background */
           :background-image: url('https://yourimagehosting.com/sloth-background.jpg');
            background-size: cover; /* Cover the whole screen */
            background-position: center center; /* Center the image */
            background-attachment: fixed; /* Keep the background fixed when scrolling */
            color: #fff; /* White text for contrast */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgba(75, 0, 130, 0.7); /* Dark purple with transparency */
            padding: 20px;
            text-align: center;
        }
        header h1 {
            color: #DDA0DD; /* Light purple for the main title */
            font-size: 3.5em;
            letter-spacing: 2px;
        }
        header p {
            color: #E6A8D7; /* Lighter purple for the subtitle */
            font-size: 1.2em;
            margin-top: 10px;
        }
        nav {
            background-color: rgba(46, 0, 79, 0.8); /* Dark purple for the navigation bar with opacity */
            text-align: center;
            padding: 12px;
        }
        nav a {
            color: #DDA0DD; /* Light purple for the nav links */
            text-decoration: none;
            margin: 0 25px;
            font-size: 1.2em;
            padding: 5px;
        }
        nav a:hover {
            color: #FF00FF; /* Bright purple hover effect */
            text-decoration: underline;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .portfolio-item {
            background-color: rgba(46, 0, 79, 0.8); /* Dark purple with transparency for items */
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        .portfolio-item img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .portfolio-item img:hover {
            transform: scale(1.05); /* Zoom effect on hover */
        }
        .portfolio-item h3 {
            margin-top: 15px;
            color: #DDA0DD; /* Light purple text */
            font-size: 1.5em;
        }
        .portfolio-item p {
            color: #E6A8D7; /* Lighter purple for the price */
            font-size: 1.1em;
            margin-top: 10px;
        }
        footer {
            background-color: rgba(46, 0, 79, 0.8); /* Dark purple footer */
            text-align: center;
            padding: 20px;
            color: #DDA0DD; /* Light purple text */
        }
        footer a {
            color: #FF00FF; /* Bright purple links in the footer */
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>mrsboooyaart</h1>
        <p>Where creativity meets craft. Explore posters & keychains that speak to you.</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to mrsboooyaart</h2>
        <p>Discover unique, handmade posters and keychains. Click on the portfolio below to explore my artwork.</p>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-grid">
            <!-- Example Item 1 (Poster) -->
            <div class="portfolio-item">
                <img src="poster1.jpg" alt="Poster 1">
                <h3>Poster Design 1</h3>
                <p>Price: $5 - $20</p>
            </div>
            <!-- Example Item 2 (Keychain) -->
            <div class="portfolio-item">
                <img src="keychain1.jpg" alt="Keychain 1">
                <h3>Keychain Design 1</h3>
                <p>Price: $5 - $10</p>
            </div>
            <!-- Add more items as needed -->
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm [Jenna], the artist behind mrsboooyaart. My journey started with a love for creating vibrant designs that could be held in your hand or displayed on your wall. I specialize in designing posters and keychains, each with a unique twist. Thanks for exploring my art!</p>
        <p>Poster prices range from $5 to $20 and keychains range from $5 to $10 depending on design complexity.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>If you're interested in a custom order or simply want to reach out, feel free to send me a message!</p>
        
        <h3>Payment Method:</h3>
        <p>For payment, send to my Cash App tag: <strong>$slothjen21</strong>.</p>
        

        <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
            <label for="name">Your Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Your Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Your Message:</label><br>
            <textarea id="message" name="message" required></textarea><br><br>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow me on <a href="https://instagram.com/mrsboooyaart" target="_blank">Instagram</a> | <a href="https://twitter.com/mrsboooyaart" target="_blank">Twitter</a></p>
        <p>&copy; 2025 mrsboooyaart</p>
    </footer>

</body>
</html>
