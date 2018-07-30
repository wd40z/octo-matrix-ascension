<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>JS + CSS Clock</title>
</head>
<body>


    <div class="clock">
      <div class="clock-face">
        <div class="handA hour-hand"></div>
        <div class="handB min-hand"></div>
        <div class="handC second-hand"></div>
      </div>
    </div>


  <style>
    html {
      createCanvas(800,800);
      font-family:'helvetica neue';
      text-align: center;
      font-size: 10px;
    }

    body {
      margin: 0;
      font-size: 2rem;
      display:flex;
      flex:1;
      min-height: 100vh;
      align-items: center;
    }

    .clock {
      width: 50rem;
      height: 50rem;
      border:20px solid rgb(213, 125, 9);
      border-radius:50%;
      margin:50px auto;
      position: relative;
      padding:2rem;
      box-shadow:
        0 0 0 4px rgba(0,0,0,0.1),
        inset 0 0 0 3px #EFEFEF,
        inset 0 0 10px black,
        0 0 10px rgba(0,0,0,0.2);
    }

    .clock-face {
      position: relative;
      width: 100%;
      height: 100%;
      transform: translateY(-3px); /* account for the height of the clock hands */
    }

    .handA {
      width:50%;
      height:6px;
      background:black;
      position: absolute;
      top:50%;
      transform-origin: 100%;
      transform: rotate(360deg);
      transition: :active  all 90.5s;

      function setDate() {
          const now = new Date();

          const seconds = now.getSeconds();
          const secondsDegrees = ((seconds / 60) * 360) + 90;
          secondHand.style.transform = `rotate(${secondsDegrees}deg)`;
    }

    .handB {
      width:50%;
      height:6px;
      background:black;
      position: absolute;
      top:50%;
      transform-origin: 100%;
      transform: rotate(33deg);
      transition: all 40.5s;
      transition-duration: 33s
    
    }

    .handC {
      width:50%;
      height:6px;
      background:black;
      position: absolute;
      top:50%;
      transform-origin: 100%;
      transform: rotate(-90deg);
      transition: all 33.5s;
      transition-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1)
    }

  </style>

  <script>


  </script>
</body>
</html>
