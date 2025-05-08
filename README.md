<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-W7EWRLZ3ZE"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());
      gtag('config', 'G-W7EWRLZ3ZE');
    </script>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Prakash (CP Sharma)</title>
    <link rel="icon" href="https://github.com/prakashsharma19/prakash/blob/main/mydp-removebg-preview.png?raw=true" type="image/png">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <nav>
      <div class="nav__bar">
        <a href="#"><span class="logo nav__logo">CP</span> Prakash Sharma</a>
        <div class="nav__menu__btn" id="menu-btn">
          <i class="ri-menu-3-line"></i>
        </div>
      </div>
      <ul class="nav__links" id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#service">Service</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact" class="btn">Contact</a></li>
      </ul>
      <a href="#contact" class="btn btn__large">Contact</a>
    </nav>

    <header class="section__container header__container" id="home">
      <div class="header__image">
        <img src="https://github.com/prakashsharma19/prakash/blob/main/my_image-removebg-preview.png?raw=true" alt="Prakash Sharma" />
      </div>
      <div class="header__content">
        <div>
          <h1>Chandra Prakash Sharma<br />Web Developer</h1>
        </div>
        <p class="section__description">
          MBA in Marketing & IT | Experienced in Website Development, SEO, Google/Meta Ads & Prompt Engineering | Let's Collaborate on Innovative Projects
        </p>
        <div class="header__btn">
          <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Hire Me Now</button>
        </div>
      </div>
    </header>

    <section class="section__container about__container" id="about">
      <div class="about__image">
        <img src="assets/bg.png" alt="bg" class="about__bg-1" />
        <img src="assets/bg.png" alt="bg" class="about__bg-2" />
        <img src="https://github.com/prakashsharma19/prakash/blob/main/my_image-removebg-preview.png?raw=true" alt="about" class="about__img" />
      </div>
      <div class="about__content">
        <h2 class="section__header">Bit About Me</h2>
        <p class="section__description">
          MBA in Marketing & IT from AKTU. Passionate about Web Dev, Coding, AI, and Psychology. I build solutions combining design, functionality, and marketing. Let's collaborate on meaningful tech.
        </p>
        <ul>
          <li><strong>Currently Learning:</strong> Python, Data Science, Cloud, Prompt Engineering</li>
          <li><strong>Collaborate On:</strong> AI + Sustainability Projects</li>
          <li><strong>Location:</strong> Prayagraj, India</li>
        </ul>
        <div class="about__btn">
          <a href="mailto:contact@cpsharma.com" class="btn">Email Me</a>
        </div>
      </div>
    </section>

    <section class="section__container service__container" id="service">
      <h2 class="section__header">My Services</h2>
      <div class="service__grid">
        <div class="service__card"><span><i class="ri-window-fill"></i></span><h4>Website Dev</h4><p>Custom web solutions using modern stacks & CMS.</p></div>
        <div class="service__card"><span><i class="ri-seo-line"></i></span><h4>SEO</h4><p>Search engine optimization for better visibility.</p></div>
        <div class="service__card"><span><i class="ri-facebook-box-fill"></i></span><h4>Meta Ads</h4><p>Targeted social ads that convert leads.</p></div>
        <div class="service__card"><span><i class="ri-google-fill"></i></span><h4>Google Ads</h4><p>Results-driven PPC campaigns with measurable ROI.</p></div>
        <div class="service__card"><span><i class="ri-wordpress-fill"></i></span><h4>WordPress Dev</h4><p>Build & customize high-performance WordPress sites.</p></div>
        <div class="service__card"><span><i class="ri-robot-2-line"></i></span><h4>Prompt Engineering</h4><p>Crafting AI prompts for business automation.</p></div>
      </div>
    </section>

    <section class="section__container portfolio__container" id="portfolio">
      <h2 class="section__header">My Portfolio</h2>
      <p class="section__description">
        I’ve delivered custom websites, AI-integrated tools, and marketing results through Google, Meta, and LinkedIn campaigns. More on <a href="https://in.linkedin.com/in/chandra-prakash-sharma-31a80428a" target="_blank">LinkedIn</a>.
      </p>
      <div class="portfolio__grid">
        <div class="portfolio__card"><img src="assets/project-1.jpg" alt="Project 1" /></div>
        <div class="portfolio__card"><img src="assets/project-2.jpg" alt="Project 2" /></div>
        <div class="portfolio__card"><img src="assets/project-3.jpg" alt="Project 3" /></div>
        <div class="portfolio__card"><img src="assets/project-4.jpg" alt="Project 4" /></div>
      </div>
      <div class="portfolio__banner">
        <div class="portfolio__banner__card"><span><i class="ri-macbook-line"></i></span><h4>150+ Projects</h4><p>Delivered</p></div>
        <div class="portfolio__banner__card"><span><i class="ri-discuss-line"></i></span><h4>1500+ Clients</h4><p>Engaged</p></div>
        <div class="portfolio__banner__card"><span><i class="ri-heart-fill"></i></span><h4>2700+ Feedbacks</h4><p>Received</p></div>
      </div>
    </section>

    <section class="section__container contact__container" id="contact">
      <div class="logo">CP</div>
      <h2 class="section__header">Let's Connect</h2>
      <p class="section__description">Contact me via the form or connect through social media.</p>
      <div class="contact__socials">
        <a href="https://x.com/ambvert_" target="_blank"><i class="ri-twitter-fill"></i></a>
        <a href="https://www.instagram.com/ambvert_/" target="_blank"><i class="ri-instagram-line"></i></a>
        <a href="https://www.linkedin.com/in/chandra-prakash-sharma-31a80428a" target="_blank"><i class="ri-linkedin-fill"></i></a>
        <a href="https://www.quora.com/profile/Prakash-1051" target="_blank"><i class="ri-quora-fill"></i></a>
      </div>
      <form action="https://formspree.io/f/xgvwjkqz" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
      <div class="booking-button">
        <script src="https://topmate-embed.s3.ap-south-1.amazonaws.com/v1/topmate-embed.js"
          user-profile="https://topmate.io/embed/profile/prakash_sharma?theme=D5534D"
          btn-style='{"backgroundColor":"#003366","color":"#fff","border":"1px solid #003366"}'
          embed-version="v1" button-text="Let's Connect 1:1"
          position-right="30px" position-bottom="30px"
          custom-padding="0px" custom-font-size="16px"
          custom-font-weight="500" custom-width="200px" async defer>
        </script>
      </div>
    </section>

    <footer class="footer">
      © 2025 Chandra Prakash Sharma | All Rights Reserved
    </footer>

    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="main.js"></script>
  </body>
</html>
