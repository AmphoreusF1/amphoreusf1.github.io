/* Global Styles */
body {
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    background-color: #0b0b0b;
    color: #f5f5f5;
}

a {
    text-decoration: none;
    color: #f5f5f5;
}

nav {
    background-color: #0b0b0b;
    border-bottom: 2px solid #e50914;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 10px 0;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav a:hover {
    color: #e50914;
    border-bottom: 2px solid #e50914;
    padding-bottom: 2px;
}

header {
    text-align: center;
    padding: 60px 20px;
}

header h1 {
    font-family: 'Orbitron', sans-serif;
    color: #e50914;
    font-size: 48px;
    margin: 0;
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

h2 {
    color: #e50914;
    text-align: center;
    margin-bottom: 30px;
}

.grid {
    display: grid;
    gap: 20px;
}

.team-grid, .gallery-grid, .sponsors-grid {
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    display: grid;
}

.team-member {
    text-align: center;
}

.team-member img {
    width: 100%;
    height: auto;
    border: 2px solid #e50914;
    border-radius: 5px;
}

.team-member p {
    margin-top: 10px;
    font-style: italic;
    color: #aaaaaa;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0b0b0b;
    border-top: 2px solid #e50914;
    margin-top: 50px;
    font-size: 14px;
}

/* Responsive */
@media(max-width: 768px) {
    header h1 { font-size: 36px; }
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Amphoreus F1 - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <header>
        <h1>Amphoreus F1</h1>
        <p>Racing into STEM Excellence</p>
    </header>

    <div class="container">
        <h2>Welcome to Amphoreus F1</h2>
        <p style="text-align:center;">Your premier STEM racing team, combining science, engineering, and speed. Explore our team, our car, and our journey to the podium.</p>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Us - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>About Us</h2>
        <p>Amphoreus F1 is a STEM racing team dedicated to pushing the limits of science, technology, and engineering in motorsport. Our mission is to inspire innovation, teamwork, and a love for speed among the next generation of engineers.</p>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Team Members - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>Our Team</h2>
        <div class="team-grid">
            <!-- Example Team Member -->
            <div class="team-member">
                <img src="images/member1.jpg" alt="Member 1">
                <p>"Racing is science in motion."</p>
            </div>
            <div class="team-member">
                <img src="images/member2.jpg" alt="Member 2">
                <p>"Engineering speed, engineering success."</p>
            </div>
            <div class="team-member">
                <img src="images/member3.jpg" alt="Member 3">
                <p>"STEM fuels our drive."</p>
            </div>
        </div>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Team Members - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>Our Team</h2>
        <div class="team-grid">
            <!-- Example Team Member -->
            <div class="team-member">
                <img src="images/member1.jpg" alt="Member 1">
                <p>"Racing is science in motion."</p>
            </div>
            <div class="team-member">
                <img src="images/member2.jpg" alt="Member 2">
                <p>"Engineering speed, engineering success."</p>
            </div>
            <div class="team-member">
                <img src="images/member3.jpg" alt="Member 3">
                <p>"STEM fuels our drive."</p>
            </div>
        </div>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gallery - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <!-- 18 placeholder images -->
            <img src="images/photo1.jpg" alt="Gallery 1" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo2.jpg" alt="Gallery 2" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo3.jpg" alt="Gallery 3" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo4.jpg" alt="Gallery 4" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo5.jpg" alt="Gallery 5" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo6.jpg" alt="Gallery 6" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo7.jpg" alt="Gallery 7" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo8.jpg" alt="Gallery 8" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo9.jpg" alt="Gallery 9" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo10.jpg" alt="Gallery 10" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo11.jpg" alt="Gallery 11" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo12.jpg" alt="Gallery 12" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo13.jpg" alt="Gallery 13" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo14.jpg" alt="Gallery 14" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo15.jpg" alt="Gallery 15" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo16.jpg" alt="Gallery 16" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo17.jpg" alt="Gallery 17" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/photo18.jpg" alt="Gallery 18" style="width:100%;border:2px solid #e50914;border-radius:5px;">
        </div>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sponsors - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>Our Sponsors</h2>
        <div class="sponsors-grid">
            <img src="images/sponsor1.png" alt="Sponsor 1" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/sponsor2.png" alt="Sponsor 2" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/sponsor3.png" alt="Sponsor 3" style="width:100%;border:2px solid #e50914;border-radius:5px;">
            <img src="images/sponsor4.png" alt="Sponsor 4" style="width:100%;border:2px solid #e50914;border-radius:5px;">
        </div>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - Amphoreus F1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="team.html">Team Members</a>
        <a href="car.html">Car Design</a>
        <a href="gallery.html">Gallery</a>
        <a href="sponsors.html">Sponsors</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h2>Contact Us</h2>
        <p>Email us at: <strong>amphoreusf1@gmail.com</strong></p>
    </div>

    <footer>
        © 2025 Amphoreus F1
    </footer>
</body>
</html>
