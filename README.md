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

    /* Hover effect for the "Learn More" button */
    .btn-primary:hover {
      background-color: #0056b3;
      color: white;
      transition: background-color 0.3s;
    }

    /* Style for the Privacy Policy content */
    .privacy-content {
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* Style for the Contact Us section */
    .contact-us-section {
      display: none; /* Make sure it's hidden by default */
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
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
    <!-- Product Overview Section -->
    <section id="overview" class="container py-5">
      <h2 class="section-title">Product Overview</h2>
      <p>The Braille Phone Tablet is designed to provide visually impaired individuals with a device that offers both accessibility and independence...</p>
    </section>

    <!-- Key Features Section -->
    <section id="product" class="container py-5">
      <h2 class="section-title">Key Features</h2>
      <div class="feature-list">
        <div class="feature-item">
          <h3>Braille Function</h3>
          <p>The Braille Phone Tablet features a Braille pad for both text input and output...</p>
        </div>
        <div class="feature-item">
          <h3>Screen Reader Compatibility</h3>
          <p>Fully compatible with screen readers, the Braille Phone Tablet ensures that every action...</p>
        </div>
        <div class="feature-item">
          <h3>Ergonomic Design</h3>
          <p>With its lightweight, portable design, the Braille Phone Tablet is comfortable to hold...</p>
        </div>
      </div>
    </section>

    <!-- New Section: Testing & User Feedback -->
    <section id="testing" class="container py-5">
      <h2 class="section-title">Testing & User Feedback</h2>
      <p>Thorough user testing is a crucial part of the development process...</p>
    </section>
  </main>

  <!-- Footer Section -->
  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; 2024 Braille Tech. All rights reserved.</p>
    <p>
      <a href="javascript:void(0);" id="contact-link" class="text-white">Contact Us</a> | 
      <a href="#" class="text-white" data-bs-toggle="collapse" data-bs-target="#privacy-policy" aria-expanded="false" aria-controls="privacy-policy">Privacy Policy</a>
    </p>
  </footer>

  <!-- Collapsible Privacy Policy Section -->
  <div class="collapse" id="privacy-policy">
    <section class="container py-5">
      <div class="privacy-content">
        <h2 class="section-title">Privacy Policy for Phone Table with Braille Pad</h2>
        <p><strong>Effective Date</strong>: February 1, 2033</p>
        <h3>1. Information Collection</h3>
        <p>We do not collect any personal information when you use the Device...</p>
      </div>
    </section>
  </div>

  <!-- Hidden Contact Us Section -->
  <div id="contact-us" class="contact-us-section">
    <h2 class="section-title">Contact Us</h2>
    <p>If you have any questions or need assistance, please reach out to us. Our team is happy to help!</p>
    <p><strong>Phone:</strong> 347-554-3087</p>
    <p><strong>Email:</strong> stafari.thomas1@sfc.edu</p>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // Toggle the visibility of the Contact Us section when the link is clicked
    document.getElementById('contact-link').addEventListener('click', function() {
      var contactSection = document.getElementById('contact-us');
      // Toggle visibility of the Contact Us section
      if (contactSection.style.display === 'none' || contactSection.style.display === '') {
        contactSection.style.display = 'block';
      } else {
        contactSection.style.display = 'none';
      }
    });
  </script>
</body>
</html>
