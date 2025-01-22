<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>प्रज्ञसंस्कार - Cultivating Wisdom & Values</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="app-title">
      <h1>प्रज्ञसंस्कार</h1>
      <p class="subtitle">Cultivating Wisdom & Values</p>
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#activities">Activities</a></li>
        <li><a href="#uploading">Upload</a></li>
        <li><a href="#exploring">Explore</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Page Section -->
  <section id="home" class="home-section">
    <div class="profile-info">
      <img src="profile-placeholder.jpg" alt="User Profile" class="profile-pic">
      <div class="user-details">
        <p><strong>Name:</strong> [User’s Name]</p>
        <p><strong>Age:</strong> [User’s Age]</p>
        <p><strong>Gender:</strong> [User’s Gender]</p>
      </div>
    </div>

    <div class="activities-log">
      <h2>Recent Activities</h2>
      <ul>
        <li>Reflecting on Wisdom Texts</li>
        <li>Mindfulness Practice</li>
        <li>Cultivating Compassion</li>
      </ul>
    </div>

    <div class="quote-section">
      <p>"Wisdom is the foundation of a fulfilling life."</p>
    </div>
  </section>

  <!-- Activities Section -->
  <section id="activities" class="activities-section">
    <h2>Activities</h2>
    <div class="activity-list">
      <div class="activity-item">
        <h3>Mindfulness Practices</h3>
        <p>Engage in practices that cultivate presence and awareness.</p>
      </div>
      <div class="activity-item">
        <h3>Philosophical Reflections</h3>
        <p>Reflect on ancient teachings and philosophical wisdom.</p>
      </div>
      <div class="activity-item">
        <h3>Developing Empathy and Compassion</h3>
        <p>Explore exercises that nurture compassion for self and others.</p>
      </div>
    </div>
  </section>

  <!-- Uploading Section -->
  <section id="uploading" class="uploading-section">
    <h2>Upload Your Wisdom</h2>
    <p>Share your thoughts, images, or experiences with us.</p>
    <button class="upload-btn">Share Your Wisdom</button>
  </section>

  <!-- Exploring Section -->
  <section id="exploring" class="exploring-section">
    <h2>Explore Wisdom</h2>
    <p>Discover teachings, articles, and discussions on wisdom.</p>
    <div class="explore-categories">
      <div class="category-card">
        <h3>Articles on Ancient Wisdom</h3>
      </div>
      <div class="category-card">
        <h3>Mindfulness Practices</h3>
      </div>
      <div class="category-card">
        <h3>Thoughtful Conversations</h3>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <div class="footer-content">
      <p>"Cultivate wisdom, and the world will be brighter."</p>
      <p>&copy; 2025 प्रज्ञसंस्कार. All Rights Reserved.</p>
      <div class="footer-links">
        <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a> | <a href="#">Contact Us</a>
      </div>
    </div>
  </footer>
</body>
</html>
/* General Styling */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}

h1, h2, h3 {
  color: #2C3E50;
}

/* Header Section */
header {
  background: linear-gradient(135deg, #F9E79F, #F5B041);
  padding: 20px;
  text-align: center;
  color: #fff;
}

header .app-title h1 {
  font-family: 'Merriweather', serif;
  font-size: 3rem;
}

header .app-title .subtitle {
  font-size: 1.2rem;
  font-style: italic;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  margin-top: 10px;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1.1rem;
}

nav ul li a:hover {
  text-decoration: underline;
}

/* Home Page Section */
.home-section {
  padding: 20px;
  text-align: center;
}

.profile-info {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 30px;
}

.profile-info .profile-pic {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-right: 20px;
}

.user-details p {
  margin-bottom: 5px;
}

.activities-log ul {
  list-style: none;
  margin: 20px 0;
}

.activities-log li {
  padding: 5px 0;
}

.quote-section p {
  font-style: italic;
  font-size: 1.2rem;
  margin-top: 20px;
}

/* Activities Section */
.activities-section {
  padding: 40px;
  background: #f0f0f0;
}

.activity-list {
  display: flex;
  justify-content: space-between;
}

.activity-item {
  background: #fff;
  padding: 15px;
  border-radius: 10px;
  width: 30%;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.activity-item h3 {
  margin-bottom: 10px;
}

/* Uploading Section */
.uploading-section {
  padding: 30px;
  background: #F1C40F;
  text-align: center;
}

.upload-btn {
  background-color: #2C3E50;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1rem;
}

.upload-btn:hover {
  background-color: #34495E;
}

/* Exploring Section */
.exploring-section {
  padding: 30px;
}

.explore-categories {
  display: flex;
  justify-content: space-between;
}

.category-card {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  width: 30%;
  text-align: center;
}

.category-card h3 {
  font-size: 1.3rem;
  color: #F39C12;
}

/* Footer Section */
footer {
  background: #2C3E50;
  color: white;
  padding: 20px;
  text-align: center;
}

footer .footer-content p {
  margin: 10px 0;
}

footer .footer-links a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
}

footer .footer-links a:hover {
  text-decoration: underline;
}
