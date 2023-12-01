<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name - Personal Website</title>
<style>
  body { font-family: Arial, sans-serif; }
  .container { width: 80%; margin: auto; }
  header, footer { text-align: center; padding: 1em; }
  nav { text-align: center; padding: 1em; }
  nav ul { list-style-type: none; padding: 0; }
  nav ul li { display: inline; margin-right: 20px; }
  section { margin-bottom: 20px; }
  .biography, .resume, .contact { padding: 1em; border: 1px solid #ccc; }
</style>
</head>
<body>
<div class="container">
  <header>
    <h1>Your Name</h1>
    <p>Welcome to my personal website!</p>
  </header>
  
  <nav>
    <ul>
      <li><a href="#biography">Biography</a></li>
      <li><a href="#resume">Resume</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  
  <section id="biography" class="biography">
    <h2>Biography</h2>
    <p>Here you can write about your background, education, and interests.</p>
  </section>
  
  <section id="resume" class="resume">
    <h2>Resume</h2>
    <p>Include your professional experience, skills, and achievements here.</p>
  </section>
  
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out to me at:</p>
    <p>Email: your.email@example.com</p>
    <p>Phone: +1234567890</p>
  </section>
  
  <footer>
    <p>© 2023 Your Name</p>
  </footer>
</div>

<script>
  // You can add JavaScript here for interactive features.
</script><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name - Personal Website</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
<style>
  /* Add your CSS styles here */
  /* Example of responsive design */
  @media (max-width: 600px) {
    .container { width: 100%; }
    nav ul li { display: block; margin-bottom: 10px; }
  }
  /* Rest of the styles */
</style>
</head>
<body>
<div class="container">
  <!-- Rest of the HTML content -->
  
  <section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <!-- Add your portfolio items here -->
  </section>
  
  <section id="testimonials" class="testimonials">
    <h2>Testimonials</h2>
    <!-- Add testimonials here -->
  </section>
  
  <footer>
    <div class="social-media">
      <!-- Add your social media links here -->
      <a href="https://www.linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://www.github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
      <!-- More social media icons -->
    </div>
    <p>© 2023 Your Name</p>
  </footer>
</div>

<script>
  // Add your JavaScript here
  // Example of smooth scrolling
  document.querySelectorAll('nav ul li a').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const targetId = this.getAttribute('href');
      document.querySelector(targetId).scrollIntoView({
        behavior: 'smooth'
      });
    });
  });
</script>
</body>
</html>

</body>
</html>
