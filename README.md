<!DOCTYPE html>
<html>
<head>
  <title >My Website: Viet Tri Ong</title>
  <meta charset="utf-8">
  <link rel="stylesheet" href="assets/css/main.css"/>
  <noscript><link rel="stylesheet" href="assets/css/main.css"></noscript>

  <style>
    h1{
        text-align: center;
        color: white;
        padding-bottom: 10px; 
        padding-top:25px;
    }
    p{
        text-align: center;
        color: white;
    }
    body{
      background-color: white;
    }
    .div1{
      background-color: #5D7B6F;
      margin: 0;
      padding: 0;
    }
    .div2{
      background-color: #A4C3A2;
      margin: 0;
      padding: 0;
    }
    .div3{
      /* background-color: #EAE7D6; */
      background-color: #B0D4B8;
      margin: 10;
      padding: 10;
    }
    #nav {
      background-color: #B0D4B8;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
    }

    #nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
    }

    #nav ul li {
      margin-right: 20px;
    }

    #nav ul li:last-child {
      margin-right: 0;
    }

    #nav a {
      text-decoration: none;
      color: #5D7B6F;
      font-weight: bold;
      font-size: 16px;
    }

    #nav a.active {
      font-weight: bold;
    }

    .icon {
      margin-right: 5px;
    }

    .fullscreen-img {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      object-fit: cover;
      z-index: -1; /* Send the image behind other content */
    }
    .container {
        background-color: #B0D4B8;
        box-shadow: 5px 5px 5px #5D7B6F;
        border-radius: 10px;
        font-family: Arial;
        font-size: 14px;
        text-align: left;
        margin-right: 40px;
        margin-left: 40px;
      }
  </style>

</head>
<body>
<!-- Header to introduce -->
<div class="div1">
  <h1 style="font-size: 15px;">Linkn: Viet Tri Ong - Ingtagram: im.brian_  <br /></h1>

    <div class="div2">
      <h1 >Viet Tri Ong - Brian Ong<br />
          Portfolio</h1>
          <p style="padding-bottom: 25px;">Student in Computer Science (Artificial Intellegence and Big Data)
    
            <nav id="nav">
              <ul class="links">
                <li class="active"><a href="Page1.html">Home</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="resume.html">Resume</a></li>
              </ul>
              <ul class="icons">
                <li><a href="https://www.facebook.com/swiitt2703" class="icon brands fa-facebook"><span class="label">Facebook</span></a></li>
                <li><a href="https://www.linkedin.com/in/viet-tri-ong-198392172" class="icon brands fa-twitter"><span class="label">Linkedln</span></a></li>
                <li><a href="#" class="icon brands fa-instagram"><span class="label">Email</span></a></li>
              </ul>
            </nav>
    </div>

    
</div>


<div>
  <h1 class="metal-text">Welcome to My Website <br /></h1>
  <div class="div3 container" >
    <h1 class="metal-text">My Background <br /></h1>
    <p>" ">
  </div>
  <img class="fullscreen-img" src="./Images/conifers-1867371.jpg">
</div>
</body>
</html>
