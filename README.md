# Teripehe-United
/* About Us Section */
#about-us {
  padding: 2rem;
  background: #f5f5f5;
  border-radius: 8px;
  margin: 1.5rem 0;
}
#about-us h2 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}
#about-us p {
  line-height: 1.6;
}
<section id="about-us">
  <h2>About Teripehe United</h2>
  <p>We are a passionate football team from Sri Lanka, bringing energy and teamwork to every match. Founded in 2023, we aim to inspire young athletes and make a mark in local tournaments.</p>
</section>
<section id="team-roster">
  <h2>Our Players</h2>
  <div class="player-card">
    <img src="players/player1.jpg" alt="Player 1">
    <h3>Harsha</h3>
    <p>Position: Forward<br>Jersey #: 10</p>
  </div>
</section>
<section id="contact">
  <h2>Contact Us</h2>
  <a href="https://wa.me/94771234567" class="button">Chat on WhatsApp</a>
</section>
#about-us, #team-roster, #contact {
  padding: 2rem;
  margin-bottom: 2rem;
  background-color: #f0f0f0;
  border-radius: 8px;
}

#team-roster .player-card {
  text-align: center;
  margin-top: 1rem;
}

.player-card img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 2px solid #333;
}

.button {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  background-color: #25D366;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}
/* Reset & base styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  background: #121212;
  color: #e0e0e0;
}

a {
  text-decoration: none;
  color: #81c784;
}

a:hover {
  color: #a5d6a7;
}

nav {
  background-color: #1e1e1e;
  padding: 1rem;
}

.nav-menu {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

.nav-menu li a {
  color: #81c784;
  font-weight: 600;
  padding-bottom: 0.25rem;
  border-bottom: 2px solid transparent;
}

.nav-menu li a.active,
.nav-menu li a:hover {
  border-color: #81c784;
}

header {
  padding: 3rem 1rem 1rem 1rem;
  text-align: center;
  background: #2e7d32;
  color: white;
}

section {
  padding: 2rem 1rem;
  max-width: 900px;
  margin: 0 auto;
}

.player-card {
  background: #263238;
  border-radius: 10px;
  padding: 1rem;
  margin: 1rem 0;
  text-align: center;
}

.player-card img {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  margin-bottom: 1rem;
}

table {
  width: 100%;
  border-collapse: collapse;
  background: #263238;
  border-radius: 10px;
  overflow: hidden;
}

th, td {
  padding: 0.75rem 1rem;
  text-align: left;
  border-bottom: 1px solid #424242;
}

th {
  background: #1b5e20;
}

tr:hover {
  background-color: #37474f;
}

