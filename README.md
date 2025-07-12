<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('placeholder-image.jpg') no-repeat center center/cover;
      color: #fff;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.4);
    }

    .container {
      position: relative;
      z-index: 2;
      max-width: 800px;
      padding: 20px;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      height: 40px;
      margin-right: 10px;
    }

    h1 {
      font-size: 48px;
      color: #FFC300;
      margin: 20px 0 10px;
    }

    p {
      font-size: 18px;
      max-width: 500px;
    }

    .donate-btn {
      background: #FFC300;
      color: #000;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 20px;
    }

    .input-group {
      margin-top: 30px;
      display: flex;
      align-items: center;
    }

    .input-group input {
      padding: 15px;
      font-size: 16px;
      border: none;
      border-radius: 5px 0 0 5px;
      width: 200px;
    }

    .input-group button {
      padding: 15px 30px;
      background: #FFC300;
      border: none;
      color: #000;
      font-size: 16px;
      cursor: pointer;
      border-radius: 0 5px 5px 0;
    }

    .donations {
      background: #FFC300;
      color: #000;
      padding: 20px;
      border-radius: 10px;
      margin-top: 30px;
      max-width: 300px;
    }

    .donations h3 {
      margin: 0 0 10px;
    }

    .donation-item {
      display: flex;
      justify-content: space-between;
      margin-bottom: 5px;
    }

    .total-raised {
      position: absolute;
      bottom: 40px;
      right: 40px;
      background: #FFC300;
      color: #000;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="container">
    <div class="logo">
      <img src="logo-placeholder.png" alt="Charity: Water Logo" />
      <h2>Charity:Water</h2>
    </div>
    <h1>Change Starts with You. And Clean Water.</h1>
    <p>10% of the human population lacks access to clean water. Save lives by donating today.</p>
    <button class="donate-btn">Donate</button>

    <div class="input-group">
      <input type="text" placeholder="I'm Thirsty" />
      <button>Donate</button>
    </div>

    <div class="donations">
      <h3>Donations Today</h3>
      <div class="donation-item">
        <span>Clean Water</span>
        <span>$20</span>
      </div>
      <div class="donation-item">
        <span>Clean Water</span>
        <span>$10</span>
      </div>
      <div class="donation-item">
        <span>Clean Water</span>
        <span>$40</span>
      </div>
    </div>
  </div>

  <div class="total-raised">
    <strong>Clean Water</strong><br />
    TOTAL RAISED<br />
    <span>$480,378</span>
  </div>
</body>
</html>
