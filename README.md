<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мой Linktree</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #ffffff, #000000);
      color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
      border: 3px solid white;
      object-fit: cover;
    }
    h1 {
      margin: 0;
      font-size: 28px;
    }
    p {
      margin: 5px 0 20px;
      font-size: 16px;
      opacity: 0.9;
    }
    .link {
      display: block;
      width: 220px;
      margin: 10px auto;
      padding: 12px;
      background: white;
      color: black;
      text-decoration: none;
      font-weight: bold;
      border-radius: 12px;
      transition: transform 0.2s, background 0.2s;
    }
    .link:hover {
      background: #f0f0f0;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <!-- Аватарка -->
  <img src="avatar.png" alt="Profile" class="profile-img">
  
  <!-- Имя и описание -->
  <h1>Exxspiravit</h1>
  <p>✨ Добро пожаловать в мой подвал ✨</p>

  <!-- Ссылки -->
  <a href="https://t.me/podval_prizraka" class="link" target="_blank">Telegram</a>
  <a href="https://www.instagram.com/exxspiravit?igsh=bzRvdTNpM3JzdTZt" class="link" target="_blank">Instagram</a>
  <a href="https://tiktok.com/@exxspiravit" class="link" target="_blank">TikTok</a>
</body>
</html>
