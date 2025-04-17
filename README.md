<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>デジタル名刺</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #f0f4f8, #d9e2ec);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 1.5rem;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      text-align: center;
      max-width: 320px;
      width: 90%;
    }

    .name {
      font-size: 1.8rem;
      font-weight: bold;
      color: #2c3e50;
    }

    .title {
      color: #555;
      margin-top: 0.5rem;
    }

    .email {
      margin-top: 1rem;
      color: #3498db;
      text-decoration: none;
    }

    .email:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="name">山田 太郎</div>
    <div class="title">フルスタックエンジニア @ Yamada Inc.</div>
    <a class="email" href="mailto:taro@example.com">taro@example.com</a>
  </div>
</body>
</html>
