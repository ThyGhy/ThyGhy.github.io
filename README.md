<html>
  <head>
    <title>Thy_Ghy</title>
    <style>
      body {
        background-image: linear-gradient(90deg, 
          black, 
          grey, 
          grey, 
          grey, 
          black
        );
        background-size: 100% 100px;
        background-repeat: repeat-y;
        animation: animateBackground 20s linear infinite;
        text-align: center;
        padding: 0;
      }
      @keyframes animateBackground {
        0% {
          background-position: 0% 0%;
        }
        100% {
          background-position: 0% 100%;
        }
      }
      .navbar {
        background-color: #333333;
        border-radius: 10px;
        padding: 20px;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3), 
                    -5px -5px 10px rgba(255, 255, 255, 0.3);
        width: 100%;
        position: absolute;
        top: 0;
        left: 0;
      }
      .navbar a {
        font-size: 20px;
        color: white;
        font-weight: normal;
        text-shadow: 0 0 5px darkgrey, 0 0 10px darkgrey, 0 0 15px darkgrey;
        text-decoration: none;
        margin-right: 20px;
      }
      .centerblock {
        background-color: #333333;
        border-radius: 10px;
        padding: 20px;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3), 
                    -5px -5px 10px rgba(255, 255, 255, 0.3);
        display: inline-block;
        transform: translate(0, -5px);
        width: auto;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
      h1 {
        font-size: 50px;
        color: white;
        text-shadow: 0 0 5px darkgrey, 0 0 10px darkgrey, 0 0 15px darkgrey;
      }
      h2 {
        font-size: 30px;
        color: white;
        font-weight: normal;
        text-shadow: 0 0 5px darkgrey, 0 0 10px darkgrey, 0 0 15px darkgrey;
      }
      h3 {
        font-size: 20px;
        color: white;
        font-weight: normal;
        text-shadow: 0 0 5px darkgrey, 0 0 10px darkgrey, 0 0 15px darkgrey;
      }
    </style>
  </head>
  <body>
    <div class="navbar">
      <a href="https://thy-ghy.itch.io/">My Itch.io</a>
      <a href="#">About Me</a>
      <a href="#">Twitter</a>
    </div>
    <div class="centerblock">
<h1>Thy_Ghy</h1>
<h2>Game Developer and Designer</h2>
<h3>Welcome to my portfolio website</h3>
</div>
  </body>
</html>
