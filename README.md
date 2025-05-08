<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chandra Prakash Sharma | Portfolio</title>
    <link rel="icon" href="https://github.com/prakashsharma19/prakash/blob/main/mydp-removebg-preview.png?raw=true" type="image/png" />
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="styles.css" />
    <style>
      /* You can also move this to styles.css */

      body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background-color: #FFFCF2;
        color: #333;
        margin: 0;
      }

      nav {
        background-color: #003366;
        color: white;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem 2rem;
        flex-wrap: wrap;
      }

      .nav__bar a {
        font-size: 1.5rem;
        font-weight: bold;
        color: white;
        text-decoration: none;
      }

      .nav__logo {
        background: white;
        color: #003366;
        padding: 0.2rem 0.5rem;
        border-radius: 5px;
        margin-right: 0.5rem;
      }

      .nav__links {
        display: flex;
        gap: 1.5rem;
        list-style: none;
      }

      .nav__links a {
        text-decoration: none;
        color: white;
        font-weight: 500;
      }

      .btn {
        background-color: #004080;
        color: white;
        padding: 0.5rem 1rem;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        text-decoration: none;
      }

      .btn:hover {
        background-color: #003366;
      }

      .section__container {
        max-width: 1200px;
        margin: auto;
        padding: 4rem 2rem;
      }

      .section__header {
        font-size: 2rem;
        color: #003366;
        margin-bottom: 1rem;
        text-align: center;
      }

      .header__container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 2rem;
      }

      .header__image img {
        width: 150px;
        border-radius: 12px;
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      }

      .header__content h1 {
        font-size: 2rem;
        color: #003366;
      }

      .section__description {
        margin-top: 1rem;
        font-size: 1rem;
      }

      .about__content ul {
        list-style: disc;
        padding-left: 1.5rem;
      }

      .service__grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
        gap: 1.5rem;
        margin-top: 2rem;
      }

      .service__card {
        background: #fff;
        border: 1px solid #ddd;
        padding: 1.5rem;
        border-radius: 10px;
        text-align: center;
        transition: 0.3s;
      }

      .service__card:hover {
        box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      }

      .service__card i {
        font-size: 2rem;
        color: #003366;
        margin-bottom: 1rem;
      }

      .portfolio__grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
        gap: 1rem;
        margin-top: 2rem;
      }

      .portfolio__grid img {
        width: 100%;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      }

      .contact__socials {
        display: flex;
        justify-content: center;
        gap: 1rem;
        margin: 1.5rem 0;
      }

      .contact__socials a {
        font-size: 1.5rem;
        color: #003366;
      }

      form {
        max-width: 600px;
        margin: auto;
      }

      form input,
      form textarea {
        width: 100%;
        padding: 1rem;
        margin-bottom: 1rem;
        border: 1px solid #ccc;
        border-radius: 8px;
      }

      form button {
        background-color: #004080;
        color: white;
        padding: 0.75rem 1.5rem;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }

      form button:hover {
        background-color: #003366;
      }

      .footer {
        text-align: center;
        padding: 1rem;
        background-color: #003366;
        color: white;
      }
    </style>
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
        <img src="assets/project-1.jpg" alt="Project 1" />
        <img src="assets/project-2.jpg" alt="Project 2" />
        <img src="assets/project-3.jpg" alt="Project 3" />
        <img src="assets/project-4.jpg" alt="Project 4" />
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
  </body>
</html>
