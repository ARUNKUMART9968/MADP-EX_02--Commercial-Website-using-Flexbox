# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SN Coffee</title>
    <!-- CSS Link -->
    <link rel="stylesheet" href="style.css" />
    <!-- Box Icon Link for Icons -->
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
  </head>
  <body>
    <!-- Header & Navbar Section -->
    <header>
      <nav>
        <div class="nav_logo">
          <a href="#">
            <img src="images/coffee_logo.png" alt="Coffee Logo" />
            <h2>Coffee</h2>
          </a>
        </div>

        <input type="checkbox" id="click" />
        <label for="click">
          <i class="menu_btn bx bx-menu"></i>
          <i class="close_btn bx bx-x"></i>
        </label>

        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#service">Services</a></li>
          <li><a href="#why">Why Us</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero_section">
      <div class="section_container">
        <div class="hero_container">
          <div class="text_section">
            <h2>Fuel Your Passion</h2>
            <h3>Discover the Magic in Every Cup</h3>
            <p>
              Welcome to our coffee paradise, where every bean tells a story and
              every cup sparks.
            </p>

            <div class="hero_section_button">
              <button class="button">Order Online</button>
              <button class="button">Book A Table</button>
            </div>
          </div>

          <div class="image_section">
            <img src="images/cofffee_image.png" alt="Coffee" />
          </div>
        </div>
      </div>
    </section>

    <!-- About Us Section -->
    <section class="about_us" id="about">
      <div class="section_container">
        <div class="about_container">
          <div class="text_section">
            <h2 class="section_title">About Us</h2>
            <p>
              We at Coffee House, located in Berndorf, Germany, are one of the
              favorite hangouts for coffee and conversations. Our goal is to
              offer the best experience to our guests, ensuring an authentic
              coffee drinking experience in a warm, friendly, and relaxed
              environment. We aim to bring a sense of relaxation to the city
              with our cozy space, complete with comfortable couches to lounge
              in while you enjoy your coffee.
            </p>
          </div>

          <div class="image_section">
            <img src="images/about_coffee.png" alt="coffee" />
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="service">
      <h2 class="section_title">Our Services</h2>
      <div class="section_container">
        <div class="service_container">
          <div class="services_items">
            <img src="images/hot_beverages.png" alt="Hot Beverages" />
            <div class="services_text">
              <h3>Hot Beverages</h3>
              <p>
                Wide range of Steaming hot coffees to make you fresh and light.
              </p>
            </div>
          </div>
          <div class="services_items">
            <img src="images/cold_beverages.png" alt="Cold Beverages" />
            <div class="services_text">
              <h3>Cold Beverages</h3>
              <p>
                Creamy and frothy cold coffee to make you feel cool from inside.
              </p>
            </div>
          </div>
          <div class="services_items">
            <img src="images/refreshment.png" alt="Refreshment" />
            <div class="services_text">
              <h3>Refreshment</h3>
              <p>Fruit and icy refreshing drink to make you feel good.</p>
            </div>
          </div>
          <div class="services_items">
            <img src="images/special_combos.png" alt="Special Combos" />
            <div class="services_text">
              <h3>Special Combos</h3>
              <p>
                Now it's really easy to chose your favourite eating and drinking
                combinations.
              </p>
            </div>
          </div>
          <div class="services_items">
            <img
              src="images/burger_frenchFries.png"
              alt="Burger & French Fries"
            />
            <div class="services_text">
              <h3>Burger & French Fries</h3>
              <p>Yummy! Quick bites to satisfy your small size hunger.</p>
            </div>
          </div>
          <div class="services_items">
            <img src="images/dessert.png" alt="Desserts" />
            <div class="services_text">
              <h3>Desserts</h3>
              <p>
                This for sure would satiate your palate and take you on a
                culinary treat.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Why Us Section -->
    <section class="why_us" id="why">
      <h2 class="section_title">Why Us?</h2>
      <div class="section_container">
        <div class="why_container">
          <div class="why_items">
            <img src="images/delicious.png" alt="Delicious" />
            <div class="why_us_text">
              <h3>Delicious Food</h3>
              <p>
                With a lavish spread of finger licking food, we serve to satisfy
                your palate and take you on a culinary treat.
              </p>
            </div>
          </div>
          <div class="why_items">
            <img src="images/pleasant.png" alt="Pleasant" />
            <div class="why_us_text">
              <h3>Pleasant Ambience</h3>
              <p>
                We seek to serve all our guests with the perfect dining
                experience. We provide perfect ambbience to cherish special
                moments.
              </p>
            </div>
          </div>
          <div class="why_items">
            <img src="images/hospitality.png" alt="Hospitality" />
            <div class="why_us_text">
              <h3>Hospitality</h3>
              <p>
                Our staff members are happy to help. We go the extra mile to
                make you happy.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery" id="gallery">
      <h2 class="section_title">Gallery</h2>
      <div class="section_container">
        <div class="gallery_container">
          <div class="gallery_items">
            <img src="images/gallery_1.jpg" alt="Gallery Image" />
          </div>
          <div class="gallery_items">
            <img src="images/gallery_2.jpg" alt="Gallery Image" />
          </div>
          <div class="gallery_items">
            <img src="images/gallery_3.jpg" alt="Gallery Image" />
          </div>
          <div class="gallery_items">
            <img src="images/gallery_4.jpg" alt="Gallery Image" />
          </div>
          <div class="gallery_items">
            <img src="images/gallery_5.jpg" alt="Gallery Image" />
          </div>
          <div class="gallery_items">
            <img src="images/gallery_6.jpg" alt="Gallery Image" />
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
      <h2 class="section_title">Contact Us</h2>
      <div class="section_container">
        <div class="contact_container">
          <div class="contact_form">
            <form action="#">
              <div class="field">
                <label for="Name">Full Name</label>
                <input type="text" id="Name" placeholder="Your Name" required />
              </div>
              <div class="field">
                <label for="email">Your Email</label>
                <input
                  type="text"
                  id="email"
                  placeholder="Your Email"
                  required
                />
              </div>
              <div class="field">
                <label for="number">Your Number</label>
                <input
                  type="number"
                  id="number"
                  placeholder="Your Contact Number"
                  required
                />
              </div>
              <div class="field">
                <label for="textarea">Textarea</label>
                <textarea
                  name="textarea"
                  id="textarea"
                  placeholder="Your Message"
                ></textarea>
              </div>

              <button class="button" id="submit">Submit</button>
            </form>
          </div>

          <div class="contact_text">
            <div class="contact_items">
              <i class="bx bx-current-location"></i>
              <div class="contact_details">
                <h3>Our Location</h3>
                <p>TamilNadu, Hosur</p>
              </div>
            </div>
            <div class="contact_items">
              <i class="bx bxs-envelope"></i>
              <div class="contact_details">
                <h3>General Enquries</h3>
                <p>coffeeshop@xyz.com</p>
              </div>
            </div>
            <div class="contact_items">
              <i class="bx bxs-phone-call"></i>
              <div class="contact_details">
                <h3>Call Us</h3>
                <p>+01 92728239</p>
              </div>
            </div>
            <div class="contact_items">
              <i class="bx bxs-time-five"></i>
              <div class="contact_details">
                <h3>Our Timing</h3>
                <p>Mon-Sun : 10:00 AM - 7:00 PM</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer>
      <div class="section_container">
        <div class="footer_section">
          <div class="footer_logo">
            <a href="index.html">
              <img src="images/coffee_logo.png" alt="Coffee Logo" />
              <h2>Coffee</h2>
            </a>
          </div>

          <div class="useful_links">
            <h3>Useful Links</h3>
            <ul>
              <li><a href="#about">About</a></li>
              <li><a href="#service">Services</a></li>
              <li><a href="#why">Why Us</a></li>
              <li><a href="#gallery">Gallery</a></li>
              <li><a href="#contact">Contact</a></li>
            </ul>
          </div>

          <div class="contact_us">
            <h3>Contact</h3>
            <ul>
              <li>
                <i class="bx bx-current-location"></i>
                <span>TamilNadu, Hosur</span>
              </li>
              <li>
                <i class="bx bxs-phone-call"></i> <span>+01 92728239</span>
              </li>
              <li>
                <i class="bx bxs-time-five"></i>
                <span>Mon-Sun : 10:00 AM - 7:00 PM</span>
              </li>
            </ul>
          </div>

          <div class="follow_us">
            <h3>Follow</h3>
            <i class="bx bxl-facebook-circle"></i>
            <i class="bx bxl-twitter"></i>
            <i class="bx bxl-instagram-alt"></i>
          </div>
        </div>
      </div>
    </footer>
    <script src="script.js"></script>
  </body>
</html>
```
```css
/* Importing Google font - Poppins */
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}


:root {

    --primary-color: #3b141c;
    --secondary-color: #f3961c;
    --dark-color: #252525;
    --white-color: #fff;
    --light-gray-color: #f2f2f2;
    --site-max-width: 1300px;
}

html {
    scroll-behavior: smooth;
}

body {
    background-color: var(--white-color);
}

a {
    text-decoration: none;
}

ul {
    list-style: none;
}

.section_container {
    margin: 0 auto;
    max-width: var(--site-max-width);
}

.section_title {
    text-align: center;
    padding: 60px 0 100px;
    font-size: 32px;
    font-family: "Righteous", sans-serif;
    text-transform: uppercase;
}

.section_title::after {
    content: '';
    width: 80px;
    background: var(--secondary-color);
    height: 5px;
    display: block;
    margin: 7px auto 0;
    border-radius: 8px;
}

/* Styling for the header section */
header {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1;
    background: var(--primary-color);
}

nav {
    display: flex;
    padding: 15px 0 15px 20px;
    justify-content: space-between;
    align-items: center;
    margin: 0 auto;
    max-width: var(--site-max-width);
}

nav .nav_logo a {
    display: flex;
    gap: 15px;
    align-items: center;
}

nav .nav_logo a img {
    max-width: 55px;
}

nav .nav_logo h2 {
    color: var(--white-color);
    font-weight: 600;
    font-size: 32px;
}

nav ul {
    display: flex;
    gap: 10px;
}

nav ul li a {
    display: block;
    padding: 10px 25px;
    font-size: 18px;
    font-weight: 500;
    color: var(--white-color);
    border-radius: 30px;
    transition: all 0.2s ease;
}

nav ul li a:hover {
    color: var(--primary-color);
    background-color: var(--secondary-color);
}

nav label {
    font-size: 32px;
    color: var(--white-color);
    cursor: pointer;
}

label .menu_btn,
label .close_btn {
    display: none;
}

#click {
    display: none;
}

/* Hero Section */
.hero_section {
    min-height: 100vh;
    background: var(--primary-color);
}

.hero_container {
    display: flex;
    gap: 20px;
    padding: 20px;
    align-items: center;
    padding-top: 85px;
    min-height: calc(100vh - 85px);
    justify-content: space-between;
}

.hero_container .text_section h2 {
    font-size: 40px;
    color: var(--secondary-color);
}

.hero_container .text_section h3 {
    font-size: 35px;
    font-weight: 600;
    color: var(--white-color);
    margin-top: 8px;
}

.hero_container .text_section p {
    font-size: 20px;
    font-weight: 400;
    color: var(--white-color);
    margin: 24px 0 40px;
    max-width: 70%;
}

.hero_container .hero_section_button {
    display: flex;
    gap: 24px;
}

.hero_container .hero_section_button .button {
    padding: 8px 28px;
    border: 2px solid transparent;
    outline: none;
    cursor: pointer;
    border-radius: 50px;
    background: var(--secondary-color);
    color: var(--primary-color);
    font-size: 18px;
    font-weight: 600;
    transition: all 0.4s ease;
}

.hero_container .hero_section_button .button:last-child {
    color: var(--white-color);
    border-color: var(--white-color);
    background: none;
}

.hero_container .hero_section_button .button:first-child:hover {
    color: var(--white-color);
    background: transparent;
    border-color: var(--white-color);
}

.hero_container .hero_section_button .button:last-child:hover {
    color: var(--primary-color);
    background: var(--secondary-color);
    border-color: var(--secondary-color);
}

.hero_container .image_section {
    max-width: 45%;
}

.hero_container .image_section img {
    width: 100%;
}

/* About Us Section */
.about_us {
    padding: 60px 20px 120px;
    background: var(--light-gray-color);
}

.about_container {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    align-items: center;
}

.about_container .text_section {
    max-width: 50%;
}

.about_container .text_section p {
    font-size: 18px;
    font-weight: 500;
    letter-spacing: 1px;
    line-height: 30px;
    text-align: center;
}

.about_container .image_section {
    max-width: 45%;
}

.about_container .image_section img {
    width: 100%;
}

/* Services Section */
.services {
    background: var(--dark-color);
    color: var(--white-color);
    padding: 60px 20px 120px;
}

.services .service_container {
    display: flex;
    justify-content: space-between;
    gap: 120px;
    align-items: center;
    flex-wrap: wrap;
}

.section_container .services_items img {
    width: 100%;
}

.section_container .services_items {
    width: calc(100% / 3 - 120px);
}

.services_items .services_text {
    text-align: center;
}

.services_items .services_text h3 {
    margin: 12px 0;
    font-weight: 600;
    font-size: 24px;
}

.services_items .services_text p {
    font-size: 17px;
}

/* Why Us Section */
.why_us {
    background: var(--light-gray-color);
    padding: 60px 20px 120px;
}

.why_us .why_container {
    display: flex;
    justify-content: space-between;
    gap: 80px;
    align-items: center;
    flex-wrap: wrap;
}

.why_container .why_items img {
    width: 30%;
    margin-bottom: 10px;
}

.why_container .why_items {
    width: calc(100% / 3 - 80px);
    padding: 12px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 12px;
}

.why_items .why_us_text {
    text-align: center;
}

.why_items .why_us_text h3 {
    margin: 20px 0;
    font-size: 22px;
}

.why_items .why_us_text p {
    font-size: 17px;
}

/* Gallery Section */
.gallery {
    background: var(--white-color);
    padding: 60px 20px 100px;
}

.gallery .gallery_container {
    display: flex;
    justify-content: space-between;
    gap: 32px;
    align-items: center;
    flex-wrap: wrap;
}

.gallery_container .gallery_items {
    width: calc(100% / 3 - 32px);
    overflow: hidden;
    border-radius: 8px;
}

.gallery .gallery_container img {
    width: 100%;
    border-radius: 8px;
    transition: transform 0.4s ease;
}

.gallery_container .gallery_items:hover img {
    transform: scale(1.3);
}

/* Contact Section */
.contact {
    background: var(--light-gray-color);
    padding: 60px 20px 100px;
}

.contact_container {
    display: flex;
    gap: 50px;
    align-items: center;
    justify-content: space-between;
}

.contact_container .contact_form {
    max-width: 65%;
    width: 100%;
}

.contact_container .contact_form .field {
    margin: 20px 0;
}

.contact_container .contact_form .field label {
    display: block;
    font-size: 17px;
    font-weight: 500;
    margin-bottom: 8px;
}

.contact_container .contact_form .field input {
    width: 100%;
    height: 50px;
    padding: 0 12px;
    font-size: 16px;
    border-radius: 6px;
    border: 1px solid #ccc;
}

.contact_container .contact_form textarea {
    width: 100%;
    height: 200px;
    padding: 12px;
    font-size: 16px;
    border-radius: 8px;
    border: 1px solid #ccc;
    resize: vertical;
}

.contact_container .contact_form .button {
    padding: 8px 28px;
    border: 2px solid transparent;
    outline: none;
    cursor: pointer;
    border-radius: 50px;
    background: var(--primary-color);
    color: var(--white-color);
    font-size: 17px;
    font-weight: 600;
    transition: all 0.4s ease;
}

.contact_container .contact_form .button:hover {
    color: var(--primary-color);
    background: transparent;
    border-color: var(--primary-color);
}

.contact_text .contact_items {
    display: flex;
    gap: 20px;
    margin: 80px 0;
}

.contact_text .contact_items i {
    font-size: 32px;
    margin-top: 5px;
}

/* Footer Section */
footer {
    background: #1b1b1b;
    color: var(--white-color);
    padding: 60px 20px;
}

.footer_section {
    display: flex;
    justify-content: space-between;
}

.footer_section h3 {
    font-size: 22px;
    margin-bottom: 16px;
    font-weight: 600;
}

.footer_section .footer_logo a {
    display: flex;
    gap: 15px;
    align-items: center;
    color: var(--white-color);
}

.footer_section .footer_logo a img {
    max-width: 55px;
}

.footer_section .footer_logo a h2 {
    font-weight: 600;
}

.footer_section .useful_links ul li {
    margin: 20px 0;
}

.footer_section .useful_links ul li a {
    color: var(--white-color);
    font-size: 17px;
}

.footer_section .useful_links ul li a:hover {
    text-decoration: underline;
}

.footer_section .contact_us ul li {
    margin: 20px 0;
    display: flex;
    align-items: center;
    gap: 20px;
}

.footer_section .contact_us ul li i {
    font-size: 25px;
}

.footer_section .contact_us ul li span {
    font-size: 17px;
}

.footer_section .follow_us i {
    font-size: 26px;
    margin-right: 25px;
    cursor: pointer;
    transition: all 0.3s ease;
}

.footer_section .follow_us i:hover {
    color: var(--secondary-color);
}
```



## OUTPUT
![screencapture-127-0-0-1-5500-index-html-2025-04-30-08_30_43](https://github.com/user-attachments/assets/dd8a10ec-8e3d-4dd8-b90a-e9951bfe9171)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
