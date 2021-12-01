<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | NFT preview card component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    body{
    display: grid;
    border: 20px solid gray;
    margin: auto;
    padding: 0.5em;
    width: 400px;
    height: 650px;
    background-color: hsl(217, 54%, 11%);
    font-size: 18px;
    font-family: sans-serif;
  }
  </style>
</head>
<body>
<div class="img" id="one"style="text-align: center; "><img src="image-equilibrium.jpg" width="300" height="300" alt=""></div>
  <p style="color: hsl(0, 0%, 100%)">Equilibrium #3429</p>

  <p style="color: gray;">Our Equilibrium collection promotes balance and calm.</p>

   <div style="width: 100%;">
    <div style="width: 50%; height: 100px; color: hsl(178, 100%, 50%); float:left;">0.041 ETH </div>
    <div style="margin-left: 50%; height: 100px; color: gray;"><img src="icon-clock.svg" alt=""> 3 days left</div><hr>
   </div>
  <div style="width: 100%;">
  <p style="color: gray;"><img style="width: 30px; height: 30px;" src="image-avatar.png" alt=""> Creation of <span style="color: white;">Jules Wyvern</span> </p>
  </div>
  <div class="attribution">
    <span style="color: darkgray;">Challenge by</span><a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Sameh</a>.
  </div>
</body>
</html>
