<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chandra Prakash Sharma | Portfolio</title>
    <link rel="icon" href="https://github.com/prakashsharma19/prakash/blob/main/mydp-removebg-preview.png?raw=true" type="image/png" />
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="styles.css" />
    
  </head>

  <body>
    <nav>
      <div class="nav__bar">
        <a href="#"><span class="nav__logo">CP</span> Prakash Sharma</a>
      </div>
      <ul class="nav__links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#service">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact" class="btn">Contact</a></li>
      </ul>
    </nav>

    <header class="section__container header__container" id="home">
      <div class="header__image">
        <img src="https://github.com/prakashsharma19/prakash/blob/main/my_image-removebg-preview.png?raw=true" alt="Prakash Sharma" />
      </div>
      <div class="header__content">
        <h1>Chandra Prakash Sharma<br />Web Developer</h1>
        <p class="section__description">
          MBA in Marketing & IT | Skilled in Website Development, SEO, Google/Meta Ads, AI, SMM & Prompt Engineering
        </p>
        <a href="#contact" class="btn">Hire Me</a>
      </div>
    </header>

    <section class="section__container about__container" id="about">
      <h2 class="section__header">Bit About Me</h2>
      <div class="about__content">
        <p>
          I am passionate about using technology to solve real-world problems. My strengths lie in Web Development,
          Software Engineering, AI Integration, SEO, and Digital Marketing.
        </p>
        <ul>
          <li>Currently learning Python, Data Science, Cloud, Prompt Engineering</li>
          <li>Looking to collaborate on AI + sustainability projects</li>
          <li>Based in Prayagraj, India</li>
        </ul>
      </div>
    </section>

    <section class="section__container service__container" id="service">
      <h2 class="section__header">My Services</h2>
      <div class="service__grid">
        <div class="service__card"><i class="ri-window-fill"></i><h4>Website Dev</h4><p>Responsive websites tailored to your brand.</p></div>
        <div class="service__card"><i class="ri-code-s-slash-line"></i><h4>Software Development</h4><p>Custom-built tools and systems for your needs.</p></div>
        <div class="service__card"><i class="ri-brain-line"></i><h4>AI Integration</h4><p>Embedding smart features with GPT/automation.</p></div>
        <div class="service__card"><i class="ri-facebook-box-fill"></i><h4>SMM</h4><p>Managing & growing your brand on social platforms.</p></div>
        <div class="service__card"><i class="ri-google-fill"></i><h4>Google Ads</h4><p>Grow your reach with paid advertising.</p></div>
        <div class="service__card"><i class="ri-seo-line"></i><h4>SEO</h4><p>Boost rankings and site visibility.</p></div>
      </div>
    </section>

    <section class="section__container portfolio__container" id="portfolio">
      <h2 class="section__header">My Portfolio</h2>
      <p class="section__description">Samples of my work are available upon request or through my LinkedIn.</p>
      <div class="portfolio__grid">
        <img src="https://via.placeholder.com/300x200?text=Project+1" alt="Project 1" />
        <img src="https://via.placeholder.com/300x200?text=Project+2" alt="Project 2" />
        <img src="https://via.placeholder.com/300x200?text=Project+3" alt="Project 3" />
        <img src="https://via.placeholder.com/300x200?text=Project+4" alt="Project 4" />
      </div>
    </section>

    <section class="section__container contact__container" id="contact">
      <h2 class="section__header">Let's Connect</h2>
      <p class="section__description">Feel free to reach out for collaboration or freelance work.</p>
      <div class="contact__socials">
        <a href="https://x.com/ambvert_" target="_blank"><i class="ri-twitter-fill"></i></a>
        <a href="https://www.instagram.com/ambvert_/" target="_blank"><i class="ri-instagram-line"></i></a>
        <a href="https://www.linkedin.com/in/chandra-prakash-sharma-31a80428a" target="_blank"><i class="ri-linkedin-fill"></i></a>
        <a href="https://www.quora.com/profile/Prakash-1051" target="_blank"><i class="ri-quora-line"></i></a>
      </div>
      <form action="https://formspree.io/f/xgvwjkqz" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>

    <footer class="footer">
      © 2025 Chandra Prakash Sharma | All Rights Reserved
    </footer>
  </body>
</html>
