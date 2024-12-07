# Syam-protofolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Katakamsetti Syam Sai - Portfolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Katakamsetti Syam Sai</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Home Section -->
<section id="home" class="d-flex align-items-center text-center bg-primary text-white vh-100">
  <div class="container">
    <h1>Hi, I'm Katakamsetti Syam Sai</h1>
    <p>Computer Science Engineer & Business Systems Specialist</p>
    <a href="#projects" class="btn btn-light btn-lg">View My Work</a>
    <a href="#contact" class="btn btn-outline-light btn-lg">Contact Me</a>
  </div>
</section>

<!-- About Section -->
<section id="about" class="py-5">
  <div class="container text-center">
    <h2>About Me</h2>
    <p class="lead">Driven and detail-oriented Computer Science Engineer specializing in Business Systems. Passionate about data analysis, machine learning, and impactful projects.</p>
  </div>
</section>

<!-- Projects Section -->
<section id="projects" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">My Projects</h2>
    <div class="row">
      <div class="col-md-6">
        <div class="card shadow-sm">
          <div class="card-body">
            <h3 class="card-title">House Price Prediction Model</h3>
            <p><strong>Technologies Used:</strong> Python, Jupyter Notebook, GUI</p>
            <p>Developed a machine learning model to predict house prices based on features like location, size, and property age. The model offers reliable pricing estimates, supporting real estate professionals and buyers.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Skills Section -->
<section id="skills" class="py-5">
  <div class="container text-center">
    <h2>My Skills & Certifications</h2>
    <div class="row">
      <div class="col-md-4">
        <h4>Technical Skills</h4>
        <ul class="list-unstyled">
          <li>Python</li>
          <li>HTML, CSS, Bootstrap</li>
          <li>Power BI, Tableau</li>
          <li>Data Structures & Algorithms</li>
          <li>Team Player</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h4>Cloud & Tools</h4>
        <ul class="list-unstyled">
          <li>AWS (Certified)</li>
          <li>Data Visualization (IBM Certified)</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center">Contact Me</h2>
    <p class="text-center">Email: <a href="mailto:syamsai470@gmail.com">syamsai470@gmail.com</a> | Phone: <a href="tel:+919391578787">+91 9391578787</a></p>
    <form action="submit_form.php" method="POST">
      <div class="row">
        <div class="col-md-6 mb-3">
          <input type="text" name="name" class="form-control" placeholder="Your Name" required>
        </div>
        <div class="col-md-6 mb-3">
          <input type="email" name="email" class="form-control" placeholder="Your Email" required>
        </div>
      </div>
      <div class="mb-3">
        <textarea name="message" class="form-control" placeholder="Your Message" rows="5" required></textarea>
      </div>
      <div class="text-center">
        <button type="submit" class="btn btn-primary">Send</button>
      </div>
    </form>
  </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
  <p>&copy; 2024 Katakamsetti Syam Sai. All Rights Reserved.</p>
</footer>

</body>
</html>
