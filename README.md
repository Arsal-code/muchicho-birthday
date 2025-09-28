<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Muchicho ❤️</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      color: #fff;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
    }

    p {
      font-size: 1.5em;
      margin-bottom: 1em;
    }

    .heart {
      font-size: 4em;
      animation: beat 1s infinite;
    }

    @keyframes beat {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.3);
      }
    }

    .btn {
      padding: 10px 20px;
      font-size: 1em;
      background: #fff;
      color: #ff6f91;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #ffe2e6;
    }

    .message {
      display: none;
      margin-top: 1.5em;
      font-size: 1.3em;
      color: #fff;
    }
  </style>
</head>
<body>

  <h1>Happy Birthday, Muchicho! 🎂</h1>
  <p>You make the world brighter just by being in it.</p>
  <div class="heart">❤️</div>

  <button class="btn" onclick="showMessage()">Click for a Surprise 🎁</button>

  <div class="message" id="surpriseMessage">
    Dear Muchicho,<br><br>
    YK HOW MUCH U MEAN TO ME AND I GOT INTO LIL VOIDS AND STUFF LEKIN IT DOESNT
     MEAN K I DONT THINK ABT U U ARE THE BEST PERSON IN MY LIFE
     AND U WERE ASKING ABT UR SURPRISE AS I CANT GET U PHYSICAL STUFF THAT FAR SO I MADE U A LIL WEBSITE FOR U
     I HOPE U LIKE IT THO. 💖<br>
    Thank you for being you. Let's make this birthday as beautiful as your smile!<br><br>
    Love you always! ❤️
  </div>

  <script>
    function showMessage() {
      document.getElementById("surpriseMessage").style.display = "block";
    }
  </script>
  
</body>
</html>
