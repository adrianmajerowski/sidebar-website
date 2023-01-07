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
  <div> <svg class="bg-svg" width="100%" height="667" viewBox="0 0 1617 667" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect width="1617" height="667" fill="white"/>
<rect x="195.5" y="143.5" width="1336" height="424" rx="14.5" stroke="#2C3E50"/>
<rect x="192" y="140" width="26" height="20" fill="white"/>
<rect x="192" y="140" width="229" height="8" fill="white"/>
<rect x="192" y="222" width="62" height="8" transform="rotate(-90 192 222)" fill="white"/>
<circle cx="195.5" cy="221.5" r="2.5" fill="#2C3E50"/>
<circle cx="420.5" cy="143.5" r="2.5" fill="#2C3E50"/>
</svg></div>
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
    <div class="client-box">
      <div class="rectangle-22"></div>
      <img class="client-img" src="@/assets/hero.jpg"/>
      <div class="rectangle-23"></div>
      <div class="client-content">Hi, it’s me.<br />Book a call.</div>
      <div class="button">case study</div>
    </div>

    <div class="client-box">
      <div class="rectangle-22"></div>
      <img class="client-img" src="invest-in-pomerania-logo-1.png"/>
      <div class="rectangle-23"></div>
      <div class="client-content">Hi, it’s me.<br />Book a call.</div>
      <div class="button">case study</div>
    </div>

    <div class="client-box">
      <div class="rectangle-22"></div>
      <img class="client-img" src="invest-in-pomerania-logo-1.png"/>
      <div class="rectangle-23"></div>
      <div class="client-content">Hi, it’s me.<br />Book a call.</div>
      <div class="button">case study</div>
    </div>
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
    margin-left: 20px;
  }

  .services .service {
    margin-bottom: 30px;
    background-position: 50% 46%;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 150px 0 150px 0;
    width: 50%;
    text-align: center;
    margin-right: 130px;
    margin-left: -90px;
    
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

  .bg-svg{
    margin-bottom: -610px;

  }

  .client-box,
.client-box * {
  box-sizing: border-box;
}
.client-box {
  width: 351px;
  height: 556px;
  position: relative;
}
.rectangle-22 {
  background: #ffffff;
  border-radius: 15px 15px 0px 0px;
  border: solid #000000;
  border-width: 1px;
  width: 351px;
  height: 338px;
  position: absolute;
  left: 0px;
  top: 556px;
  transform-origin: 0 0;
  transform: rotate(0deg) scale(1, -1);
}
.client-img {
  border-radius: 15px 15px 0px 0px;
  border: solid #000000;
  border-width: 1px;
  width: 351px;
  height: 219px;
  position: absolute;
  left: 0px;
  top: 0px;
}
.rectangle-23 {
  background: #d9d9d9;
  border-radius: 5px;
  width: 252.08px;
  height: 43px;
  position: absolute;
  left: 49.46px;
  top: 492px;
}
.client-content {
  color: #000000;
  text-align: left;
  font: 400 12px "Inter", sans-serif;
  position: absolute;
  left: 49.46px;
  top: 255px;
  width: 252.08px;
  height: 203px;
}

</style>