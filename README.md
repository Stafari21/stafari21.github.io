<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Braille Phone Tablet</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    .hero {
      background-color: #007bff;
      color: white;
      padding: 50px 0;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
    }
    .hero p {
      font-size: 1.2rem;
    }
    .section-title {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .feature-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 30px;
    }
    .feature-item {
      width: 30%;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-bottom: 30px;
    }
    .feature-item h3 {
      color: #007bff;
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 1.5rem;
      }
      .hero p {
        font-size: 1rem;
      }
      .hero {
        padding: 30px 0;
      }
      .feature-item {
        width: 100%;
      }
    }

    /* Hover effect for the "Watch Demo" button */
    .btn-primary:hover {
      background-color: #0056b3;
      color: white;
      transition: background-color 0.3s;
    }
  </style>
</head>
<body>

  <header>
    <div class="hero">
      <h1>Introducing the Braille Phone Tablet</h1>
      <p>Empowering the visually impaired with a seamless device for communication and accessibility.</p>
      <a href="#product" class="btn btn-light btn-lg" aria-label="Learn more about the Braille Phone Tablet">Learn More</a>
    </div>
  </header>

  <main>
    <section id="product" class="container py-5">
      <h2 class="section-title">Key Features</h2>
      <div class="feature-list">
        <div class="feature-item">
          <h3>Braille Input & Output</h3>
          <p>Experience tactile feedback with a Braille pad for easy text input and reading.</p>
        </div>
        <div class="feature-item">
          <h3>Screen Reader Compatible</h3>
          <p>Full compatibility with screen readers ensures every interaction is seamless.</p>
        </div>
        <div class="feature-item">
          <h3>Ergonomic Design</h3>
          <p>Lightweight, portable, and designed for comfort, making it perfect for everyday use.</p>
        </div>
      </div>
    </section>

    <section class="container py-5">
      <h2 class="section-title">How It Works</h2>
      <p>Our phone-tablet with Braille technology works seamlessly with both text-based and voice-based interactions. Watch the demo below:</p>
      <a href="demo_video.mp4" class="btn btn-primary" aria-label="Watch the demo of Braille Phone Tablet">Watch Demo</a>
    </section>
  </main>

  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; 2024 Braille Tech. All rights reserved.</p>
    <p><a href="contact.html" class="text-white">Contact Us</a> | <a href="privacy.html" class="text-white">Privacy Policy</a></p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
