<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="shortcut icon" href="ico.jpg" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://unpkg.com/boxicons@2.0.9/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="main.css" />
    <title>Karam Afandi</title>
  </head>
  <body class="hidden">
    <div class="loader-screen">
      <h2>Karam Afandi</h2>
      <p>Page is loading, please wait.</p>
    </div>
    <nav>
      <div class="container">
        <h1 class="logo">Karam Afandi</h1>
        <ul>
          <li><a href="#home" class="link-active">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
        </ul>
        <div class="hamburger">
          <div class="line-1"></div>
          <div class="line-2"></div>
          <div class="line-3"></div>
        </div>
      </div>
    </nav>
    <section id="home">
      <div class="container">
        <div class="left">
          <h2>Hi!<br />I am Karam.</h2>
          <div class="social">
            <a href="mailto:karam_afandi@yahoo.com" target="_blank"
              ><i class="bx bx-envelope"></i
            ></a>
            <a href="https://www.instagram.com/karamlyy/" target="_blank"
              ><i class="bx bxl-instagram"></i
            ></a>
            <a href="https://www.facebook.com/karamlyy/" target="_blank"
              ><i class="bx bxl-facebook"></i
            ></a>
            <a href="https://github.com/karamlyy" target="_blank"
              ><i class="bx bxl-github"></i
            ></a>
          </div>
        </div>
      </div>
    </section>
    <section id="about">
      <div class="container reveal">
        <h3 class="header-3">About me</h3>
        <p>
            I am Karam Afandi. I am 19 years old. I started web programming in 2019. 
            Although programming seemed difficult to me at first, I worked on myself 
            and overcame the difficulties. My biggest goal is to work as a web 
            developer at Rockstar. I think I will achieve my goal.You too will strive
            to achieve your goals, and in the end you will definitely achieve what you want. 
        </p>
      </div>
    </section>
    <section id="portfolio">
      <div class="container reveal">
        <h3 class="header-3">Portfolio</h3>
        <p class="paragraph">Knowledge</p>
        <div class="knowledge reveal">
          <div>
            <h5>HTML</h5>
            <div class="bar"></div>
          </div>
          <div>
            <h5>CSS</h5>
            <div class="bar"></div>
          </div>
          <div>
            <h5>Bootstrap</h5>
            <div class="bar"></div>
          </div>
          <div>
            <h5>JavaScript</h5>
            <div class="bar"></div>
          </div>
          <div>
            <h5>JQuery</h5>
            <div class="bar"></div>
          </div>
          <div>
            <h5>React</h5>
            <div class="bar"></div>
          </div>
        </div>
        <p class="paragraph">Last Projects</p>
        <div class="projects">
          <div>
            <img src="Screenshot 2021-10-13 034707.png" alt="" />
            <a href="https://karamlyy.github.io/restaurant/"
              >Karamlyy Restaurant</a>
          </div>
          <div>
            <img src="quiz app.jpeg" alt="" />
            <a href="https://karamlyy.github.io/quiz_app/"
              >Karamlyy Quiz App</a>
          </div>
          <div>
            <img src="auto.jpeg" alt="" />
            <a href="https://karamlyy.github.io/karamlyy_auto2/">Karamlyy Auto</a>
          </div>
          <div>
            <img src="social.jpeg" alt="" />
            <a href="https://karamlyy.github.io/karamlyy_social/">Karamlyy Social Media</a>
          </div>
          <div>
            <img src="saat.png" alt="" />
            <a href="https://karamlyy.github.io/flip_clock/"
              >Karamlyy Flip Clock</a>
          </div>
          <div>
            <img src="agecalc.png" alt="" />
            <a href="https://karamlyy.github.io/age_calculator/"
              >Karamlyy Age Calculator</a>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <p class="paragraph">&copy; 2021 - Designed by  <a href="https://karamlyy.github.io/profile/" target="_blank">Karam Afandi</a></p>
    </footer>
    <canvas class="webgl"></canvas>
    <script src="three.min.js"></script>
    <script src="webgl.js"></script>
    <script src="reveal.js"></script>
    <script src="navbar.js"></script>
    <script src="project.js"></script>
  </body>
</html>

