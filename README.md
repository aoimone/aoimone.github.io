<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>〇〇公式サイト</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Google Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --main-color: #111;
      --accent-color: #0a3cff;
      --bg-color: #ffffff;
      --gray: #f5f5f5;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: "Noto Sans JP", sans-serif;
      background: var(--bg-color);
      color: var(--main-color);
      line-height: 1.8;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    /* ---------- Header ---------- */
    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(255,255,255,0.95);
      border-bottom: 1px solid #eaeaea;
      z-index: 100;
    }

    .header-inner {
      max-width: 1200px;
      margin: auto;
      padding: 16px 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-weight: 700;
      font-size: 18px;
    }

    nav a {
      margin-left: 24px;
      font-size: 14px;
    }

    /* ---------- Hero ---------- */
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 16px;
      letter-spacing: 0.05em;
    }

    .hero p {
      font-size: 18px;
      color: #555;
    }

    /* ---------- Section ---------- */
    section {
      padding: 120px 20px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 28px;
      margin-bottom: 32px;
      position: relative;
    }

    h2::after {
      content: "";
      display: block;
      width: 40px;
      height: 3px;
      background: var(--accent-color);
      margin-top: 12px;
    }

    .text {
      font-size: 16px;
      color: #444;
    }

    /* ---------- Card ---------- */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 32px;
      margin-top: 40px;
    }

    .card {
      background: var(--gray);
      padding: 32px;
      border-radius: 8px;
    }

    .card h3 {
      margin-top: 0;
      font-size: 18px;
    }

    /* ---------- Footer ---------- */
    footer {
      background: #111;
      color: #ccc;
      padding: 60px 20px;
      font-size: 14px;
    }

    footer .container {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    footer p {
      margin: 0;
    }

    /* ---------- Responsive ---------- */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 30px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="logo">〇〇公式サイト</div>
    <nav>
      <a href="#about">ABOUT</a>
      <a href="#service">SERVICE</a>
      <a href="#contact">CONTACT</a>
    </nav>
  </div>
</header>

<main>
  <!-- Hero -->
  <div class="hero">
    <div>
      <h1>未来をつくる、<br>〇〇の挑戦</h1>
      <p>〇〇は、新しい価値を生み出し続けます。</p>
    </div>
  </div>

  <!-- About -->
  <section id="about">
    <div class="container">
      <h2>ABOUT</h2>
      <p class="text">
        〇〇は、◯◯分野を中心に活動する団体・企業です。<br>
        私たちは「◯◯◯◯」を理念に、日々取り組んでいます。
      </p>
    </div>
  </section>

  <!-- Service -->
  <section id="service">
    <div class="container">
      <h2>SERVICE</h2>

      <div class="cards">
        <div class="card">
          <h3>事業内容01</h3>
          <p class="text">
            サービスや活動内容の説明が入ります。
          </p>
        </div>

        <div class="card">
          <h3>事業内容02</h3>
          <p class="text">
            サービスや活動内容の説明が入ります。
          </p>
        </div>

        <div class="card">
          <h3>事業内容03</h3>
          <p class="text">
            サービスや活動内容の説明が入ります。
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <div class="container">
      <h2>CONTACT</h2>
      <p class="text">
        お問い合わせは下記メールアドレスまでお願いいたします。
      </p>
      <p class="text">
        📩 example@example.com
      </p>
    </div>
  </section>
</main>

<footer>
  <div class="container">
    <p>〇〇株式会社 / 〇〇団体</p>
    <p>© 2026 〇〇. All Rights Reserved.</p>
  </div>
</footer>

</body>
</html>
