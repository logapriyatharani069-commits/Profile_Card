# Profile_Card
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Profile Card</title>

  <!-- Font Awesome (for icons) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      background: white;
      width: 320px;
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    .profile-img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #333;
      margin-bottom: 15px;
    }

    h2 {
      margin: 10px 0 5px;
    }

    h4 {
      color: gray;
      margin-bottom: 15px;
    }

    p {
      font-size: 14px;
      color: #444;
      line-height: 1.5;
    }

    .icons {
      margin-top: 15px;
    }

    .icons a {
      margin: 0 10px;
      font-size: 22px;
      color: #333;
      transition: 0.3s;
    }

    .icons a:hover {
      color: #0077b5; /* LinkedIn blue */
      transform: scale(1.2);
    }
  </style>
</head>

<body>

  <div class="card">

    <!-- 🔥 Your Photo -->
    <img src="c:\Users\logap\Pictures\Screenshots\Screenshot 2026-03-26 144611.png" class="profile-img">

    <h2>Loga Priya N</h2>
    <h4>AIML Student</h4>

    <p>
      I have logical thinking.<br>
      Passionate about web development & UI design.<br>
      I enjoy learning new skills.<br>
      Goal: Strong AI/ML career.
    </p>

    <!-- 🔥 Icons -->
    <div class="icons">

      <!-- LinkedIn -->
      <a href="https://www.linkedin.com/in/loga-priya-n-74a7b4377" target="_blank">
        <i class="fab fa-linkedin"></i>
      </a>

      <!-- GitHub -->
      <a href="https://github.com/logapriyatharani069-commits" target="_blank">
        <i class="fab fa-github"></i>
      </a>

    </div>

  </div>

</body>
</html>


 output
      https://logapriyatharani069-commits.github.io/Profile_Card/
