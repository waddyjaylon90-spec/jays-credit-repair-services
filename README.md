<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jay's Credit Repair Services</title>
  <style>
    /* Reset and base styles */
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9fafb;
      color: #1a1a1a;
      line-height: 1.6;
    }
    a {
      color: #1a73e8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    /* Container */
    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 0 20px;
    }
    /* Header */
    header {
      background: #004aad;
      color: white;
      padding: 20px 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
      font-weight: 700;
    }
    header .phone {
      font-size: 1.1rem;
      font-weight: 600;
    }
    /* Navigation */
    nav {
      margin-top: 10px;
      width: 100%;
    }
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 30px;
      margin: 0;
    }
    nav ul li {
      font-weight: 600;
    }
    nav ul li a {
      color: white;
      font-size: 1rem;
    }
    nav ul li a:hover {
      color: #ffcc00;
    }
    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #004aad 0%, #0066ff 100%);
      color: white;
      padding: 80px 20px;
      text-align: center;
      border-radius: 0 0 40px 40px;
    }
    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.3rem;
      margin-bottom: 30px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      line-height: 1.5;
    }
    .hero .btn {
      background-color: #ffcc00;
      color: #004aad;
      padding: 15px 30px;
      font-weight: 700;
      font-size: 1.1rem;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }
    .hero .btn:hover {
      background-color: #e6b800;
    }
    /* Sections */
    section {
      padding: 60px 20px;
      text-align: center;
    }
    section h3 {
      font-size: 2rem;
      color: #004aad;
      margin-bottom: 25px;
      font-weight: 700;
    }
    section p {
      max-width: 700px;
      margin: 0 auto 40px auto;
      font-size: 1.1rem;
      color: #333;
    }
    /* How It Works */
    .steps {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 40px;
    }
    .step {
      background: white;
      border-radius: 15px;
      padding: 30px 25px;
      flex: 1 1 250px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .step:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }
    .step h4 {
      font-size: 1.4rem;
      margin-bottom: 15px;
      color: #004aad;
      font-weight: 700;
    }
    /* Services */
    .services-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }
    .service-item {
      background: white;
      border-radius: 15px;
      padding: 25px 20px;
      flex: 1 1 220px;
      box-shadow: 0 5px 12px rgba(0,0,0,0.08);
      font-weight: 600;
      font-size: 1.1rem;
      color: #222;
    }
    /* Why Choose Us */
    .why-list {
      max-width: 600px;
      margin: 0 auto;
      text-align: left;
      list-style: disc;
      color: #004aad;
      font-weight: 600;
      font-size: 1.1rem;
      padding-left: 20px;
      line-height: 1.6;
    }
    /* Contact */
    .contact-info {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 20px;
    }
    .contact-btn {
      background-color: #004aad;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 30px;
      font-weight: 700;
      font-size: 1.1rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: background-color 0.3s ease;
    }
    .contact-btn:hover {
      background-color: #00337a;
    }
    /* Footer */
    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9rem;
    }
    /* Responsive */
    @media(max-width: 768px) {
      nav ul {
        flex-direction: column;
        gap: 15px;
      }
      .steps, .services-list {
        flex-direction: column;
        gap: 20px;
      }
    }
  </style>
</head>
<body>
  <header class="container" role="banner">
    <h1>Jay's Credit Repair Services</h1>
    <div class="phone">
      <a href="tel:3464643757" style="color: white; text-decoration:none;">📞 346-464-3757</a>
    </div>
    <nav role="navigation">
      <ul>
        <li><a href="#hero">Home</a></li>
        <li><a href="#how-it-works">How It Works</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero" class="hero" role="region" aria-label="Hero Section">
      <h2>Fix Your Credit. Change Your Life.</h2>
      <p>Remove collections, late payments, charge-offs & errors to qualify for what you deserve.</p>
      <a href="tel:3464643757" class="btn" role="button" aria-label="Call Jay's Credit Repair Services">Get Your FREE Credit Evaluation</a>
    </section>

    <section id="how-it-works" class="container" role="region" aria-label="How It Works Section">
      <h3>How It Works</h3>
      <div class="steps">
        <article class="step" role="article" aria-label="Step 1: Free Credit Evaluation">
          <h4>Step 1: Free Credit Evaluation</h4>
          <p>We analyze your credit report at no cost.</p>
        </article>
        <article class="step" role="article" aria-label="Step 2: Dispute Negative Items">
          <h4>Step 2: Dispute Negative Items</h4>
          <p>We challenge collections, errors, and late payments.</p>
        </article>
        <article class="step" role="article" aria-label="Step 3: See Your Score Improve">
          <h4>Step 3: See Your Score Improve</h4>
          <p>Watch your credit score rise as negative items drop.</p>
        </article>
      </div>
    </section>

    <section id="services" class="container" role="region" aria-label="Services Section">
      <h3>Our Services</h3>
      <div class="services-list">
        <div class="service-item">Credit Report Review</div>
        <div class="service-item">Credit Dispute Management</div>
        <div class="service-item">Monthly Credit Monitoring (optional)</div>
        <div class="service-item">Personalized Credit Coaching</div>
      </div>
    </section>

    <section id="why-choose-us" class="container" role="region" aria-label="Why Choose Us Section">
      <h3>Why Choose Us?</h3>
      <ul class="why-list">
        <li>No long-term contracts</li>
        <li>Transparent pricing</li>
        <li>Experienced credit specialists</li>
        <li>Real results for Texans</li>
      </ul>
    </section>

    <section id="contact" class="container" role="region" aria-label="Contact Section">
      <h3>Contact Us</h3>
      <p class="contact-info">📞 Phone: <a href="tel:3464643757">346-464-3757</a></p>
      <p class="contact-info">✉️ Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
      <a href="tel:3464643757" class="contact-btn" role="button" aria-label="Call Jay's Credit Repair Services">Start Your Free Evaluation Today</a>
    </section>
  </main>

  <footer role="contentinfo">
    <p>© 2026 Jay's Credit Repair Services. All rights reserved.</p>
  </footer>
</body>
</html>
