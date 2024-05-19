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


