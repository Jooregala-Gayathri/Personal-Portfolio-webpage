
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jooregala Gayathri | Portfolio</title>

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" />

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="bg-dark text-white text-center py-4">
    <h1>Jooregala Gayathri</h1>
    <nav class="mt-3">
      <a href="#about" class="text-white mx-2">About</a>
      <a href="#projects" class="text-white mx-2">Projects</a>
      <a href="#contact" class="text-white mx-2">Contact</a>
    </nav>
  </header>

  <section id="about" class="container py-5">
    <h2>About Me</h2>
    <p>I’m a passionate front-end developer with a focus on responsive web design. I enjoy building user-friendly and accessible web experiences using HTML and CSS.</p>
  </section>

  <section id="projects" class="container py-5">
    <h2>Projects</h2>
    <div class="row">
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <h5 class="card-title">Survey Form</h5>
            <p class="card-text">A responsive survey form built using HTML and CSS.</p>
            <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-survey-form-project/build-a-survey-form" target="_blank" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <h5 class="card-title">Tribute Page</h5>
            <p class="card-text">A webpage dedicated to a famous figure, showcasing structured layout and design.</p>
            <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-tribute-page-project/build-a-tribute-page" target="_blank" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <h5 class="card-title">Technical Documentation</h5>
            <p class="card-text">A documentation page with sections, code blocks, and side navigation.</p>
            <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-technical-documentation-page-project/build-a-technical-documentation-page" target="_blank" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <h5 class="card-title">Product Landing Page</h5>
            <p class="card-text">A landing page with product details, images, and calls to action.</p>
            <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-product-landing-page-project/build-a-product-landing-page" target="_blank" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <h5 class="card-title">Portfolio Webpage</h5>
            <p class="card-text">A personal portfolio project to showcase web development work.</p>
            <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-personal-portfolio-webpage-project/build-a-personal-portfolio-webpage" target="_blank" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="container py-5">
    <h2>Contact</h2>
    <p><i class="fas fa-envelope"></i> <a href="mailto:jgayathri247@gmail.com">jgayathri247@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Jooregala Gayathri. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
<style>
/* Base styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f8f9fa;
  color: #333;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

/* Headings */
h1, h2 {
  font-weight: bold;
}

/* Header */
header {
  background: linear-gradient(to right, #0d6efd, #6610f2);
  color: white;
  padding: 2rem 0;
}

header nav a {
  color: #ffffff;
  font-weight: 500;
  margin: 0 1rem;
  text-decoration: none;
  transition: color 0.3s ease;
}

header nav a:hover {
  color: #ffc107;
  text-decoration: underline;
}

/* Section padding */
section {
  padding: 60px 0;
}

/* Cards */
.card {
  border: none;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.card:hover {
  transform: translateY(-5px);
}

/* Buttons */
.btn-primary {
  background-color: #0d6efd;
  border: none;
  font-weight: 500;
}

.btn-primary:hover {
  background-color: #0b5ed7;
}

/* Footer */
footer {
  background-color: #343a40;
  color: #fff;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 60px;
}

/* Contact section */
#contact a {
  color: #0d6efd;
  font-weight: 500;
}

#contact a:hover {
  text-decoration: underline;
}
</style>
