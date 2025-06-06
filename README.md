# Html-Css-Js-Php-C-Python
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
    />
    <link rel="stylesheet" href="styles.css" />
    <title>Web Design Mastery | SKYWINGS</title>
  </head>
  <body>
    <nav>
      <div class="nav__header">
        <div class="nav__logo">
          <a href="#" class="logo">Skywings</a>
        </div>
        <div class="nav__menu__btn" id="menu-btn">
          <i class="ri-menu-line"></i>
        </div>
      </div>
      <ul class="nav__links" id="nav-links">
        <li><a href="#home">HOME</a></li>
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#tour">TOUR</a></li>
        <li><a href="#package">PACKAGE</a></li>
        <li><a href="#contact">CONTACT</a></li>
        <li><a href="#">BOOK TRIP</a></li>
      </ul>
      <div class="nav__btns">
        <button class="btn">BOOK TRIP</button>
      </div>
    </nav>

    <header id="home">
      <div class="header__container">
        <div class="header__content">
          <p>ELEVATE YOUR TRAVEL JOURNEY</p>
          <h1>Experience The Magic Of Flight!</h1>
          <div class="header__btns">
            <button class="btn">Book A Trip Now</button>
            <a href="#">
              <span><i class="ri-play-circle-fill"></i></span>
            </a>
          </div>
        </div>
        <div class="header__image">
          <img src="assets/header.png" alt="header" />
        </div>
      </div>
    </header>

    <section class="section__container destination__container" id="about">
      <h2 class="section__header">Popular Destination</h2>
      <p class="section__description">
        Discover the Most Loved Destinations Around the Globe
      </p>
      <div class="destination__grid">
        <div class="destination__card">
          <img src="assets/destination-1.jpg" alt="destination" />
          <div class="destination__card__details">
            <div>
              <h4>Tradition and Futurism</h4>
              <p>New York City, USA</p>
            </div>
            <div class="destination__rating">
              <span><i class="ri-star-fill"></i></span>
              4.7
            </div>
          </div>
        </div>
        <div class="destination__card">
          <img src="assets/destination-2.jpg" alt="destination" />
          <div class="destination__card__details">
            <div>
              <h4>The City of Lights</h4>
              <p>Paris, France</p>
            </div>
            <div class="destination__rating">
              <span><i class="ri-star-fill"></i></span>
              4.5
            </div>
          </div>
        </div>
        <div class="destination__card">
          <img src="assets/destination-3.jpg" alt="destination" />
          <div class="destination__card__details">
            <div>
              <h4>Island of the Gods</h4>
              <p>Bali, Indonesia</p>
            </div>
            <div class="destination__rating">
              <span><i class="ri-star-fill"></i></span>
              4.8
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section__container journey__container" id="tour">
      <h2 class="section__header">Journey To The Sky Made Simple!</h2>
      <p class="section__description">
        Effortless Planning for Your Next Adventure
      </p>
      <div class="journey__grid">
        <div class="journey__card">
          <div class="journey__card__bg">
            <span><i class="ri-bookmark-3-line"></i></span>
            <h4>Seamless Booking Process</h4>
          </div>
          <div class="journey__card__content">
            <span><i class="ri-bookmark-3-line"></i></span>
            <h4>Easy Reservations, One Click Away</h4>
            <p>
              From flights and accommodations to activities and transfers,
              everything you need is available at your fingertips, making travel
              planning effortless.
            </p>
          </div>
        </div>
        <div class="journey__card">
          <div class="journey__card__bg">
            <span><i class="ri-landscape-fill"></i></span>
            <h4>Tailored Itineraries</h4>
          </div>
          <div class="journey__card__content">
            <span><i class="ri-landscape-fill"></i></span>
            <h4>Customized Plans Just for You</h4>
            <p>
              Enjoy personalized travel plans designed to match your preferences
              and interests. Whether you seek adventure or cultural immersion,
              our tailored itineraries ensure your journey is uniquely yours.
            </p>
          </div>
        </div>
        <div class="journey__card">
          <div class="journey__card__bg">
            <span><i class="ri-map-2-line"></i></span>
            <h4>Expert Local Insights</h4>
          </div>
          <div class="journey__card__content">
            <span><i class="ri-map-2-line"></i></span>
            <h4>Insider Tips and Recommendations</h4>
            <p>
              We provide curated recommendations for dining, sightseeing, and
              hidden gems, so you can experience each destination like a local.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="section__container showcase__container" id="package">
      <div class="showcase__image">
        <img src="assets/showcase.jpg" alt="showcase" />
      </div>
      <div class="showcase__content">
        <h4>UNLEASH WANDERLUST WITH SKYWINGS</h4>
        <p>
          Embark on a journey like no other with Skywings, where your travel
          dreams come to life. Our mission is to inspire and facilitate your
          adventures, whether you seek the vibrant energy of bustling
          cityscapes, the serene beauty of pristine beaches, or the captivating
          history of ancient landmarks. At Skywings, we provide expertly curated
          destinations and personalized itineraries, ensuring that every trip is
          tailored to your unique preferences. Discover hidden gems, immerse
          yourself in diverse cultures, and create unforgettable memories that
          will last a lifetime.
        </p>
        <p>
          With Skywings as your ultimate travel companion, exploring the wonders
          of the world has never been easier. Our insider tips and local
          insights give you the tools to navigate new places with confidence and
          excitement. From the moment you start planning to the day you return
          home, we are dedicated to making your travel experience seamless and
          enriching.
        </p>
        <div class="showcase__btn">
          <button class="btn">
            Book A Flight Now
            <span><i class="ri-arrow-right-line"></i></span>
          </button>
        </div>
      </div>
    </section>

    <section class="section__container banner__container">
      <div class="banner__card">
        <h4>10+</h4>
        <p>Years Experience</p>
      </div>
      <div class="banner__card">
        <h4>12K</h4>
        <p>Happy Clients</p>
      </div>
      <div class="banner__card">
        <h4>4.8</h4>
        <p>Overall Ratings</p>
      </div>
    </section>

    <section class="section__container discover__container">
      <h2 class="section__header">Discover The World From Above</h2>
      <p class="section__description">
        Experience Breathtaking Views and Unique Perspectives
      </p>
      <div class="discover__grid">
        <div class="discover__card">
          <span><i class="ri-camera-lens-line"></i></span>
          <h4>Aerial Cityscapes</h4>
          <p>
            Witness the architectural marvels and bustling streets from
            bird's-eye view, offering a unique perspective.
          </p>
        </div>
        <div class="discover__card">
          <span><i class="ri-ship-line"></i></span>
          <h4>Coastal Wonders</h4>
          <p>
            Fly over pristine coastlines and turquoise waters, revealing hidden
            coves and vibrant coral reefs.
          </p>
        </div>
        <div class="discover__card">
          <span><i class="ri-landscape-line"></i></span>
          <h4>Historic Landmarks</h4>
          <p>
            Observe the grandeur of ancient castles and other significant sites
            in a way that ground tours can't offer.
          </p>
        </div>
      </div>
    </section>

    <section class="section__container client__container">
      <h2 class="section__header">Loved By Over Thousand Travelers</h2>
      <p class="section__description">
        Discover the stories of wanderlust and cherished memories through the
        eyes of our valued clients.
      </p>
      <!-- Slider main container -->
      <div class="swiper">
        <!-- Additional required wrapper -->
        <div class="swiper-wrapper">
          <!-- Slides -->
          <div class="swiper-slide">
            <div class="client__card">
              <div class="client__content">
                <div class="client__rating">
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                </div>
                <p>
                  Skywings has completely transformed my travel experience. From
                  finding hidden gems in bustling cities to discovering serene
                  retreats off the beaten path, every detail was thoughtfully
                  arranged. I can't recommend Skywings enough for anyone looking
                  to elevate their travel experience!
                </p>
              </div>
              <div class="client__details">
                <img src="assets/client-1.jpg" alt="client" />
                <div>
                  <h4>John Adams</h4>
                  <h5>Travel Blogger</h5>
                </div>
              </div>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="client__card">
              <div class="client__content">
                <div class="client__rating">
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                </div>
                <p>
                  My recent adventure with Skywings was nothing short of
                  spectacular. The personalized itineraries and recommendations
                  they provided led me to extraordinary locations that I would
                  never have found on my own. I'm already planning my next
                  adventure with them!
                </p>
              </div>
              <div class="client__details">
                <img src="assets/client-2.jpg" alt="client" />
                <div>
                  <h4>Emily Thompson</h4>
                  <h5>Adventure Enthusiast</h5>
                </div>
              </div>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="client__card">
              <div class="client__content">
                <div class="client__rating">
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                </div>
                <p>
                  Skywings offered a transformative experience for my research
                  into historical landmarks. The unique aerial perspectives and
                  provided a new level of appreciation and insight into the
                  sites I studied. I highly recommend their services to fellow
                  historians and cultural enthusiasts.
                </p>
              </div>
              <div class="client__details">
                <img src="assets/client-3.jpg" alt="client" />
                <div>
                  <h4>Sarah Lee</h4>
                  <h5>Cultural Historian</h5>
                </div>
              </div>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="client__card">
              <div class="client__content">
                <div class="client__rating">
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                  <span><i class="ri-star-fill"></i></span>
                </div>
                <p>
                  Finding a balance between work and travel can be challenging,
                  but Skywings made it effortless. Their efficient planning and
                  excellent recommendations helped me maximize my downtime and
                  enjoy every moment of my trip. I look forward to working with
                  them again on future travels.
                </p>
              </div>
              <div class="client__details">
                <img src="assets/client-4.jpg" alt="client" />
                <div>
                  <h4>David Patel</h4>
                  <h5>Business Executive</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer id="contact">
      <div class="section__container footer__container">
        <div class="footer__col">
          <div class="footer__logo">
            <a href="#" class="logo">Skywings</a>
          </div>
          <p>
            Explore the world with ease and excitement through our comprehensive
            travel platform. Your journey begins here, where seamless planning
            meets unforgettable experiences.
          </p>
          <ul class="footer__socials">
            <li>
              <a href="#"><i class="ri-facebook-fill"></i></a>
            </li>
            <li>
              <a href="#"><i class="ri-instagram-line"></i></a>
            </li>
            <li>
              <a href="#"><i class="ri-youtube-line"></i></a>
            </li>
          </ul>
        </div>
        <div class="footer__col">
          <h4>Quick Links</h4>
          <ul class="footer__links">
            <li><a href="#">Home</a></li>
            <li><a href="#">Flights</a></li>
            <li><a href="#">Hotels</a></li>
            <li><a href="#">Cruise</a></li>
          </ul>
        </div>
        <div class="footer__col">
          <h4>Contact Us</h4>
          <ul class="footer__links">
            <li>
              <a href="#">
                <span><i class="ri-phone-fill"></i></span> +91 9876543210
              </a>
            </li>
            <li>
              <a href="#">
                <span><i class="ri-record-mail-line"></i></span> info@skywings
              </a>
            </li>
            <li>
              <a href="#">
                <span><i class="ri-map-pin-2-fill"></i></span> New Delhi, India
              </a>
            </li>
          </ul>
        </div>
        <div class="footer__col">
          <h4>Subscribe</h4>
          <form action="/">
            <input type="text" placeholder="Enter your email" />
            <button class="btn">Subscribe</button>
          </form>
        </div>
      </div>
      <div class="footer__bar">
        Copyright © 2024 Web Design Mastery. All rights reserved.
      </div>
    </footer>

    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    <script src="main.js"></script>
  </body>
</html>

CSS File Name :

@import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&display=swap");

:root {
  --primary-color: #2887ff;
  --primary-color-dark: #2476da;
  --text-dark: #0a0a0a;
  --text-light: #737373;
  --extra-light: #f3f4f6;
  --white: #ffffff;
  --max-width: 1200px;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.section__container {
  max-width: var(--max-width);
  margin: auto;
  padding: 5rem 1rem;
}

.section__header {
  margin-bottom: 5px;
  font-size: 2.5rem;
  font-weight: 700;
  color: var(--text-dark);
  text-align: center;
}

.section__description {
  max-width: 600px;
  margin-inline: auto;
  color: var(--text-light);
  text-align: center;
}

.btn {
  padding: 0.75rem 1.5rem;
  outline: none;
  border: none;
  font-size: 1rem;
  white-space: nowrap;
  color: var(--white);
  background-color: var(--primary-color);
  border-radius: 5rem;
  transition: 0.3s;
  cursor: pointer;
}

.btn:hover {
  background-color: var(--primary-color-dark);
}

.logo {
  font-size: 1.75rem;
  font-weight: 800;
  color: var(--text-dark);
}

img {
  display: flex;
  width: 100%;
}

a {
  text-decoration: none;
  transition: 0.3s;
}

ul {
  list-style: none;
}

html,
body {
  scroll-behavior: smooth;
}

body {
  font-family: "DM Sans", sans-serif;
}

nav {
  position: fixed;
  isolation: isolate;
  top: 0;
  width: 100%;
  z-index: 9;
}

.nav__header {
  padding: 1rem;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: var(--primary-color);
}

.nav__logo .logo {
  font-size: 1.5rem;
  color: var(--white);
}

.nav__menu__btn {
  font-size: 1.5rem;
  color: var(--white);
  cursor: pointer;
}

.nav__links {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 2rem;
  background-color: var(--primary-color);
  transition: transform 0.5s;
  z-index: -1;
}

.nav__links.open {
  transform: translateY(100%);
}

.nav__links a {
  font-weight: 600;
  color: var(--white);
  white-space: nowrap;
}

.nav__links a:hover {
  color: var(--text-dark);
}

.nav__btns {
  display: none;
}

header {
  margin-top: 5rem;
  padding-inline: 1rem;
  position: relative;
  isolation: isolate;
  overflow: hidden;
}

header::before {
  position: absolute;
  content: "";
  height: 100%;
  width: calc(100% - 2rem);
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-image: url("assets/header-bg.jpg");
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  border-radius: 3rem;
  z-index: -1;
}

.header__container {
  display: grid;
}

.header__content {
  padding: 4rem 1rem;
}

.header__content p {
  margin-bottom: 5px;
  font-size: 1rem;
  font-weight: 600;
  color: var(--text-dark);
  text-align: center;
}

.header__content h1 {
  margin-bottom: 2rem;
  font-size: 4.5rem;
  font-weight: 600;
  color: var(--text-dark);
  line-height: 5.5rem;
  text-align: center;
}

.header__btns {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 1rem;
}

.header__btns .btn {
  padding: 1rem 2rem;
}

.header__btns a {
  padding: 9px 13px;
  font-size: 1.5rem;
  color: var(--primary-color);
  background-color: var(--white);
  border-radius: 100%;
}

.header__btns a:hover {
  color: var(--white);
  background-color: var(--primary-color);
}

.destination__container :is(.section__header, .section__description) {
  text-align: left;
  margin-inline-start: unset;
}

.destination__grid {
  margin-top: 4rem;
  display: grid;
  gap: 2rem 1rem;
}

.destination__card img {
  border-radius: 1.5rem;
  box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.2);
}

.destination__card__details {
  padding: 1rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}

.destination__card__details h4 {
  margin-bottom: 5px;
  font-size: 1.2rem;
  font-weight: 600;
  columns: var(--text-dark);
}

.destination__card__details p {
  columns: var(--text-light);
}

.destination__rating {
  padding: 5px 10px;
  font-size: 0.9rem;
  white-space: nowrap;
  color: var(--white);
  background-color: var(--primary-color);
  border-radius: 1rem;
  transition: 0.3s;
}

.destination__card:hover .destination__rating {
  background-color: var(--primary-color-dark);
}

.journey__grid {
  margin-top: 2rem;
  display: grid;
  gap: 0 1rem;
}

.journey__card {
  position: relative;
  isolation: isolate;
  padding-top: 4rem;
  overflow: hidden;
}

.journey__card__bg {
  padding: 2rem;
  background-color: var(--extra-light);
  border-top-right-radius: 1rem;
  border-top-left-radius: 1rem;
}

.journey__card__bg span {
  display: inline-block;
  margin-bottom: 4rem;
  font-size: 1.75rem;
  color: var(--primary-color);
}

.journey__card__bg h4 {
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--text-dark);
}

.journey__card__content {
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
  height: 100%;
  padding: 2rem;
  background-color: var(--primary-color);
  border-top-right-radius: 1rem;
  border-top-left-radius: 1rem;
  transition: 0.3s;
}

.journey__card:hover .journey__card__content {
  top: 0;
}

.journey__card__content span {
  display: inline-block;
  margin-bottom: 1rem;
  padding: 7px 9px;
  font-size: 1rem;
  color: var(--white);
  border: 2px solid var(--white);
  border-radius: 100%;
}

.journey__card__content h4 {
  margin-bottom: 1rem;
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--white);
}

.journey__card__content p {
  color: var(--extra-light);
}

.showcase__container {
  display: grid;
  gap: 2rem;
  overflow: hidden;
}

.showcase__image img {
  max-width: 400px;
  margin-inline: auto;
  box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.2);
}

.showcase__content h4 {
  margin-bottom: 2rem;
  font-size: 3rem;
  font-weight: 600;
  color: var(--text-dark);
}

.showcase__content p {
  margin-bottom: 1rem;
  color: var(--text-light);
}

.showcase__content .btn {
  width: 100%;
  margin-top: 2rem;
  padding: 1.5rem;
  font-weight: 600;
  color: var(--text-dark);
  background-image: url("assets/header-bg.jpg");
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  border-radius: 5px;
}

.banner__container {
  display: grid;
  gap: 2rem;
}

.banner__card {
  padding: 2rem 1rem;
  text-align: center;
  background-color: var(--extra-light);
  border-radius: 2rem;
  box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.1);
}

.banner__card h4 {
  font-size: 5rem;
  font-weight: 500;
  color: var(--primary-color);
}

.banner__card p {
  color: var(--text-light);
}

.discover__grid {
  margin-top: 4rem;
  display: grid;
  gap: 2rem;
}

.discover__card {
  padding: 2rem 1rem;
  text-align: center;
  transition: 0.3s;
  border-radius: 1rem;
}

.discover__card:hover {
  box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.1);
}

.discover__card span {
  display: inline-block;
  margin-bottom: 1rem;
  padding: 10px 15px;
  font-size: 1.5rem;
  color: var(--primary-color);
  background-color: rgba(40, 135, 255, 0.1);
  border-radius: 100%;
}

.discover__card h4 {
  max-width: 150px;
  margin-inline: auto;
  margin-bottom: 1rem;
  font-size: 1.2rem;
  font-weight: 700;
  color: var(--text-dark);
}

.destination__card p {
  color: var(--text-light);
}

.swiper {
  margin-top: 4rem;
  width: 100%;
}

.swiper-slide {
  min-width: 375px;
}

.client__card {
  padding: 5px;
  background-color: var(--extra-light);
  border-radius: 1rem;
  transition: 0.3s;
}

.client__card:hover {
  background-color: var(--primary-color);
}

.client__content {
  padding: 1rem;
  background-color: var(--white);
  border-radius: calc(1rem - 5px);
}

.client__rating {
  margin-bottom: 1rem;
  color: var(--primary-color);
}

.client__content p {
  color: var(--text-dark);
}

.client__details {
  padding: 1rem;
  display: flex;
  align-items: center;
  gap: 1rem;
}

.client__details img {
  max-width: 50px;
  border-radius: 100%;
}

.client__details h4 {
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--text-dark);
  transition: 0.3s;
}

.client__card:hover h4 {
  color: var(--white);
}

.client__details h5 {
  font-size: 1rem;
  font-weight: 500;
  color: var(--text-light);
  transition: 0.3s;
}

.client__card:hover h5 {
  color: var(--extra-light);
}

footer {
  background-color: var(--extra-light);
}

.footer__container {
  display: grid;
  gap: 4rem 2rem;
}

.footer__col p {
  max-width: 300px;
  margin-block: 2rem;
  color: var(--text-light);
}

.footer__socials {
  display: flex;
  align-items: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.footer__socials a {
  display: inline-block;
  padding: 7px 10px;
  font-size: 1.25rem;
  color: var(--white);
  background-color: var(--primary-color);
  border-radius: 100%;
}

.footer__socials a:hover {
  background-color: var(--primary-color-dark);
}

.footer__col h4 {
  margin-bottom: 2rem;
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--text-dark);
}

.footer__links {
  display: grid;
  gap: 1rem;
}

.footer__links a {
  display: flex;
  align-items: center;
  gap: 10px;
  color: var(--text-light);
}

.footer__links a:hover {
  color: var(--primary-color);
}

.footer__links a span {
  font-size: 1.25rem;
}

.footer__col form {
  display: grid;
  gap: 1rem;
}

.footer__col input {
  padding: 0.75rem;
  font-size: 1rem;
  color: var(--text-dark);
  background-color: var(--white);
  border: 1px solid var(--text-light);
  border-radius: 5px;
}

.footer__col input::placeholder {
  color: var(--text-light);
}

.footer__col .btn {
  border-radius: 5px;
}

.footer__bar {
  padding: 1rem;
  font-size: 0.9rem;
  color: var(--text-light);
  text-align: center;
}

@media (width > 540px) {
  .destination__grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .journey__grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .showcase__container {
    grid-template-columns: repeat(2, 1fr);
    align-items: center;
  }

  .banner__container {
    grid-template-columns: repeat(2, 1fr);
  }

  .discover__grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .footer__container {
    grid-template-columns: repeat(2, 1fr);
  }

  .footer__col:last-child {
    grid-area: 2/1/3/2;
  }
}

@media (width > 768px) {
  nav {
    position: static;
    padding: 2rem 1rem;
    max-width: var(--max-width);
    margin-inline: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
  }

  .nav__header {
    flex: 1;
    padding: 0;
    background-color: transparent;
  }

  .nav__logo .logo {
    color: var(--text-dark);
  }

  .nav__menu__btn {
    display: none;
  }

  .nav__links {
    position: static;
    width: fit-content;
    padding: 0;
    flex-direction: row;
    background-color: transparent;
    transform: none !important;
  }

  .nav__links a {
    color: var(--text-dark);
  }

  .nav__links a:hover {
    color: var(--primary-color);
  }

  .nav__links li:last-child {
    display: none;
  }

  .nav__btns {
    flex: 1;
    display: flex;
    justify-content: flex-end;
  }

  .nav__btns button {
    padding: 0.75rem 2rem;
    background-color: var(--text-dark);
  }

  header {
    margin-top: 0;
  }

  .header__container {
    grid-template-columns:
      minmax(0, 1fr)
      repeat(5, minmax(0, calc(var(--max-width) / 5)))
      minmax(0, 1fr);
  }

  .header__content {
    grid-column: 2/4;
    padding-block: 8rem;
  }

  .header__content :is(p, h1) {
    text-align: left;
  }

  .header__btns {
    justify-content: flex-start;
  }

  .header__image {
    grid-column: 4/8;
    position: relative;
    isolation: isolate;
    height: 100%;
  }

  .header__image img {
    position: absolute;
    top: 2rem;
    left: 0;
    height: 100%;
    width: unset;
  }

  .destination__grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .journey__grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .showcase__container {
    grid-template-columns: repeat(3, 1fr);
  }

  .showcase__content {
    grid-column: 2/4;
  }

  .banner__container {
    grid-template-columns: repeat(3, 1fr);
  }

  .discover__grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .footer__container {
    grid-template-columns: 2fr 1fr 1fr 1.5fr;
  }

  .footer__col:last-child {
    grid-area: unset;
  }
}

@media (width > 1200px) {
  .header__content {
    padding-inline: 1rem 0;
  }

  .destination__grid {
    gap: 2rem;
  }
}


Main Js Flie Name :
const menuBtn = document.getElementById("menu-btn");
const navLinks = document.getElementById("nav-links");
const menuBtnIcon = menuBtn.querySelector("i");

menuBtn.addEventListener("click", (e) => {
  navLinks.classList.toggle("open");

  const isOpen = navLinks.classList.contains("open");
  menuBtnIcon.setAttribute("class", isOpen ? "ri-close-line" : "ri-menu-line");
});

navLinks.addEventListener("click", (e) => {
  navLinks.classList.remove("open");
  menuBtnIcon.setAttribute("class", "ri-menu-line");
});

const scrollRevealOption = {
  origin: "bottom",
  distance: "50px",
  duration: 1000,
};

ScrollReveal().reveal(".header__image img", {
  ...scrollRevealOption,
  origin: "right",
});
ScrollReveal().reveal(".header__content p", {
  ...scrollRevealOption,
  delay: 500,
});
ScrollReveal().reveal(".header__content h1", {
  ...scrollRevealOption,
  delay: 1000,
});
ScrollReveal().reveal(".header__btns", {
  ...scrollRevealOption,
  delay: 1500,
});

ScrollReveal().reveal(".destination__card", {
  ...scrollRevealOption,
  interval: 500,
});

ScrollReveal().reveal(".showcase__image img", {
  ...scrollRevealOption,
  origin: "left",
});
ScrollReveal().reveal(".showcase__content h4", {
  ...scrollRevealOption,
  delay: 500,
});
ScrollReveal().reveal(".showcase__content p", {
  ...scrollRevealOption,
  delay: 1000,
});
ScrollReveal().reveal(".showcase__btn", {
  ...scrollRevealOption,
  delay: 1500,
});

ScrollReveal().reveal(".banner__card", {
  ...scrollRevealOption,
  interval: 500,
});

ScrollReveal().reveal(".discover__card", {
  ...scrollRevealOption,
  interval: 500,
});

const swiper = new Swiper(".swiper", {
  slidesPerView: 3,
  spaceBetween: 20,
  loop: true,
});

