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
      <p>The Braille Phone Tablet is designed to provide visually impaired individuals with a device that offers both accessibility and independence. This innovative tablet integrates tactile Braille functionality, allowing users to easily interact with technology through touch, ensuring a seamless, hands-on experience.</p>

      <p>This product is crafted specifically for visually impaired individuals who are often limited by the lack of tactile feedback in typical devices. The Braille Phone Tablet solves this problem by providing a built-in Braille interface, enabling users to read and input text without relying on voice commands or traditional touch screens. The tablet’s ergonomic design ensures comfort, making it easy to hold and use for extended periods of time.</p>

      <p>In addition to its Braille capabilities, the tablet comes equipped with a large, easy-to-read screen and incorporates voice control for added flexibility. The device is perfect for everyday tasks such as messaging, browsing the internet, and accessing apps, all while ensuring that users can do so independently and efficiently. Whether for communication, entertainment, or productivity, the Braille Phone Tablet is designed to meet the unique needs of its users.</p>
    </section>

    <!-- Key Features Section -->
    <section id="product" class="container py-5">
      <h2 class="section-title">Key Features</h2>
      <div class="feature-list">
        <div class="feature-item">
          <h3>Braille Input & Output</h3>
          <p>The Braille Phone Tablet features a Braille pad for both text input and output, allowing users to easily read and write messages or documents through tactile feedback. This feature transforms the way visually impaired users interact with their device, providing a natural and intuitive experience.</p>
        </div>
        <div class="feature-item">
          <h3>Screen Reader Compatibility</h3>
          <p>Fully compatible with screen readers, the Braille Phone Tablet ensures that every action, from reading text to navigating apps, is easily understood through audio output. This feature creates a smooth, accessible experience for users, allowing them to interact with the device as naturally as possible.</p>
        </div>
        <div class="feature-item">
          <h3>Ergonomic Design</h3>
          <p>With its lightweight, portable design, the Braille Phone Tablet is comfortable to hold and easy to use for long periods. The device is designed to accommodate various grip styles, making it a versatile tool for daily use, whether at home, on the go, or in the workplace.</p>
        </div>
      </div>
    </section>

    <!-- New Section: Testing & User Feedback -->
    <section id="testing" class="container py-5">
      <h2 class="section-title">Testing & User Feedback</h2>
      <p>Thorough user testing is a crucial part of the development process for the Braille Phone Tablet. By conducting usability tests with real users, we ensure that the device is practical, easy to use, and meets the needs of its target audience. From initial prototypes to final production, user feedback plays a critical role in shaping the product.</p>

      <p>Early-stage testing with prototypes allows us to address potential usability issues and fine-tune the device’s design. As the product develops, we continue to gather feedback through beta testing and surveys, ensuring that each update brings us closer to a fully optimized product. This iterative testing process ensures that every aspect of the Braille Phone Tablet, from navigation to functionality, is user-friendly and accessible.</p>

      <p>Ultimately, the feedback we receive is used to refine the device’s features, ensuring it delivers the best possible experience for visually impaired users. The Braille Phone Tablet is designed with accessibility in mind, and its success is measured by how effectively it helps users engage with the world around them.</p>
    </section>
  </main>

  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; 2024 Braille Tech. All rights reserved.</p>
    <p><a href="contact.html" class="text-white">Contact Us</a> | <a href="privacy.html" class="text-white">Privacy Policy</a></p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
