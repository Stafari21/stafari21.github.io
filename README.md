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
      <p>The Braille Phone Tablet is designed to provide visually impaired individuals with a device that not only meets their needs but empowers them to feel connected and independent. With a focus on accessibility and usability, the tablet offers an intuitive and tactile interface that simplifies interactions, ensuring that technology is no longer a barrier, but a tool for independence.</p>

      <p>This device is crafted specifically for individuals with visual impairments. Through the innovative integration of Braille functionality, users can now easily navigate their device using tactile feedback, making everyday tasks more manageable and less reliant on voice commands. The tactile Braille interface enhances the user experience by allowing them to input text and read information with their fingertips, providing a sense of control and ease in their daily activities.</p>

      <p>The tablet is delivered in a convenient, portable form that integrates a large screen with Braille functionality on the back. This design offers both visual and tactile features, enabling users to access everything from messaging to browsing with a single device. The combination of ergonomic design and advanced technology makes the Braille Phone Tablet the ideal solution for anyone seeking an accessible and user-friendly mobile experience.</p>
    </section>

    <!-- Key Features Section -->
    <section id="product" class="container py-5">
      <h2 class="section-title">Key Features</h2>
      <div class="feature-list">
        <div class="feature-item">
          <h3>Braille Input & Output</h3>
          <p>Experience tactile feedback with a Braille pad for easy text input and reading. This feature enables users to type and read in Braille, making communication fast and effortless.</p>
        </div>
        <div class="feature-item">
          <h3>Screen Reader Compatible</h3>
          <p>Full compatibility with screen readers ensures that every interaction is seamless, whether it's navigating apps or reading content on the screen. Users will always have clear audio guidance for navigation.</p>
        </div>
        <div class="feature-item">
          <h3>Ergonomic Design</h3>
          <p>Lightweight and portable, the Braille Phone Tablet is designed for comfort, ensuring that users can hold and interact with the device for extended periods without strain. Its design makes it ideal for everyday use, wherever users go.</p>
        </div>
      </div>
    </section>

    <!-- New Section: Testing & User Feedback -->
    <section id="testing" class="container py-5">
      <h2 class="section-title">Testing & User Feedback</h2>
      <p>Before the Braille Phone Tablet is made available to the public, extensive testing with real users ensures that the device meets the needs of its intended audience. By starting with early prototypes, we can identify usability issues and make improvements based on real-world feedback.</p>
      
      <p>We employ a continuous testing process, beginning with initial usability tests using prototypes, followed by additional testing as the product evolves. Beta testing allows us to fine-tune the product, ensuring that it functions smoothly and effectively for all users.</p>

      <p>Our testing process focuses on understanding the challenges visually impaired users may face while interacting with the tablet. Through direct user feedback, we gather valuable insights into how the Braille pad and other features are utilized. This iterative approach ensures that the final product is both accessible and user-friendly.</p>

      <p>Ultimately, the feedback from these sessions plays a crucial role in shaping the final design, ensuring that the Braille Phone Tablet is as intuitive, functional, and accessible as possible for its users.</p>
    </section>
  </main>

  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; 2024 Braille Tech. All rights reserved.</p>
    <p><a href="contact.html" class="text-white">Contact Us</a> | <a href="privacy.html" class="text-white">Privacy Policy</a></p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
