<!doctype html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="theme-color" content="#0c534d" />
  <meta name="description" content="شرکت سمپاشی عجم تجارت آریا؛ خدمات کنترل آفات و جوندگان شهری در تهران و کرج، با بازدید رایگان و ضمانت‌نامه کتبی." />
  <title>عجم تجارت آریا | سمپاشی تهران و کرج</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800&display=swap');

    :root{
      --primary:#0c534d;
      --primary-dark:#073b37;
      --accent:#f4b942;
      --ink:#102a29;
      --muted:#5f7270;
      --light:#f5faf8;
      --white:#ffffff;
      --line:#dce9e5;
      --danger:#b42318;
      --shadow:0 16px 42px rgba(7,59,55,.12);
      --radius:18px;
    }

    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family:"Vazirmatn",Tahoma,sans-serif;
      color:var(--ink);
      background:#fff;
      line-height:1.9;
    }

    a{text-decoration:none;color:inherit}
    button,input,select,textarea{font:inherit}
    .container{width:min(1160px,92%);margin:auto}
    .section{padding:82px 0}
    .soft{background:var(--light)}
    .eyebrow{
      color:var(--primary);
      font-size:.88rem;
      font-weight:800;
      letter-spacing:.2px;
    }
    .title{
      margin:6px 0 12px;
      font-size:clamp(1.7rem,4vw,2.5rem);
      line-height:1.5;
    }
    .lead{color:var(--muted);max-width:720px;margin:0}

    /* Header */
    .topbar{
      background:var(--primary-dark);
      color:#e9f6f3;
      font-size:.86rem;
    }
    .topbar .container{
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:12px;
      padding:8px 0;
      flex-wrap:wrap;
    }
    .topbar a{color:#fff;font-weight:700}
    header{
      position:sticky;
      top:0;
      z-index:50;
      background:rgba(255,255,255,.96);
      backdrop-filter:blur(10px);
      border-bottom:1px solid rgba(12,83,77,.08);
    }
    .nav{
      min-height:78px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:18px;
    }
    .brand{display:flex;align-items:center;gap:10px;min-width:205px}
    .brand-mark{
      width:46px;height:46px;border-radius:14px;
      display:grid;place-items:center;
      background:linear-gradient(145deg,var(--primary),#14786f);
      color:var(--accent);
      font-size:1.35rem;font-weight:800;
      box-shadow:0 8px 20px rgba(12,83,77,.2);
    }
    .brand-fa{font-size:1rem;font-weight:800;line-height:1.2}
    .brand-en{
      direction:ltr;text-align:right;display:block;
      color:var(--muted);font-family:Arial,sans-serif;
      letter-spacing:1px;font-size:.6rem;margin-top:4px;
    }
    .menu{display:flex;align-items:center;gap:18px;font-size:.91rem;font-weight:600}
    .menu a:hover{color:var(--primary)}
    .nav-actions{display:flex;gap:8px;align-items:center}
    .language{
      border:1px solid var(--line);
      background:#fff;
      border-radius:10px;
      padding:7px 8px;
      color:var(--primary);
      cursor:pointer;
      font-size:.8rem;
    }
    .btn{
      display:inline-flex;align-items:center;justify-content:center;gap:8px;
      border:0;cursor:pointer;border-radius:12px;
      padding:11px 17px;font-weight:800;
      transition:.2s ease;
    }
    .btn:hover{transform:translateY(-2px)}
    .btn-primary{background:var(--primary);color:#fff;box-shadow:0 10px 20px rgba(12,83,77,.18)}
    .btn-accent{background:var(--accent);color:#2a2412}
    .btn-outline{background:#fff;color:var(--primary);border:1px solid #b8d5ce}
    .menu-toggle{display:none;background:transparent;border:0;font-size:1.5rem;color:var(--primary)}

    /* Hero */
    .hero{
      overflow:hidden;
      position:relative;
      color:#fff;
      background:
        linear-gradient(100deg,rgba(5,49,45,.95),rgba(8,84,77,.78)),
        url("https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=1600&q=80") center/cover;
    }
    .hero:after{
      content:"";position:absolute;width:520px;height:520px;border-radius:50%;
      background:rgba(244,185,66,.13);left:-190px;bottom:-260px;
    }
    .hero .container{
      min-height:555px;display:grid;grid-template-columns:1.2fr .8fr;gap:35px;
      align-items:center;position:relative;z-index:1;
    }
    .hero h1{
      font-size:clamp(2rem,5vw,3.7rem);line-height:1.35;
      margin:13px 0 16px;
    }
    .hero p{max-width:650px;color:#e4f3ef;font-size:1.05rem}
    .hero-tag{
      display:inline-flex;gap:8px;align-items:center;
      background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.2);
      border-radius:999px;padding:7px 12px;font-size:.84rem;
    }
    .hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:27px}
    .hero-card{
      background:rgba(255,255,255,.96);color:var(--ink);
      padding:26px;border-radius:22px;box-shadow:var(--shadow);
      border:1px solid rgba(255,255,255,.7);
    }
    .hero-card h3{margin:0 0 8px;color:var(--primary)}
    .hero-card p{color:var(--muted);font-size:.88rem;margin:0 0 15px}
    .quick-list{display:grid;gap:10px;margin:15px 0}
    .quick-item{display:flex;align-items:center;gap:10px;font-size:.88rem}
    .tick{
      width:23px;height:23px;border-radius:50%;background:#dff4eb;
      color:var(--primary);display:grid;place-items:center;font-weight:800;font-size:.8rem
    }

    /* Trust bar */
    .trust{background:#fff;border-bottom:1px solid var(--line)}
    .trust-grid{
      display:grid;grid-template-columns:repeat(5,1fr);
      gap:12px;padding:22px 0;
    }
    .trust-item{display:flex;gap:9px;align-items:center;font-size:.86rem;font-weight:700}
    .trust-icon{
      width:34px;height:34px;border-radius:10px;background:#eaf7f3;color:var(--primary);
      display:grid;place-items:center;font-size:1.1rem
    }

    /* Cards */
    .grid{display:grid;gap:20px}
    .services{grid-template-columns:repeat(3,1fr);margin-top:32px}
    .card{
      background:#fff;border:1px solid var(--line);border-radius:var(--radius);
      padding:24px;transition:.25s ease;
    }
    .card:hover{transform:translateY(-5px);box-shadow:var(--shadow);border-color:#c2ded7}
    .service-icon{
      width:52px;height:52px;border-radius:15px;background:#e9f7f2;
      display:grid;place-items:center;font-size:1.55rem;margin-bottom:15px
    }
    .card h3{font-size:1.06rem;margin:0 0 7px;color:var(--primary)}
    .card p{margin:0;color:var(--muted);font-size:.9rem;line-height:1.9}

    /* Steps */
    .steps{grid-template-columns:repeat(4,1fr);margin-top:34px;position:relative}
    .step{position:relative;background:#fff;padding:22px;border-radius:16px;border:1px solid var(--line)}
    .step-number{
      background:var(--primary);color:#fff;width:34px;height:34px;border-radius:50%;
      display:grid;place-items:center;font-weight:800;margin-bottom:12px
    }
    .step h3{margin:0 0 7px;font-size:1rem}
    .step p{margin:0;color:var(--muted);font-size:.85rem}

    /* Articles */
    .articles{grid-template-columns:repeat(3,1fr);margin-top:30px}
    .article{overflow:hidden;padding:0}
    .article-img{height:175px;background-size:cover;background-position:center}
    .article-content{padding:20px}
    .article span{font-size:.76rem;color:var(--primary);font-weight:800}
    .article h3{font-size:1rem;margin:8px 0}
    .article p{font-size:.86rem}

    /* Contact / map */
    .contact-wrap{display:grid;grid-template-columns:1fr 1fr;gap:25px}
    .contact-box{background:#fff;border:1px solid var(--line);padding:28px;border-radius:20px}
    .contact-list{display:grid;gap:14px;margin-top:18px}
    .contact-row{display:flex;gap:12px;align-items:flex-start}
    .contact-row b{display:block;color:var(--primary);font-size:.88rem}
    .contact-row span,.contact-row a{font-size:.9rem;color:var(--muted)}
    .map{min-height:370px;border:0;border-radius:20px;width:100%;box-shadow:var(--shadow)}

    /* Modal form */
    .modal{
      position:fixed;inset:0;background:rgba(3,25,23,.65);z-index:100;
      display:none;align-items:center;justify-content:center;padding:18px;
    }
    .modal.show{display:flex}
    .modal-box{
      width:min(760px,100%);max-height:92vh;overflow:auto;
      background:#fff;border-radius:22px;padding:28px;position:relative;
    }
    .close{
      position:absolute;left:17px;top:13px;border:0;background:#eef7f4;
      color:var(--primary);width:35px;height:35px;border-radius:50%;cursor:pointer;font-size:1.15rem
    }
    .progress{height:8px;background:#e7efec;border-radius:99px;margin:15px 0 24px;overflow:hidden}
    .progress > div{height:100%;width:20%;background:var(--primary);transition:.3s}
    .form-step{display:none}
    .form-step.active{display:block}
    .form-grid{display:grid;grid-template-columns:1fr 1fr;gap:15px}
    .field{display:grid;gap:6px;margin-bottom:13px}
    .field.full{grid-column:1/-1}
    label{font-size:.85rem;font-weight:700;color:#24413e}
    input,select,textarea{
      border:1px solid #cde0db;border-radius:11px;padding:11px 12px;outline:none;
      color:var(--ink);background:#fff;
    }
    input:focus,select:focus,textarea:focus{border-color:var(--primary);box-shadow:0 0 0 3px rgba(12,83,77,.09)}
    textarea{min-height:92px;resize:vertical}
    .form-actions{display:flex;justify-content:space-between;gap:10px;margin-top:18px}
    .hint{font-size:.78rem;color:var(--muted)}
    .success{text-align:center;padding:20px 10px}
    .success .success-mark{
      width:74px;height:74px;border-radius:50%;display:grid;place-items:center;
      margin:0 auto 15px;background:#dff4eb;color:var(--primary);font-size:2rem
    }
    .tracking{
      margin:16px auto;padding:15px;background:#f0faf6;border:1px dashed #76b5a7;
      border-radius:12px;color:var(--primary);font-size:1.25rem;font-weight:800;direction:ltr;width:max-content
    }

    /* Footer & floating */
    footer{background:#073b37;color:#d9eeea;padding:55px 0 20px}
    .footer-grid{display:grid;grid-template-columns:1.3fr 1fr 1fr;gap:35px}
    .footer-title{color:#fff;font-weight:800;margin-bottom:12px}
    footer p,footer a{font-size:.87rem;color:#c5ddd8}
    .footer-links{display:grid;gap:7px}
    .copy{border-top:1px solid rgba(255,255,255,.12);padding-top:16px;margin-top:35px;font-size:.75rem;color:#adcbc4}
    .float{
      position:fixed;left:18px;bottom:18px;z-index:80;
      display:flex;flex-direction:column;gap:10px;
    }
    .float a{
      width:53px;height:53px;border-radius:17px;display:grid;place-items:center;
      color:#fff;font-size:1.35rem;box-shadow:0 10px 20px rgba(0,0,0,.18)
    }
    .whatsapp{background:#25d366}.phone{background:var(--primary)}

    @media(max-width:900px){
      .menu{display:none}
      .menu-toggle{display:block}
      .hero .container{grid-template-columns:1fr;padding:56px 0}
      .hero-card{max-width:500px}
      .trust-grid{grid-template-columns:repeat(2,1fr)}
      .services,.articles{grid-template-columns:repeat(2,1fr)}
      .steps{grid-template-columns:repeat(2,1fr)}
      .contact-wrap{grid-template-columns:1fr}
    }
    @media(max-width:580px){
      .topbar .container{justify-content:center;text-align:center}
      .nav{min-height:68px}
      .brand-mark{width:40px;height:40px}
      .nav-actions .btn{display:none}
      .hero h1{font-size:2rem}
      .hero .container{min-height:auto}
      .services,.articles,.steps,.form-grid,.footer-grid{grid-template-columns:1fr}
      .trust-grid{grid-template-columns:1fr}
      .section{padding:58px 0}
      .modal-box{padding:22px 17px}
      .form-actions{flex-wrap:wrap}
    }
  </style>
</head>

<body>

  <div class="topbar">
    <div class="container">
      <span>پاسخ‌گویی و مشاوره <b>۲۴ ساعته</b> در تهران و کرج</span>
      <span>واتساپ و تماس: <a href="tel:09206847795">۰۹۲۰۶۸۴۷۷۹۵</a></span>
    </div>
  </div>

  <header>
    <div class="container nav">
      <a class="brand" href="#home" aria-label="عجم تجارت آریا">
        <span class="brand-mark">ع</span>
        <span>
          <span class="brand-fa">عجم تجارت آریا</span>
          <span class="brand-en">AJAM TEJARAT ARIA</span>
        </span>
      </a>

      <nav class="menu">
        <a href="#home">خانه</a>
        <a href="#services">خدمات</a>
        <a href="#process">روند کار</a>
        <a href="#articles">مقالات</a>
        <a href="#contact">تماس با ما</a>
      </nav>

      <div class="nav-actions">
        <button class="language" type="button" title="نسخه چندزبانه">فا | EN | AR</button>
        <button class="btn btn-primary open-form" type="button">درخواست رایگان</button>
        <button class="menu-toggle" type="button" aria-label="منو">☰</button>
      </div>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container">
        <div>
          <span class="hero-tag">✓ بازدید و کارشناسی اولیه رایگان</span>
          <h1>سمپاشی تخصصی در تهران و کرج، با ضمانت‌نامه کتبی</h1>
          <p>
            شرکت سمپاشی عجم تجارت آریا از سال ۱۳۹۵ در زمینه کنترل حشرات موذی و جوندگان شهری،
            خدمات باغی، نظافتی و تأمین نیروی انسانی فعالیت دارد.
          </p>
          <div class="hero-actions">
            <button class="btn btn-accent open-form" type="button">ثبت درخواست عملیات</button>
            <a class="btn btn-outline" href="tel:09206847795">تماس فوری</a>
          </div>
        </div>

        <aside class="hero-card">
          <h3>چرا عجم تجارت آریا؟</h3>
          <p>ارائه راهکار متناسب با شرایط محل، همراه با پیگیری تا حصول نتیجه.</p>
          <div class="quick-list">
            <div class="quick-item"><span class="tick">✓</span> پاسخ‌گویی ۲۴ ساعته</div>
            <div class="quick-item"><span class="tick">✓</span> بازدید و کارشناسی رایگان</div>
            <div class="quick-item"><span class="tick">✓</span> ضمانت‌نامه کتبی خدمات</div>
            <div class="quick-item"><span class="tick">✓</span> پوشش تمام مناطق تهران و کرج</div>
          </div>
          <button class="btn btn-primary open-form" type="button" style="width:100%">درخواست بازدید رایگان</button>
        </aside>
      </div>
    </section>

    <section class="trust">
      <div class="container trust-grid">
        <div class="trust-item"><span class="trust-icon">◷</span>پاسخ‌گویی ۲۴ ساعته</div>
        <div class="trust-item"><span class="trust-icon">⌕</span>بازدید رایگان</div>
        <div class="trust-item"><span class="trust-icon">✓</span>ضمانت‌نامه کتبی</div>
        <div class="trust-item"><span class="trust-icon">◎</span>پوشش تهران و کرج</div>
        <div class="trust-item"><span class="trust-icon">★</span>پیگیری تا حصول نتیجه</div>
      </div>
    </section>

    <section class="section" id="services">
      <div class="container">
        <div class="eyebrow">خدمات ما</div>
        <h2 class="title">راهکارهای کامل برای محیط‌های مسکونی و سازمانی</h2>
        <p class="lead">خدمات بر اساس نوع آفت، شرایط محل و نیاز مشتری بررسی و برنامه‌ریزی می‌شود.</p>

        <div class="grid services">
          <article class="card">
            <div class="service-icon">🪳</div>
            <h3>کنترل حشرات موذی</h3>
            <p>کنترل سوسک، ساس، مورچه، مگس، پشه، کنه، موریانه و سایر حشرات مزاحم.</p>
          </article>
          <article class="card">
            <div class="service-icon">🐭</div>
            <h3>کنترل جوندگان شهری</h3>
            <p>بازدید، شناسایی مسیرها، تله‌گذاری و طعمه‌گذاری برای کنترل موش و جوندگان.</p>
          </article>
          <article class="card">
            <div class="service-icon">🏢</div>
            <h3>خدمات سازمانی</h3>
            <p>ادارات، کارخانه‌ها، انبارها، مجتمع‌ها، فروشگاه‌ها و محیط‌های تجاری.</p>
          </article>
          <article class="card">
            <div class="service-icon">🍽️</div>
            <h3>رستوران و آشپزخانه صنعتی</h3>
            <p>برنامه کنترل آفات برای رستوران، کافه، آشپزخانه و مراکز تهیه غذا.</p>
          </article>
          <article class="card">
            <div class="service-icon">🌿</div>
            <h3>خدمات باغی و فضای سبز</h3>
            <p>رسیدگی به آفات باغ و فضای سبز با توجه به شرایط محیط و نوع پوشش گیاهی.</p>
          </article>
          <article class="card">
            <div class="service-icon">🧹</div>
            <h3>نظافت و تأمین نیرو</h3>
            <p>ارائه خدمات نظافتی و تأمین نیروی انسانی متناسب با نیاز مجموعه‌ها.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section soft" id="process">
      <div class="container">
        <div class="eyebrow">روند همکاری</div>
        <h2 class="title">از ثبت درخواست تا پیگیری نتیجه</h2>
        <p class="lead">فرایندی شفاف برای ثبت دقیق درخواست و هماهنگی سریع با کارشناسان.</p>

        <div class="grid steps">
          <div class="step"><div class="step-number">۱</div><h3>ثبت درخواست</h3><p>اطلاعات محل، نوع آفت و توضیحات را به‌صورت آنلاین ثبت می‌کنید.</p></div>
          <div class="step"><div class="step-number">۲</div><h3>دریافت کد پیگیری</h3><p>پس از ثبت، یک شماره پیگیری برای شما پیامک می‌شود.</p></div>
          <div class="step"><div class="step-number">۳</div><h3>تماس کارشناس</h3><p>کارشناس برای بررسی، مشاوره و هماهنگی بازدید با شما تماس می‌گیرد.</p></div>
          <div class="step"><div class="step-number">۴</div><h3>اجرا و پیگیری</h3><p>عملیات با ضمانت‌نامه کتبی و پیگیری تا حصول نتیجه انجام می‌شود.</p></div>
        </div>
      </div>
    </section>

    <section class="section" id="articles">
      <div class="container">
        <div class="eyebrow">آموزش و راهنما</div>
        <h2 class="title">مقاله‌های کاربردی کنترل آفات</h2>
        <p class="lead">بخش وبلاگ در نسخه نهایی با مقاله‌های آموزشی کامل‌تر به‌روزرسانی می‌شود.</p>

        <div class="grid articles">
          <article class="card article">
            <div class="article-img" style="background-image:url('https://images.unsplash.com/photo-1584556814952-905f336c7d8b?auto=format&fit=crop&w=900&q=80')"></div>
            <div class="article-content">
              <span>راهنمای منزل</span>
              <h3>پیش از سمپاشی منزل چه کارهایی لازم است؟</h3>
              <p>چند نکته کاربردی برای آماده‌سازی محیط پیش از حضور کارشناس.</p>
            </div>
          </article>
          <article class="card article">
            <div class="article-img" style="background-image:url('https://images.unsplash.com/photo-1596838132731-3301c3fd4317?auto=format&fit=crop&w=900&q=80')"></div>
            <div class="article-content">
              <span>کنترل جوندگان</span>
              <h3>راه‌های پیشگیری از ورود موش به ساختمان</h3>
              <p>نکات اولیه برای کاهش ریسک حضور جوندگان در منزل و محل کار.</p>
            </div>
          </article>
          <article class="card article">
            <div class="article-img" style="background-image:url('https://images.unsplash.com/photo-1625246333195-78d9c38ad449?auto=format&fit=crop&w=900&q=80')"></div>
            <div class="article-content">
              <span>باغ و فضای سبز</span>
              <h3>زمان مناسب رسیدگی به آفات باغی</h3>
              <p>چرا شناسایی زودهنگام آفت در فضای سبز اهمیت دارد؟</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section soft" id="contact">
      <div class="container contact-wrap">
        <div class="contact-box">
          <div class="eyebrow">ارتباط با ما</div>
          <h2 class="title">آماده پاسخ‌گویی هستیم</h2>
          <p class="lead">برای مشاوره، استعلام و ثبت درخواست عملیات با ما در تماس باشید.</p>

          <div class="contact-list">
            <div class="contact-row">
              <span class="trust-icon">☎</span>
              <div><b>تماس و واتساپ</b><a href="tel:09206847795">۰۹۲۰۶۸۴۷۷۹۵</a></div>
            </div>
            <div class="contact-row">
              <span class="trust-icon">✉</span>
              <div><b>ایمیل</b><a href="mailto:ajamtejaratariaco@gmail.com">ajamtejaratariaco@gmail.com</a></div>
            </div>
 