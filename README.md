# uaibeka
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>UAIBEKA — u Айбека</title>
  <style>
    body {
      margin: 0;
      background: #0a0a0a;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      overflow-x: hidden;
    }

    header {
      background: #111;
      padding: 40px 20px;
      text-align: center;
      border-bottom: 1px solid #333;
      animation: fadeIn 1.2s ease-in-out;
    }

    h1 {
      font-size: 48px;
      margin: 0;
      color: #00fff7;
      letter-spacing: 2px;
      transform: scale(1);
      animation: jelly 2s ease-in-out;
    }

    p.slogan {
      margin-top: 10px;
      color: #aaa;
      font-size: 18px;
      animation: fadeIn 2s ease-in;
    }

    .item {
      padding: 30px 20px;
      border-bottom: 1px solid #222;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlide 1s ease forwards;
    }

    .item:nth-child(even) { animation-delay: 0.3s; }
    .item:nth-child(odd) { animation-delay: 0.6s; }

    .item h2 {
      color: #00fff7;
      margin-bottom: 10px;
    }

    .item p {
      color: #ccc;
      font-size: 16px;
    }

    .socials {
      margin-top: 30px;
    }

    .socials a {
      margin: 0 10px;
      display: inline-block;
      color: white;
      text-decoration: none;
      font-size: 24px;
      transition: transform 0.3s ease;
    }

    .socials a:hover {
      transform: scale(1.1);
      color: #00fff7;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #666;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }

    @keyframes fadeSlide {
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes jelly {
      0% { transform: scale(1); }
      25% { transform: scale(1.05, 0.95); }
      50% { transform: scale(0.95, 1.05); }
      75% { transform: scale(1.02, 0.98); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>

<header>
  <h1>UAIBEKA</h1>
  <p class="slogan">Мой стиль. Мои вещи. Мой мир.</p>

  <div class="socials">
    <a href="https://www.instagram.com/a1qwns?igsh=cDB1dW5pZDFmbmFr" target="_blank">📸</a>
    <a href="https://t.me/aibek0555" target="_blank">💬</a>
    <a href="https://www.tiktok.com/" target="_blank">🎵</a>
  </div>
</header>

<section class="item">
  <h2>📱 iPhone 11 — Сиреневый</h2>
  <p>128 ГБ, аккумулятор 72%. Всегда со мной, как правая рука.</p>
</section>

<section class="item">
  <h2>🎧 JBL 520BT</h2>
  <p>Чёрные наушники. Идеальны для фонка в зале и улицы в стиле.</p>
</section>

<section class="item">
  <h2>🕶️ Очки</h2>
  <p>Чёрные линзы. Зрение: -1 и -0.75. Вижу чётко, как цели в жизни.</p>
</section>

<section class="item">
  <h2>🧦 Носки Nike</h2>
  <p>Белые, длинные. Символ минимализма и движения.</p>
</section>

<section class="item">
  <h2>🧴 Парфюмы</h2>
  <p>
    Jean Paul Gaultier Le Male Elixir — сладкий, дерзкий.<br>
    Maison Margiela Replica Jazz Club — тёплый, как уверенность.
  </p>
</section>

<section class="item">
  <h2>👕 Манчестер Сити</h2>
  <p>Бордовая футболка. Любовь к клубу и дух победителя.</p>
</section>

<section class="item">
  <h2>⌚ Браслет AMBUSH</h2>
  <p>В стиле часов. Не просто аксессуар — символ вкуса и индивидуальности.</p>
</section>

<footer>
  © 2025 UAIBEKA. Всё, что у Айбека — со вкусом.
</footer>

</body>
</html>
