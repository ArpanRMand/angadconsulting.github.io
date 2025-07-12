<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Angad Consulting provides trusted immigration consulting services for Study Visa, PR, Work Permits, and more.">
  <title>Angad Consulting | Immigration Experts</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #fff;
      color: #333;
    }
    header {
      background: #f9f9f9;
      padding: 1.5rem;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      color: #b97a2e;
      margin: 0;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #444;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d?auto=format&fit=crop&w=1470&q=80') center/cover no-repeat;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      position: relative;
      color: white;
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.5);
    }
    .hero-content {
      position: relative;
      z-index: 1;
      max-width: 640px;
    }
    .hero-content h2 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .btn-primary {
      display: inline-block;
      background: #b97a2e;
      color: white;
      padding: 0.75rem 2rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 1rem;
    }
    .section {
      padding: 4rem 1rem;
      max-width: 1100px;
      margin: auto;
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
    }
    .service {
      background: #f8f8f8;
      border-radius: 10px;
      padding: 1.5rem;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }
    .service img {
      width: 80px;
      height: 80px;
      object-fit: contain;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
  
	  
    .carousel {
      overflow: hidden;
      position: relative;
    }
    .carousel-track {
      display: flex;
      gap: 2rem;
      width: max-content;
      animation: scroll 30s linear infinite;
    }
    .testimonial {
      flex: 0 0 300px;
      background: #f5f5f5;
      border-left: 5px solid #b97a2e;
      padding: 1.5rem;
      border-radius: 10px;
      font-style: italic;
    }
    .testimonial-author {
      margin-top: 1rem;
      font-weight: bold;
      color: #b97a2e;
    }
    @keyframes scroll {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }
    .contact {
      background: #f3f3f3;
      padding: 4rem 2rem;
      border-top: 2px solid #ddd;
      text-align: center;
      border-radius: 12px;
    }
    .contact h2 {
      font-size: 2.5rem;
      margin-bottom: 1.5rem;
      color: #b97a2e;
    }
    .contact p {
      margin: 0.5rem 0;
      font-size: 1.1rem;
    }
    .contact a {
      color: #333;
      text-decoration: none;
    }
    .contact a:hover {
      color: #b97a2e;
    }
    footer {
      background: #1e1e1e;
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #ccc;
    }
    footer a {
      color: #b97a2e;
      text-decoration: none;
      font-weight: bold;
    }
    footer a:hover {
      text-decoration: underline;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 0.75rem 1.25rem;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>Angad Consulting</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Your Trusted Immigration Experts</h2>
      <p>Helping you navigate Canadian visas, PR, spousal permits, and more with expertise and care.</p>
      <a href="#contact" class="btn-primary">Book a Consultation</a>
    </div>
  </section>

  <section id="services" class="section">
   <h2>Our Services</h2>
    <div class="services-grid">
      <div class="service">
        <img src="https://img.icons8.com/color/96/graduation-cap.png" alt="Study Visa">
        <h3>Study Visa Assistance</h3>
        <p>Admissions help, SOPs, and expert visa filing for studying in Canada, UK, and more.</p>
      </div>
      <div class="service">	 
        <img src="https://img.icons8.com/external-filled-color-icons-papa-vector/78/external-Spouses-social-participation-and-volunteering-filled-color-icons-papa-vector.png" alt="Spousal Permit">
        <h3>Spousal Open Work Permit</h3>
        <p>Helping spouses work legally while accompanying students or workers in Canada.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/color/96/briefcase.png" alt="PGWP">
        <h3>Post-Graduation Work Permit</h3>
        <p>Transition from student to employee with PGWP application support.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/color/96/maple-leaf.png" alt="PNP">
        <h3>Provincial Nominee Program</h3>
        <p>Get nominated by a Canadian province and boost your PR chances.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/color/96/passport.png" alt="PR">
        <h3>Permanent Residency</h3>
        <p>Expert help with Express Entry, Sponsorship, and other PR streams.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/color/96/airport.png" alt="Visitor Visa">
        <h3>Visitor & Business Visas</h3>
        <p>Professionally crafted visitor visa applications for business or leisure.</p>
      </div>
    </div>
  </section>

  <section id="testimonials" class="section">
    <h2>Client Testimonials</h2>
    <div class="carousel">
      <div class="carousel-track">
        <div class="testimonial">
          <p>“Angad Consulting helped me get my study permit smoothly. Highly recommended!”</p>
          <div class="testimonial-author">— Harpreet K., Toronto</div>
        </div>
        <div class="testimonial">
          <p>“Professional and responsive. My PR journey was stress-free with their help.”</p>
          <div class="testimonial-author">— Simran D., Edmonton</div>
        </div>
        <div class="testimonial">
          <p>“Clear, friendly, and always available. My spousal permit was approved!”</p>
          <div class="testimonial-author">— Jasleen M., Vancouver</div>
        </div>
        <div class="testimonial">
          <p>“They explained everything clearly and submitted my PGWP just in time.”</p>
          <div class="testimonial-author">— Rahul S., Brampton</div>
        </div>
        <div class="testimonial">
          <p>“Thanks to them, I now work full-time in Canada. Great experience.”</p>
          <div class="testimonial-author">— Neha T., Mississauga</div>
        </div>
        <!-- Duplicate testimonials for smooth infinite loop -->
        <div class="testimonial">
          <p>“Angad Consulting helped me get my study permit smoothly. Highly recommended!”</p>
          <div class="testimonial-author">— Harpreet K., Toronto</div>
        </div>
        <div class="testimonial">
          <p>“Professional and responsive. My PR journey was stress-free with their help.”</p>
          <div class="testimonial-author">— Simran D., Edmonton</div>
        </div>
        <div class="testimonial">
          <p>“Clear, friendly, and always available. My spousal permit was approved!”</p>
          <div class="testimonial-author">— Jasleen M., Vancouver</div>
        </div>
        <div class="testimonial">
          <p>“They explained everything clearly and submitted my PGWP just in time.”</p>
          <div class="testimonial-author">— Rahul S., Brampton</div>
        </div>
        <div class="testimonial">
          <p>“Thanks to them, I now work full-time in Canada. Great experience.”</p>
          <div class="testimonial-author">— Neha T., Mississauga</div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="section contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> <a href="tel:+16478944842">+1 (647) 894-4842</a></p>
    <p><strong>Email:</strong> <a href="mailto:angadconsulting@gmail.com">angadconsulting@gmail.com</a></p>
    <p><strong>Location:</strong> Brampton, Ontario, Canada</p>
    <p><strong>Business Hours:</strong> Monday to Saturday, 10 AM – 6 PM</p>
    <p><strong>Consultation:</strong> Available by appointment only</p>
  </section>

  <a href="https://wa.me/16478944842" class="whatsapp" target="_blank">💬 Chat with us on WhatsApp</a>

  <footer>
    <p>&copy; 2025 Angad Consulting. All rights reserved.</p>
    <p>Website by <a href="#">Angad Consulting</a></p>
  </footer>
</body>
</html>
 
