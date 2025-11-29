
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>امین رستمی — طراح سایت و دوبلور نیمه‌حرفه‌ای</title>

  <!-- SEO meta -->
  <meta name="description" content="امین رستمی — طراح سایت و دوبلور نیمه‌حرفه‌ای. طراحی صفحات HTML/CSS/JS زیبا، مشاوره طراحی سایت، و خدمات دوبلاژ. تماس: @ajabros" />
  <meta name="keywords" content="امین رستمی, طراحی سایت, طراح سایت, دوبلور, دوبلاژ, HTML, CSS, JavaScript, مشاوره سایت" />
  <meta name="author" content="امین رستمی" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="https://your-domain-or-github.io/" />

  <!-- Open Graph / social -->
  <meta property="og:title" content="امین رستمی — طراح سایت و دوبلور" />
  <meta property="og:description" content="طراحی سایت حرفه‌ای و دوبلاژ؛ مشاوره و پروژه‌های جذاب. تماس: @ajabros" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://your-domain-or-github.io/" />
  <!-- اگر یک تصویر دارید اینجا قرار بدید -->
  <!-- <meta property="og:image" content="https://your-domain-or-github.io/og-image.jpg" /> -->

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="امین رستمی — طراح سایت و دوبلور" />
  <meta name="twitter:description" content="طراحی سایت حرفه‌ای و دوبلاژ؛ مشاوره و پروژه‌های جذاب. تماس: @ajabros" />

  <!-- Structured data (Person) برای کمک به گوگل -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "امین رستمی",
    "jobTitle": "طراح سایت و دوبلور",
    "url": "https://your-domain-or-github.io/",
    "sameAs": [
      "https://t.me/ajabros"
    ],
    "description": "امین رستمی — طراح سایت (HTML/CSS/JS) و دوبلور نیمه‌حرفه‌ای. ارائه خدمات طراحی سایت و دوبلاژ."
  }
  </script>

  <!-- ساده اما دلنشین: فونت و استایل -->
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg1: linear-gradient(135deg,#ffecd2 0%,#fcb69f 50%, #ffd1ff 100%);
      --accent: #ff3b6b;
      --accent2: #4de0c1;
      --card: rgba(255,255,255,0.9);
      --glass: rgba(255,255,255,0.6);
      --text: #111;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:'Vazirmatn', Arial, sans-serif;
      background: var(--bg1);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      overflow-x:hidden;
    }

    /* header */
    header{
      padding:30px 18px;
      text-align:center;
      position:relative;
    }
    .brand{
      display:flex;
      align-items:center;
      justify-content:center;
      gap:14px;
      flex-wrap:wrap;
    }
    .logo{
      width:86px;height:86px;
      border-radius:18px;
      background:linear-gradient(135deg,var(--accent),var(--accent2));
      display:flex;align-items:center;justify-content:center;
      color:white;font-weight:700;font-size:28px;
      box-shadow:0 12px 30px rgba(0,0,0,0.12);
      transform:rotate(-6deg);
    }
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:#4b4b4b}

    /* floating stickers */
    .stickers{
      position:absolute;left:10px;top:10px;
      display:flex;gap:10px;flex-direction:column;
      pointer-events:none;
    }
    .sticker{
      width:56px;height:56px;border-radius:14px;
      display:flex;align-items:center;justify-content:center;
      background:rgba(255,255,255,0.85);
      box-shadow:0 8px 18px rgba(0,0,0,0.08);
      animation:float 4s ease-in-out infinite;
      font-size:26px;
    }
    .sticker:nth-child(2){animation-delay:0.6s}
    .sticker:nth-child(3){animation-delay:1.2s}

    @keyframes float{
      0%{transform:translateY(0) rotate(0)}
      50%{transform:translateY(-12px) rotate(6deg)}
      100%{transform:translateY(0) rotate(0)}
    }

    main{max-width:1100px;margin:20px auto;padding:12px}.hero{
      display:grid;grid-template-columns:1fr 380px;gap:20px;align-items:center;
      margin-bottom:18px;
    }
    /* card */
    .card{
      background:var(--card);
      border-radius:16px;padding:18px;box-shadow:0 10px 30px rgba(0,0,0,0.07);
      backdrop-filter: blur(6px);
    }
    .intro h2{margin:0 0 6px;font-size:22px;color:var(--accent)}
    .intro p{margin:0 0 8px;color:#333;line-height:1.6}

    /* badges */
    .badges{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
    .badge{background:linear-gradient(90deg,#fff 0%, rgba(255,255,255,0.8) 100%);padding:8px 12px;border-radius:999px;font-weight:700;box-shadow:0 6px 18px rgba(0,0,0,0.06)}
    .cta{display:inline-block;margin-top:12px;padding:10px 14px;border-radius:10px;background:var(--accent);color:white;text-decoration:none;font-weight:700;box-shadow:0 8px 20px rgba(255,59,107,0.18)}

    /* right column: avatar + gifs */
    .profile{
      display:flex;flex-direction:column;gap:12px;align-items:center;
    }
    .avatar{
      width:160px;height:160px;border-radius:20px;overflow:hidden;
      border:6px solid rgba(255,255,255,0.8);
      box-shadow:0 18px 40px rgba(0,0,0,0.12);
      background:linear-gradient(135deg,#fff,#f7f7f7);
      display:flex;align-items:center;justify-content:center;font-weight:800;font-size:40px;color:var(--accent);
    }
    .small-note{font-size:13px;color:#555}

    /* animated GIF-like using CSS (looping frames via transform) */
    .gif-row{display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
    .mini-gif{
      width:84px;height:84px;border-radius:12px;background:linear-gradient(135deg,#fff,#fff9);display:flex;align-items:center;justify-content:center;
      box-shadow:0 8px 18px rgba(0,0,0,0.06);position:relative;overflow:hidden;
    }
    .mini-gif .emoji{font-size:36px;animation:pop 3s infinite}
    @keyframes pop{0%{transform:scale(1)}50%{transform:scale(1.25)}100%{transform:scale(1)}}

    /* features */
    .features{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:16px}
    .feature{padding:12px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.95),rgba(255,255,255,0.9));box-shadow:0 6px 20px rgba(0,0,0,0.04)}
    .feature h4{margin:0 0 6px;color:var(--accent)}

    /* sections for work samples & contact */
    section.samples{margin-top:14px}
    .sample-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    .sample{height:140px;border-radius:12px;background:linear-gradient(135deg,#ffffff,#fff6);display:flex;align-items:center;justify-content:center;font-weight:700;color:#444}

    footer{margin-top:22px;padding:18px;text-align:center;color:#333}

    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;gap:14px}
      .stickers{left:6px;top:6px;flex-direction:row}
    }

    /* small glowing underline */
    .fancy-underline{display:inline-block;position:relative}
    .fancy-underline:after{
      content:"";position:absolute;left:0;right:0;bottom:-6px;height:6px;border-radius:6px;background:linear-gradient(90deg,var(--accent),var(--accent2));opacity:0.6;transform:skewX(-8deg)
    }

  </style>
</head>
<body>
  <header>
    <div class="stickers" aria-hidden="true">
      <div class="sticker">🎧</div>
      <div class="sticker">💻</div>
      <div class="sticker">🎙️</div>
    </div>

    <div class="brand">
      <div class="logo">AR</div>
      <div>
        <h1>امین رستمی</h1>
        <p class="lead">طراح سایت • دوبلور نیمه‌حرفه‌ای — خلاق، سریع و دقیق</p>
      </div>
    </div>
  </header>

  <main>
    <div class="hero">
      <div class="card intro">
        <h2>سلام! من <span class="fancy-underline">امین رستمی</span></h2>
        <p>من یک <strong>طراح سایت</strong> هستم که عاشق ساختن صفحات زیبا، سریع و ریسپانسیو برای کسب‌وکارهای کوچک و افراد خلاق‌ام. هم‌زمان <strong>دوبلور</strong> نیمه‌حرفه‌ای هم هستم — یعنی اگر به صدای اختصاصی برای پروژه، تیزر یا پادکست نیاز داشته باشید، من میتوانم کمک کنم.</p><div class="badges" aria-hidden="false">
          <div class="badge">HTML / CSS / JS</div>
          <div class="badge">ریسپانسیو</div>
          <div class="badge">وردپرس (base)</div>
          <div class="badge">دوبلاژ & VO</div>
        </div>

        <a class="cta" href="https://t.me/ajabros" target="_blank" rel="noopener">مشاوره & سفارش — @ajabros</a>

        <div style="margin-top:12px;color:#444">
          <strong>چند خط جذاب دربارهٔ من (قابل ویرایش):</strong>
          <p style="margin:8px 0 0;line-height:1.6">
            من پروژه‌ها را با چاشنی خلاقیت و سرعت تحویل می‌دهم. از تمیز نوشتن کد و بهینه‌سازی برای موبایل لذت می‌برم. اگر دنبال کسی هستید که هم ظاهر سایت را زیبا کند و هم عملکردش روان باشد — من انتخاب خوبی‌ام. برای نمونه‌کارها و قیمت‌ها پایین صفحه را ببینید.
          </p>
        </div>
      </div>

      <aside class="card profile">
        <div class="avatar">AR</div>
        <div class="small-note">امین رستمی — طراح سایت & دوبلور</div>

        <div class="gif-row" aria-hidden="true">
          <div class="mini-gif"><div class="emoji">✨</div></div>
          <div class="mini-gif"><div class="emoji">🔥</div></div>
          <div class="mini-gif"><div class="emoji">🎤</div></div>
        </div>

        <div style="width:100%;text-align:center;margin-top:6px">
          <a class="cta" href="https://t.me/ajabros" target="_blank" rel="noopener">دریافت قیمت / مشاوره</a>
        </div>

        <div style="margin-top:8px;font-size:13px;color:#555;text-align:center">
          <strong>قابلیت‌ها:</strong>
          <div style="margin-top:6px">طراحی سایت – بهینه‌سازی سرعت – پشتیبانی اولیه – دوبلاژ و ضبط صدا</div>
        </div>
      </aside>
    </div>

    <!-- نمونه‌کارها -->
    <section class="card samples">
      <h3 style="margin-top:0">نمونه‌کارها (نمونه‌های فرضی — جای توضیحات و لینک بذار)</h3>
      <div class="sample-grid">
        <div class="sample">فروشگاه نمونه — HTML/CSS</div>
        <div class="sample">سایت شرکتی — ریسپانسیو</div>
        <div class="sample">صفحه فرود تیزر — با انیمیشن</div>
        <div class="sample">دموی دوبلاژ — فایل صوتی (لینک)</div>
      </div>
      <p style="margin-top:10px;color:#444">جاهای خالی بالا برای لینک‌ها و توضیحات نمونه‌کارها هستند — وارد کن تا کارفرما راحت نمونه‌ها را ببینه.</p>
    </section>

    <!-- خدمات -->
    <section class="card" style="margin-top:12px">
      <h3>خدمات من</h3>
      <div class="features">
        <div class="feature">
          <h4>طراحی سایت اختصاصی</h4>
          <p>ساخت صفحات استاتیک و پویا با HTML/CSS/JS — ریسپانسیو و بهینه برای موبایل.</p>
        </div>
        <div class="feature">
          <h4>سئوی اولیه</h4>
          <p>متا تگ‌ها، JSON-LD، سرعت لود و آماده‌سازی برای ثبت در Google Search Console.</p>
        </div>
        <div class="feature">
          <h4>دوبلاژ و صدابرداری</h4>
          <p>ضبط صدای حرفه‌ای برای تیزرها، موشن گرافیک و پروژه‌های صوتی.</p>
        </div>
        <div class="feature">
          <h4>پشتیبانی و آموزش</h4>
          <p>آموزش اولیه مدیریت محتوا و آپدیت سایت به کارفرما پس از تحویل.</p>
        </div>
      </div>
    </section>

    <!-- تماس و اقدام -->
    <section class="card" style="margin-top:12px;text-align:center">
      <h3>می‌خوای پروژه رو شروع کنیم؟</h3>
      <p>برای مشاوره و ارسال نمونه‌کارها و قیمت‌ها راحت‌ترین راه تماس از طریق تلگرام هست:</p>
      <a class="cta" href="https://t.me/ajabros" target="_blank" rel="noopener">@ajabros</a>
      <p style="margin-top:10px;color:#666">یا اگر می‌خوای شماره یا وقت مشاوره بذارم، بگو تا هماهنگ کنیم.</p>
    </section>

    <footer class="card" style="margin-top:18px">
      <div style="display:flex;flex-direction:column;gap:8px;align-items:center">
        <div>© <strong>امین رستمی</strong> — طراح سایت و دوبلور</div>
        <div style="font-size:13px;color:#666">آی‌دی تلگرام: <a href="https://t.me/ajabros" target="_blank" rel="noopener">@ajabros</a></div>
      </div>
    </footer>
  </main>
</body>
</html>
