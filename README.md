# HCI
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Car Rental Website</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
</head>
<body>
  <header>
    <a href="#" class="logo">
      <img src="https://scontent.fcgy2-2.fna.fbcdn.net/v/t39.30808-6/358604864_656893773126319_2908540642411125623_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGEfspdq8qHYf6sm5WqJvaJgbaPvpSoPICBto--lKg8gL4HxCx-ovGUWPr68KvtKrU4AGm17z2WmOdmJmf8TpOH&_nc_ohc=x5eNSqBK0YAQ7kNvgGmZaAA&_nc_oc=AdiYZkBGC-h5U_FuFYvxXKrMraasMEBZAYuSUqb73TZ-JiCGj0-MlIDWynTuulHVQsM&_nc_ht=scontent.fcgy2-2.fna&oh=00_AYB3Jt2jt8CxfaSPR3OvxhQ7WbmOY4VyzWvZ8N0hdN1Szw&oe=664F525C" alt="">
    </a>
    <div class="bx bx-menu" id="menu-icon"></div>
    <ul class="navbar">
      <li><a href="#home">Home</a></li>
      <li><a href="#ride">Ride</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#reviews">Reviews</a></li>
    </ul>
    <div class="header-btn">
      <a href="#" class="sign up">Sign up</a>
      <a href="#" class="sign in">Sign in</a>       
    </div>
  </header>
  
  <section class="home" id="home">
    <div class="text">
      <h1><span>Looking</span> to <br>rent a car</h1>
      <p>Kinsmen Transport Services(KTS Express) is a vibrant land transport company which provides Best cars with the best prices</p>
      <div class="app-store">
        <img src="https://lifeokshop.com/public/img/apple.png" alt="">
        <img src="https://digianafresh.com/web/images/miscellaneous/google-play-btn.png" alt="">
      </div>
    </div>
    <div class="form-container">
      <form action="">
        <div class="input-box">
          <span>Location</span>
          <input type="search" placeholder="Search Places">
        </div>
        <div class="input-box">
          <span>Pick-up date</span>
          <input type="date">
        </div>
        <div class="input-box">
          <span>Return Date</span>
          <input type="date">
        </div>
        <input type="submit" class="btn">
      </form>
    </div>
  </section>
  
  <section class="ride" id="ride">
    <div class="heading">
      <span>How It Works</span>
      <h1>Rent with 3 Easy Steps</h1>
    </div>
    <div class="ride-container">
      <div class="box">
        <i class='bx bxs-map'></i>
        <h2>Choose A Location</h2>
        <p>Kinsmen Transport Services(KTS Express) is a vibrant land transport company which provides Best cars with the best prices</p>
      </div>
      <div class="box">
        <i class='bx bxs-calendar-check'></i>
        <h2>Pick-up Date</h2>
        <p>Kinsmen Transport Services(KTS Express) is a vibrant land transport company which provides Best cars with the best prices</p>
      </div>
      <div class="box">
        <i class='bx bxs-calendar-star'></i>
        <h2>Book A Car</h2>
        <p>Kinsmen Transport Services(KTS Express) is a vibrant land transport company which provides Best cars with the best prices</p>
      </div>
    </div>
  </section>
  
  <section class="services" id="services">
    <div class="heading">
      <span>Best Services</span>
      <h1>Explore Our Top Deals <br> From Top Rated Dealers</h1>
    </div>
    <div class="services-container">
      <div class="box">
        <div class="box-img">
          <img src="https://www.autotrader.com/wp-content/uploads/2020/08/2021-honda-civic-hatchback-front-left-side.jpg?resize=880" alt="">
        </div>
        <p>2021</p>
        <h3>Honda Civic</h3>
        <h2>₱ 1,500 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
      <div class="box">
        <div class="box-img">
          <img src="https://nextrift.com/wp-content/uploads/2020/11/toyota-vios-2020-1.jpg" alt="">
        </div>
        <p>2020</p>
        <h3>Toyota Vios</h3>
        <h2>₱ 1,200 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
      <div class="box">
        <div class="box-img">
          <img src="https://th.bing.com/th/id/R.ea9348b6b6de99e74daa0d9765ab7935?rik=phAGQ6hQnG9OpQ&riu=http%3a%2f%2fs1.paultan.org%2fimage%2f2020%2f09%2f2020-Honda-City-RS-i-MMD-Hybrid-at-MIMC-Exterior-9-1200x628.jpg&ehk=NbvlwtNnNIHS8CRlz%2bthcRxOLw3ewpbi710z3Dixg%2bU%3d&risl=&pid=ImgRaw&r=0" alt="">
        </div>
        <p>2023</p>
        <h3>Honda City</h3>
        <h2>₱ 1,500 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
      <div class="box">
        <div class="box-img">
          <img src="https://cdn.sanity.io/images/otg9j4oh/production/0cbf6e9ce0c0568838386e51ae338b735d0566ab-1000x644.png" alt="">
        </div>
        <p>2023</p>
        <h3>Ford Ranger</h3>
        <h2>₱ 3,500 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
      <div class="box">
        <div class="box-img">
          <img src="https://th.bing.com/th/id/R.a3f209d771cad6c2e6f4bf6ab1d8ba5f?rik=xXyCzdj5vM0YyA&riu=http%3a%2f%2fen.toyota-club.eu%2fgraphics%2fgallery%2ffull%2f868_toyota-hilux-2016-06.jpg&ehk=UqHpWIKZXl7qyEEbOne7J4lALtLgKWaPf8VW6nw7%2f3Y%3d&risl=&pid=ImgRaw&r=0" alt="">
        </div>
        <p>2023</p>
        <h3>Toyota Hilux</h3>
        <h2>₱ 3,500 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
      <div class="box">
        <div class="box-img">
          <img src="https://1.bp.blogspot.com/-ahUtBWzy0MY/X4qf5WEzRHI/AAAAAAAAGms/-j_6FgSrmpkf1Fd5QavS_OBC2XXmXSEMACLcBGAsYHQ/s2048/nissan%2B%252823%2529.jpg" alt="">
        </div>
        <p>2020</p>
        <h3>Nissan Navarra</h3>
        <h2>₱ 3,000 <span>/month</span></h2>
        <a href="#" class="btn">Rent Now</a>
      </div>
    </div>
  </section>
  
  <section class="about" id="about">
    <div class="heading"> 
      <div class="about-container">
        <div class="about-img">
          <img src="https://th.bing.com/th/id/R.8b01377204f7e5e60f3928fa9c6d8d8d?rik=veNTNapnhdPf5A&riu=http%3a%2f%2fpluspng.com%2fimg-png%2fpng-hd-images-of-cars-volkswagen-png-hd-1500.png&ehk=bzMQ1ueAXMsJzhilqNehN77R9uwSPUm8hoyg%2bCU3wYo%3d&risl=&pid=ImgRaw&r=0" alt="">
        </div>
        <div class="about-text">
          <span>About Us</span>
          <p>Don't let road bumps ruin your ride. With a durable and stylish vehicle, tackle any road with confidence and ease. From urban roads to off-roading, our vehicles are designed to provide smooth driving performance, passenger comfort, fun, and peace of mind.</p>
          <a href="#" class="btn">Learn More</a>
        </div>
      </div>
    </div>
  </section>
  
  <section class="reviews" id="reviews">
    <div class="heading">
      <span>Reviews</span>
      <h1>What Our Customers Say</h1>
    </div>
    <div class="reviews-container">
      <div class="box">
        <div class="rev-img">
          <img src="https://scontent.fceb1-1.fna.fbcdn.net/v/t1.18169-9/12308273_689432534525794_8913279651017866745_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGotVrqQSsj8uwYuIoanTWOiilUcqcqcIiKKVRypypwiIExgUk8eSiZI0taiJWOVBcZz__I6ArOWuZXk6Al1Glv&_nc_ohc=dIlPmeteyaYQ7kNvgFxCFbI&_nc_ht=scontent.fceb1-1.fna&oh=00_AYCZi7fWXZrP7qKD2vHXq4J4co6_FkSeD81iN_TIZ-SXOw&oe=6667F263" alt="">
        </div>
        <h2>Deniel Cuamag</h2>
        <div class="stars">
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
        </div>
        <p>Hahahhahahhaha pwede rasd</p>
      </div>
      <div class="box">
        <div class="rev-img">
          <img src="https://scontent.fceb1-5.fna.fbcdn.net/v/t39.30808-6/271799609_790030849057958_6212437058420222242_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFifJ4PuI0R-z7W-qrvCCD2EgOvZwjBPUUSA69nCME9Rfr9449ALoU1d4QX2Sz5XTqIgFD068JhfdXHv2QUAbWs&_nc_ohc=qAUHSX0oIoUQ7kNvgHZ4pmo&_nc_ht=scontent.fceb1-5.fna&oh=00_AYCitxsv3t5jbICaKR4yatOf5dOjEFuAdO_f8T_nkN3yKg&oe=664FA24F" alt="">
        </div>
        <h2>Lesther Quimpan</h2>
        <div class="stars">
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
        </div>
        <p>swito swito pasanginlan man nuon ta</p>
      </div>
      <div class="box">
        <div class="rev-img">
          <img src="https://scontent.fceb1-4.fna.fbcdn.net/v/t31.18172-8/13217103_185326331866704_1874129505756688739_o.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFHOub95joGfMWFJm0qxxNIb86s5y5jCdxvzqznLmMJ3EiBGE7NtbYYUe1CIKpiqvu4PkGtEdzXvqd4OQz4ynBX&_nc_ohc=p5ZeWb5j-roQ7kNvgHVQIYj&_nc_ht=scontent.fceb1-4.fna&oh=00_AYCsUCYgjYx7ErPe1wsI6JLMEuSqZYQwLdL3hzQYG4F0Kg&oe=6671350F" alt="">
        </div>
        <h2>Joseppe Alingalan</h2>
        <div class="stars">
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
          <i class='bx bxs-star'></i>
        </div>
        <p>Kani man jud oh!</p>
      </div>
    </div>
  </section>
  
  <section class="newsletter">
    <h2>Subscribe to Newsletter</h2>
    <div class="box">
      <input type="text" placeholder="Enter your email...">
      <a href="#" class="btn">Subscribe</a>
    </div>
  </section>
  
  <div class="copyright">
    <p>KTS express All rights reserved</p>
    <div class="social">
      <a href="#"><i class='bx bxl-facebook'></i></a>
      <a href="#"><i class='bx bxl-twitter'></i></a>
      <a href="#"><i class='bx bxl-instagram'></i></a>
    </div>
  </div>
  
  <script src="main.js"></script>
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-padding-top: 2rem;
  scroll-behavior: smooth;
  list-style: none;
  text-decoration: none;
  font-family: "Poppins", sans-serif;
}

:root {
  --main-color: blue;
  --second-color: white;
  --text-color: black;
  --gradient: linear-gradient(blue, white);
}

html::-webkit-scrollbar {
  width: 0.5rem;
}

html::-webkit-scrollbar-track {
  background: transparent;
}

html::-webkit-scrollbar-thumb {
  background: var(--main-color);
  border-radius: 5rem;
}

section {
  padding: 50px 100px;
}

header {
  position: fixed;
  width: 100%;
  top: 0;
  right: 0;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: white;
  padding: 15px 100px;
}

.logo img {
  width: 50px;
}

.navbar {
  display: flex;
}

.navbar li {
  position: relative;
}

.navbar a {
  font-size: 1rem;
  padding: 10px 20px;
  color: var(--text-color);
  font-weight: 500;
}

.navbar a::after {
  content: "";
  width: 0;
  height: 3px;
  background: var(--gradient);
  position: absolute;
  bottom: -4px;
  left: 0;
  transition: 0.5s;
}

.navbar a:hover::after {
  width: 100px;
}

#menu-icon {
  font-size: 24px;
  cursor: pointer;
  z-index: 10001;
  display: none;
}

.header-btn a {
  padding: 10px 20px;
  color: var(--text-color);
  font-weight: 500;
}

.header-btn .sign-in {
  background: #474fa0;
  color: white;
  border-radius: 0.5rem;
}

.header-btn .sign-in:hover {
  background: var(--main-color);
}

.home {
  width: 100%;
  min-height: 100vh;
  position: relative;
  background: url(https://th.bing.com/th/id/R.de0f4bf6e8075312a6eb20ad7044571a?rik=lfNj3XxNGm8pNw&riu=http%3a%2f%2fwww.hdwallpaperspulse.com%2fwp-content%2fuploads%2f2016%2f03%2f06%2fgrey-car-background.jpeg&ehk=Uj4%2fbbaFxFblSiF%2fcim9Q3DX8UR%2fQxr043KTMovOTXU%3d&risl=&pid=ImgRaw&r=0);
  background-repeat: no-repeat;
  background-position: center right;
  background-size: cover;
  display: grid;
  align-items: center;
  grid-template-columns: repeat(2, 1fr);
}

.text h1 {
  font-size: 3.5rem;
  letter-spacing: 2px;
}

.text span {
  color: orange;
}

.text p {
  margin: 0.5rem 0 1rem;
}

.app-store {
  display: flex;
}

.app-store img {
  width: 100px;
  margin-right: 1rem;
  cursor: pointer;
}

.form-container form {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 1rem;
  position: absolute;
  bottom: 4rem;
  left: 100px;
  background: white;
  padding: 20px;
  border-radius: 0.5rem;
}

.input-box {
  flex: 1 1 7rem;
  display: flex;
  flex-direction: column;
}

.input-box span {
  font-weight: 500;
}

.input-box input {
  padding: 7px;
  outline: none;
  border: none;
  background: white;
  border-radius: 0.5rem;
  font-size: 1rem;
}

.form-container form .btn {
  flex: 1 1 7rem;
  padding: 10px 34px;
  border: none;
  border-radius: 0.5rem;
  background: blue;
  color: white;
  font-size: 1rem;
  font-weight: 500;
}

.form-container form .btn:hover {
  background: orange;
}

.heading {
  text-align: center;
}

.heading span {
  font-weight: 500;
  text-transform: uppercase;
}

.heading h1 {
  font-size: 2rem;
}

.ride-container {
  display: grid;
  align-items: center;
  grid-template-columns: repeat(auto-fit, minmax(250px, auto));
  gap: 1rem;
  margin-top: 2rem;
}

.ride-container .box {
  text-align: center;
  padding: 20px;
}

.ride-container .box .box {
  font-size: 34px;
  padding: 10px;
  background: white;
  border-radius: 0.5rem;
  color: var(--main-color);
}

.ride-container .box h2 {
  font-size: 1.3rem;
  font-weight: 500;
  margin: 1.4rem 0 0.5rem;
}

.ride-container .box .bx:hover,
.ride-container .bx .bxs-calendar-check {
  background: var(--gradient);
  color: yellow;
}

.services-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, auto));
  gap: 1rem;
  margin-top: 2rem;
}

.services-container .box {
  padding: 10px;
  border-radius: 1rem;
  box-shadow: 1px 4px 41px rgba(0, 0, 0, 0.1);
}

.services-container .box .box-img {
  width: 100px;
  height: 200px;
}

.services-container .box .box-img img {
  width: 355%;
  height: 100%;
  border-radius: 0rem;
  object-fit: cover;
  object-position: center;
}

.services-container .box p {
  padding: 0 10px;
  border: 1px solid var(--text-color);
  width: 58px;
  border-radius: 0.5rem;
  margin: 1rem 0 1rem;
}

.services-container .box h3 {
  font-weight: 500;
}

.services-container .box h2 {
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--main-color);
  margin: 0.2rem 0 0.5rem;
}

.services-container .box h2 span {
  font-size: 0.8rem;
  font-weight: 500;
  color: var(--text-color);
}

.services-container .box .btn {
  display: flex;
  justify-content: center;
  background: grey;
  color: white;
  padding: 10px;
  border-radius: 0.5rem;
}

.services-container .box .btn:hover {
  background: var(--main-color);
}

.about-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  margin-top: 2rem;
  align-items: center;
  gap: 1rem;
  margin-top: 1rem;
}

.about-img img {
  width: 100%;
}

.about-text span {
  font-weight: 500;
  color: var(--main-color);
  text-transform: uppercase;
}

.about-text p {
  margin: 0.5rem 0 1.4rem;
}

.about-text .btn {
  padding: 10px 20px;
  background: grey;
  color: white;
  border-radius: 0.5rem;
}

.about-text .btn:hover {
  background: var(--main-color);
}

.reviews-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, auto));
  gap: 1rem;
  margin-top: 2rem;
}

.rev-img img {
  width: 100%;
  height: 100%;
  border-radius: 10%;
  object-fit: cover;
  object-position: center;
  border: 2px solid var(--second-color);
}

.reviews-container .box {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
  box-shadow: 1px 4px 41px rgba(0, 0, 0, 0.1);
  border-radius: 0.5rem;
}

.reviews-container .box h2 {
  font-size: 1.1rem;
  font-weight: 600;
  margin: 0.5rem 0 0.5rem;
}

.reviews-container .box p {
  font-style: italic;
}

.reviews-container .box .stars .bx {
  color: var(--main-color);
}

.newsletter {
  background: linear-gradient(to top right, red, yellow);
  display: flex;
  flex-direction: column;
  align-items: center;
}

.newsletter h2 {
  color: white;
  font-size: 1.8rem;
}

.newsletter .box {
  margin-top: 1rem;
  background: white;
  border-radius: 0.5rem;
  padding: 4px 8px;
  width: 350px;
  display: flex;
  justify-content: space-between;
}

.newsletter .box input {
  border: none;
  outline: none;
}

.newsletter .box .btn {
  background: blue;
  color: white;
  padding: 8px 20px;
  border-radius: 0.5rem;
}

.copyright {
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.social a {
  color: black;
  padding: 10px;
  font-size: 21px;
}

@media (max-width: 991px) {
  header {
    padding: 18px 40px;
  }

  section {
    padding: 50px 40px;
  }
}

@media (max-width: 881px) {
  .home {
    background-position: left;
  }

  .form-container form {
    bottom: 0.2rem;
    left: 40px;
  }
}

@media (max-width: 768px) {
  .header {
    padding: 11px 40px;
  }

  #menu-icon {
    display: initial;
  }

  .sign-up {
    display: none;
  }

  .text h1 {
    font-size: 2.5rem;
  }

  .home {
    grid-template-columns: 1fr;
  }

  .form-container form {
    position: unset;
  }

  .header .navbar {
    position: absolute;
    top: -500%;
    left: 0;
    right: 0;
    display: flex;
    flex-direction: column;
    background: white;
    box-shadow: 0 4px 4px rgba(0, 0, 0, 0.1);
    transition: 0.2s ease;
    text-align: left;
  }

  .navbar.active {
    top: 100%;
  }

  .navbar a {
    padding: 1rem;
    border-left: 2px solid var(--main-color);
    margin: 1rem;
    display: block;
  }

  .navbar a:hover {
    color: white;
    background: var(--main-color);
    border: none;
  }

  .navbar a::after {
    display: none;
  }

  .heading span {
    font-size: 0.9rem;
    font-weight: 600;
  }

  .heading h1 {
    font-size: 1.3rem;
  }

  .about-container {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .about-img {
    padding: 1rem;
    order: 2;
  }
}

@media (max-width: 568px) {
  .copyright {
    flex-direction: column;
  }

  .newsletter .box {
    width: 284px;
  }

  .form-container {
    padding-top: 2rem;
  }
}

@media (max-width: 350px) {
  header {
    padding: 6px 14px;
  }

  .logo img {
    width: 30px;
  }

  section {
    padding: 50px 14px;
  }

  .header-btn .sign-in {
    padding: 7px 10px;
    font-size: 14px;
    font-weight: 400;
  }

  .text h1 {
    font-size: 2rem;
  }

  .services-container {
    grid-template-columns: repeat(auto-fit, minmax(254px, auto));
  }
}

