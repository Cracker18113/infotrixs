# infotrixs first task Here is the link of the static portfolio website hosted in Amazon https://infotrixs1.s3.ap-south-1.amazonaws.com/sriram+portfoloio.html
![image](https://github.com/Cracker18113/infotrixs/assets/112747067/0e5baab4-c389-48c9-9435-4780402f26b5)
<html lang="en">
<head>
<link rel="stylesheet" href="portfolio.css">
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="author" content="Sanket Bodake">
  <meta name="description" content="Portfolio website | Web Developer | Open source Enthusiast">
  <meta name="keywords" content="Sanket, bodake, Sanket bodake, portfolio, css, javascript, software, coding, programming, web, 
  development, developer, frontend">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="google-site-verification" content="IZ7Sm227j_9N0Sy_JmwOvn1_OAm_O2rHr2833ZV0Fro">
  <title>Sriram Padala</title>
  <link rel="stylesheet" href="./style.css" />
  <script src="https://kit.fontawesome.com/66aa7c98b3.js" crossorigin="anonymous"></script>
  <link href="https://fonts.googleapis.com/css?family=Comfortaa:400,700,300|Quattrocento" rel="stylesheet">
  <link rel="shortcut icon" href="./img/fbavatar_1630400663387_6838396024049256103.png" type="image/x-icon">
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"
  integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
 <meta name="title" content="Portfolio Website | Sanket Bodake">
 <meta name="title" content="Portfolio Website | Sanket Bodake">
 <meta itemprop="description" content="Web Developer | Open source Enthusiast">
 <meta name="application-name" content="Portfolio Website">
 <meta property="og:site_name" content="">
 <meta property="og:type" content="website">
 <meta property="og:url" content="https://sanketbodake.ninja/">
 <meta property="og:title" content="Sriram Padala">
 <meta property="og:description" content="Portfolio website | Web Developer | Open source Enthusiast">
 <meta name="url" content="https://sanketbodake.ninja/">
 <meta name="language" content="English">  
 <meta property="twitter:card" content="summary_large_image">
<meta name="twitter:url" content="https://sanketbodake.ninja/">
<meta name="twitter:title" content="Sriram Padala">
<meta name="twitter:description" content="Portfolio website | Web Developer | Open source Enthusiast">
<meta name="twitter:site" content="@Sanket46171296">
<meta name="twitter:creator" content="@Sanket46171296">
<meta name="url" content="https://sanketbodake.ninja/">
<meta property="og:locale" content="en">
<meta name="language" content="English">
<meta itemprop="image" content="https://sanketbodake.ninja/myImage.jpg">
<meta property="og:image" content="https://sanketbodake.ninja/myImage.jpg">
<meta name="twitter:image" content="https://sanketbodake.ninja/myImage.jpg">
<meta name="twitter:image:src" content="https://sanketbodake.ninja/myImage.jpg">
<meta property="og:image:type" content="image/png">
<meta property="og:image:width" content="512">
<meta property="og:image:height" content="512">
<meta property="twitter:image:type" content="image/png">
<meta property="twitter:image:width" content="512">
<meta property="twitter:image:width" content="512">
</head>

#css code

@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
}

header {
  background-color: #25b79f;
  height: 100vh;
}

.container {
  max-width: 1200px;
  width: 90%;
  margin: auto;
}

/* ////........Navbar.......//// */

.navbar {
  position: fixed;
  width: 100%;
  z-index: 500;
}

.navbar-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 64px;
}

.menu-items {
  display: flex;
}

.menu-items li {
  list-style: none;
  padding: 1rem;
}

.menu-items a {
  text-decoration: none;
  color: #f0f0e6;
  font-size: 1.2rem;
  padding: 0.3rem;
}

.menu-items a:hover {
  border-bottom: 2px solid #f0f0e6;
}

.navbar .logo {
  order: 1;
  color: #f0f0e6;
  font-size: 2rem;
}

/* ////........Home Content........//// */

.home-content .name {
  position: absolute;
  top: 47%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #07374a;
  width: 100%;
  text-align: center;
}

.home-content .name h1 {
  font-size: 2.2rem;
  text-align: center;
}

.home-content .name p {
  color: #f0f0e6;
  font-size: 1.5rem;
}

.angle-down-icon {
  position: absolute;
  bottom: 10%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 2rem;
  border: 3px solid #07374a;
  border-radius: 50%;
}

.angle-down-icon a {
  text-decoration: none;
  color: #07374a;
  padding: 1rem;
}

/* ////........About Me........//// */

.about-me {
  background-color: #07374a;
  padding: 6rem 0;
}

.about-me .about-heading {
  color: #25b79f;
  font-size: 2rem;
  font-weight: 600;
  text-align: center;
}

.about-content img {
  height: 200px;
  width: 150px;
  object-fit: cover;
  border-radius: 50%;
}

.about-content p {
  font-size: 1.2rem;
  color: #f0f0e6;
  padding: 0 2.3rem;
  text-align: center;
}

.skills .skills-heading {
  font-size: 2rem;
  font-weight: 600;
  color: #25b79f;
  text-align: center;
}

.about-me .about-content {
  display: flex;
  flex-wrap: wrap;
}

.about-content .left-content {
  flex-basis: 45%;
  text-align: center;
}

.about-content .right-content {
  flex-basis: 45%;
}

/* ///.....Skill Bar....../// */

.skills-bar {
  padding: 25px 30px;
}

.skills-bar .bar {
  margin: 25px 0;
}

.skills-bar .bar .info span {
  font-size: 1rem;
  font-weight: 500;
}

.skills-bar .bar .info {
  margin-bottom: 8px;
  color: #f0f0e6;
}

.skills-bar .bar .progress-line {
  position: relative;
  height: 10px;
  width: 550px;
  background: #f0f0f0;
  border-radius: 10px;
  transform: scaleX(0);
  transform-origin: left;
  animation: animate 1s cubic-bezier(1, 0, 0.5, 1) forwards;
}

.bar .progress-line span {
  position: absolute;
  background: #25b79f;
  height: 100%;
  border-radius: 10px;
  transform: scaleX(0);
  transform-origin: left;
  animation: animate 1s 1s cubic-bezier(1, 0, 0.5, 1) forwards;
}

@keyframes animate {
  100% {
    transform: scaleX(1);
  }
}

.progress-line .html {
  width: 80%;
}
.progress-line .css {
  width: 70%;
}
.progress-line .bootstrap {
  width: 50%;
}
.progress-line .javascript {
  width: 50%;
}
.progress-line .c {
  width: 50%;
}

.bar .progress-line span::before {
  position: absolute;
  content: "";
  height: 0;
  right: 0;
  top: -12px;
  width: 0;
  border: 7px solid transparent;
  border-bottom-width: 0px;
  border-right-width: 0px;
  border-top-style: #f0f0f0;
  border-top-color: #f0f0f0;
}

.bar .progress-line span::after {
  position: absolute;
  right: 0;
  top: -28px;
  color: #07374a;
  font-size: 12px;
  font-weight: 700;
  background: #f0f0f0;
  padding: 1px 8px;
  border-radius: 3px;
}

.progress-line .html::after {
  content: "80%";
}
.progress-line .css::after {
  content: "70%";
}
.progress-line .bootstrap::after {
  content: "50%";
}
.progress-line .javascript::after {
  content: "50%";
}
.progress-line .c::after {
  content: "50%";
}

.navbar.solid {
  background-color: #07374a;
  transition: background-color 1s ease 0s;
  box-shadow: 0 0 4px rgb(7 55 74 / 20%);
  z-index: 500;
}

.navbar.solid .navbar-brand {
  display: inline-block;
  color: #f0f0e6;
  transition: color 1s ease 0s;
}

.navbar-brand {
  display: none;
  color: #f0f0e6;
  font-weight: 400;
}

.work-arrow {
  margin: 2rem 0;
}

.work-arrow a {
  font-size: 1rem;
  text-decoration: none;
  color: #25b79f;
}

.work-arrow-2 {
  margin: 2rem 0;
}

.work-arrow-2 a {
  font-size: 1rem;
  text-decoration: none;
  color: #25b79f;
  display: none;
}

/* ////.....Portfolio......///// */

.portfolio {
  background: #25b79f;
  padding: 6rem 0;
}

.proj-heading h1{
  text-align: center;
  color: #07374a;
  font-size: 2.3rem;
  font-weight: 700;
  margin: 3rem 0;
  
}

.proj-1{
  display: flex;
  justify-content: center;
  align-items: center;
}

.proj-1 img{
  height: 370px;
  width: 500px;
  object-fit: cover;
  
  box-shadow: 0 20px 10px -10px rgb(37 41 52 / 31%);
  margin-right: 1.7rem;
}

.proj-1 .proj1-details{
  width: 32rem;
}

.proj-1 .proj1-details i{
  font-size: 1.5rem;
  color: #07374a;
}

.proj-1 .proj1-details h2{
  font-size: 2rem;
  color: #07374a;
}

.proj-1 .proj1-details p{
  font-size: 1.3rem;
  color: #07374a;
  font-weight: 600;
}

.proj-1 .proj1-details button{
  background: #f0f0e6;
  padding: 0.5rem;
  margin-top: 0.5rem;
  width: 150px;
  border: none;
  border-bottom: 2px solid #07374a;
}

.proj-1 .proj1-details button a{
  text-decoration: none; 
  color: #07374a;
  font-size: 1.1rem;
  transition: 0.2s ease-in-out;
  text-align: center;
  transition: 0.3s ease-in-out;
}

.proj-1 .proj1-details button .fas{
  font-size: 0.7rem;
  padding: 0.3rem;
  transition: 0.2s ease-in-out;
}

.proj-1 .proj1-details button:hover {
  background: #07374a;
}
  
.proj-1 .proj1-details button:hover a,
.proj-1 .proj1-details button:hover .fas {
  color: #f0f0e6;
}

/* ////.....proj2.....//// */

.proj-2{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 3rem;
}

.proj-2 img{
  height: 330px;
  width: 380px;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0 20px 10px -10px rgb(37 41 52 / 31%);
  margin-right: 1.7rem;
}

.proj-2 .proj2-details{
  width: 32rem;
}

.proj-2 .proj2-details i{
  font-size: 1.5rem;
  color: #07374a;
}

.proj-2 .proj2-details h2{
  font-size: 2rem;
  color: #07374a;
}

.proj-2 .proj2-details p{
  font-size: 1.3rem;
  color: #07374a;
  font-weight: 600;
}

.proj-2 .proj2-details button{
  background: #f0f0e6;
  padding: 0.5rem;
  margin-top: 0.5rem;
  width: 150px;
  border: none;
  border-bottom: 2px solid #07374a;
}

.proj-2 .proj2-details button a{
  text-decoration: none; 
  color: #07374a;
  font-size: 1.1rem;
  transition: 0.2s ease-in-out;
  text-align: center;
  transition: 0.3s ease-in-out;
}

.proj-2 .proj2-details button .fas{
  font-size: 0.7rem;
  padding: 0.3rem;
  transition: 0.2s ease-in-out;
}

.proj-2 .proj2-details button:hover {
  background: #07374a;
}
  
.proj-2 .proj2-details button:hover a,
.proj-2 .proj2-details button:hover .fas {
  color: #f0f0e6;
}

.more-work {
  text-align: center;
  margin: 3rem 0 1rem 0;
}

.more-work p {
  font-size: 1.6rem;
  color: #07374a;
  font-weight: 500;
}

.more-work a {
  text-decoration: none;
  color: #f0f0e6;
  font-size: 1.3rem;
}

.more-work a:hover {
  border-bottom: 2px solid #f0f0e6;
}

/* ////......Contact......///// */

.contact {
  background: #07374a;
  position: relative;
  height: 92vh;
}

.contact-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.contact-content h2 {
  font-size: 2.5rem;
  font-weight: 400;
  color: #25b79f;
  padding-bottom: 0.5rem;
}

.contact-content .mail {
  color: #f0f0e6;
  padding-bottom: 0.2rem;
  font-size: 1rem;
}

.contact-content .links {
  color: #25b79f;
  padding: 0.5rem;
  padding-bottom: 1.8rem;
  font-size: 1rem;
}

.contact-content a {
  text-decoration: none;
  color: #25b79f;
  padding: 0.5rem;
  transition: 0.3s ease-in-out;
}

.contact-content a:hover{
  color: #f0f0e6;
}

/* ////......Media query......//// */

@media (max-width: 500px) {
  html {
    font-size: 60%;
  }

  .about-content .left-content {
    flex-basis: 100%;
    text-align: center;
  }

  .about-content .right-content {
    flex-basis: 100%;
  }

  .skills {
    width: 100%;
  }

  .skills-bar .bar .progress-line {
    width: 100%;
  }

  .work-arrow {
    display: none;
  }

  .right-content h1 {
    margin-top: 3.2rem;
  }

  .proj-1{
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .proj-1 img {
    height: 230px;
    width: 290px;
    margin-bottom: 0.5rem;
  }
  
  .proj-2{
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .proj-2 img {
    height: 250px;
    width: 290px;
    margin-bottom: 0.5rem;
  }

  .work-arrow-2 a {
    font-size: 1.3rem;
    text-decoration: none;
    color: #25b79f;
    display: block;
    text-align: center;
  }

  .contact-content {
    width: 100%;
  }
}

@media (min-width: 501px) and (max-width: 768px) {
  html {
    font-size: 65%;
  }

  .about-content .left-content {
    flex-basis: 100%;
    text-align: center;
  }

  .about-content .right-content {
    flex-basis: 100%;
  }

  .skills {
    width: 100%;
  }

  .skills-bar .bar .progress-line {
    width: 100%;
  }

  .work-arrow {
    display: none;
  }

  .right-content h1 {
    margin-top: 3.2rem;
  }

  .proj-1{
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .proj-1 img {
    height: 240px;
    width: 290px;
    margin-bottom: 0.5rem;
  }
  
  .proj-2{
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .proj-2 img {
    height: 240px;
    width: 290px;
    margin-bottom: 0.5rem;
  }

  .work-arrow-2 a {
    font-size: 1.3rem;
    text-decoration: none;
    color: #25b79f;
    display: block;
    text-align: center;
  }

  .contact-content {
    width: 100%;
  }
}

@media (min-width: 769px) and (max-width: 1200px) {
  html {
    font-size: 70%;
  }

  .about-content .left-content {
    flex-basis: 100%;
    text-align: center;
  }

  .about-content .right-content {
    flex-basis: 100%;
  }

  .skills {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .work-arrow {
    display: none;
  }

  .left-content h1 {
    margin-top: 3.2rem;
    text-align: center;
  }

  .right-content h1 {
    margin-top: 3.2rem;
    text-align: center;
  }

  .work-arrow-2 a {
    font-size: 1.3rem;
    text-decoration: none;
    color: #25b79f;
    display: block;
    text-align: center;
  }

  .contact-content {
    width: 100%;
  }
}

@media (orientation: landscape) and (max-height: 500px) {
  .header {
    height: 90vmax;
  }
}


