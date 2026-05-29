<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Watercolor Dreams</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- NAVBAR -->

    <nav>

        <h2>Watercolor Dreams</h2>

        <div>
            <a href="#gallery">Gallery</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>

    </nav>


    <!-- HERO SECTION -->

    <section class="hero">

        <h1>Beautiful Watercolor Art</h1>

        <p>
            Explore dreamy watercolor paintings and soft pastel artwork.
        </p>

        <button onclick="showMessage()">
            Explore Now
        </button>

    </section>


    <!-- GALLERY -->

    <section class="gallery" id="gallery">

        <div class="card">
            <img src="https://picsum.photos/400?1">
            <h3>Pink Horizon</h3>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400?2">
            <h3>Ocean Mist</h3>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400?3">
            <h3>Golden Sunset</h3>
        </div>

    </section>


    <!-- ABOUT -->

    <section class="about" id="about">

        <h2>About This Gallery</h2>

        <p>
            This website is inspired by watercolor textures,
            calming colors, and modern art galleries.
        </p>

    </section>


    <!-- CONTACT -->

    <section class="contact" id="contact">

        <h2>Contact</h2>

        <input type="text" placeholder="Your Name">

        <input type="email" placeholder="Your Email">

        <textarea placeholder="Your Message"></textarea>

        <button>
            Send Message
        </button>

    </section>


    <!-- FOOTER -->

    <footer>

        <p>
            © 2026 Watercolor Dreams
        </p>

    </footer>


    <script src="script.js"></script>

</body>

</html>
