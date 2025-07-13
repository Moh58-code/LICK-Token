<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>$LICK Token | Born to Lick, Built to Pump</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #0ed3cf;
      margin: 0;
      padding: 0;
      color: #fff;
      overflow: hidden;
    }
    .dollar {
      position: absolute;
      top: -100px;
      font-size: 30px;
      animation: fall linear infinite;
      color: #00ff99;
      opacity: 0.5;
    }
    @keyframes fall {
      to {
        transform: translateY(120vh);
      }
    }
    .container {
      padding: 50px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1;
      position: relative;
    }
    .hero {
      max-width: 600px;
      text-align: left;
    }
    img {
      width: 350px;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
    }
    h1 {
      font-size: 48px;
      margin: 30px 0 10px;
    }
    h2 {
      font-size: 24px;
      color: #ffd700;
      margin-bottom: 30px;
    }
    p {
      font-size: 18px;
      line-height: 1.6;
      max-width: 600px;
    }
    .contract {
      background: #fff;
      color: #000;
      padding: 15px;
      display: inline-block;
      border-radius: 10px;
      font-weight: bold;
      margin-top: 20px;
    }
    .footer {
      margin-top: 50px;
      font-size: 14px;
      color: #ccc;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- falling dollars -->
  <script>
    const dollarCount = 50;
    for (let i = 0; i < dollarCount; i++) {
      const dollar = document.createElement('div');
      dollar.className = 'dollar';
      dollar.style.left = Math.random() * 100 + 'vw';
      dollar.style.animationDuration = (Math.random() * 5 + 3) + 's';
      dollar.innerHTML = '$';
      document.body.appendChild(dollar);
    }
  </script>
  
  <div class="container">
    <div class="hero">
      <h1>$LICK Token</h1>
      <h2>Born to Lick. Built to Pump. 💦</h2>
      <p>
        Meet $LICK — the wildest meme coin in town. It doesn't just dip, it drools.<br>
        A mischievous dog with a golden crown, a fat tongue, and an even fatter ambition.<br>
        $LICK is more than a token — it's a movement of degenerates licking their way to the top 🚀.<br><br>
        0% taxes. 100% chaos. Backed by memes. Fueled by the community. Powered by hype.<br>
        Are you in, or just another dog in the background?
      </p>
      <div class="contract">
        CA (Contract Address): [Your Contract Address Here]
      </div>
    </div>
    <img src="/mnt/data/A_2D_digital_illustration_features_a_cartoon_brown.png" alt="$LICK Dog Image">
  </div>
  <div class="footer">
    &copy; 2025 $LICK Token. All licks reserved.
  </div>
</body>
</html>

