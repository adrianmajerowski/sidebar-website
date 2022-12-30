<template>
  <div>
    <div class="header">
      
    </div>
    <div class="hero" :style="{ backgroundImage: 'url(' + require('@/assets/hero-dark.jpg') + ')' }">
      <div class="hero-text">
        <p class="adrian">ADRIAN MAJEROWSKI</p>
        <h1>Design Outsourcing</h1>
        <p>I design UX/UI App prototypes and create websites for startups & business teams</p>
        <a href="#" class="button">My Work Ethics</a>
        <a href="#" class="button">Book a Meeting</a>
      </div>
    </div>
    <div class="services">
      <h2>How can I power up your project?</h2>
      <div class="service">
        <h3>App Prototyping</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.</p>
        
        <a href="#" class="button">Learn More</a>
      </div>
      <div class="service">
        <h3>Web Design & Dev</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.</p>
        
        <a href="#" class="button">Learn More</a>
      </div>
      
    </div>
    <h2>Clients</h2>
    <div class="logo-row">
  <img src="@/assets/linkedin.png" alt="LinkedIn Logo" style="width: 80px; height: 80px;" />
  <img src="@/assets/linkedin.png" alt="LinkedIn Logo" style="width: 80px; height: 80px;" />
  <img src="@/assets/linkedin.png" alt="LinkedIn Logo" style="width: 80px; height: 80px;" />
</div>

    <div class="contact">
      <h2>Contact Us</h2>
      <form>
        <input type="text" placeholder="Name" />
        <input type="email" placeholder="Email" />
        <textarea placeholder="Message"></textarea>
        <button type="submit" class="button">Send Message</button>
      </form>
    </div>
    <div class="footer">
      <div class="social-icons">
        <a href="https://www.linkedin.com/in/adrian-majerowski-ux/" target="_blank"><img src="@/assets/linkedin.png" alt="LinkedIn"/></a>
      </div>
      <div class="copyright">© 2023 AM</div>
    </div>
  </div>
</template>

<style>
  /* General Styles */
  * {
    box-sizing: border-box;
  }

  body {
    font-family: sans-serif;
  }

  /* Header Styles */

  .header {
    width: 100%;
    background: #222;
    padding: 10px 0;
  }

  .header .logo {
    float: left;
    color: #fff;
    font-size: 20px;
    font-weight: bold;
    padding: 10px 15px;
  }

  .header nav {
    float: right;
  }

  .header nav a {
    float: left;
    color: #fff;
    text-decoration: none;
    padding: 10px 15px;
    font-size: 14px;
  }

  /* Hero Styles */
  .hero {
    background: #777;
    text-align: center;
    padding: 100px 0;
    background-position: 50% 46%;
    background-repeat: no-repeat;
    background-size: cover;
    
  }

  .hero-image {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
  }

  .hero-image img { 
    width: 100%;
  }

  .hero-text {
    margin-top: 20px;
  }

  .hero-text h1 {
    color: #fff;
    font-size: 60px;
    font-weight: 600;
    margin: 10px 0 0 0;
  
  }

  .hero-text .adrian{
    color:#fff;
    font-size: 13px;
    weight: 600;

  }

  .hero-text p {
    color: #fff;
    font-size: 16px;
    margin: 20px 32% 40px 32%;

  }

  .hero-text .button {
    color: #222;
    background: #fff;
    text-decoration: none;
    padding: 10px 20px;
    margin: 0 10px 0 10px;
    font-size: 16px;
    border-radius: 5px;
  }

  /* Services Styles */
  .services {
    text-align: center;
    padding: 50px 0;
    display: flex;
    justify-content: center;
  }

  .services h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 30px;
  }

  .services .service {
    margin-bottom: 30px;
    background-position: 50% 46%;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 150px 0 150px 0;
    width: 50%;
    text-align: center;
    
  }

  .services .service h3 {
    font-size: 22px;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .services .service p {
    font-size: 16px;
    line-height: 24px;
    margin-bottom: 20px;
  }

  .services .service .button {
    color: #222;
    background: #fff;
    text-decoration: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
  }

  /* Testimonials Styles */
  .logo-row{
    display: flex;
    justify-content: center;

  }
  

  .testimonials {
    text-align: center;
    padding: 50px 0;
  }

  .testimonials h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 30px;
  }

  .testimonials .testimonial {
    margin-bottom: 30px;
  }

  .testimonials .testimonial p {
    font-size: 16px;
    line-height: 24px;
    margin-bottom: 10px;
  }

  .testimonials .testimonial h3 {
    font-size: 16px;
    font-weight: bold;
  }

  /* Contact Styles */
  .contact {
    text-align: center;
    padding: 50px 0;
  }

  .contact h2 {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 30px;
  }

  .contact form {
    margin-bottom: 30px;
  }

  .contact form input,
  .contact form textarea {
    width: 100%;
    padding: 10px;
    font-size: 16px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }

  .contact form .button {
    color: #222;
    background: #fff;
    text-decoration: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
  }

  /* Footer Styles */
  .footer {
    background: #222;
    padding: 20px 0;
    text-align: center;
  }

  .footer .social-icons {
    margin-bottom: 10px;
  }

  .footer .social-icons img {
    width: 30px;
    margin: 0 5px;
  }

  .footer .copyright {
    color: #fff;
    font-size: 14px;
  }
</style>