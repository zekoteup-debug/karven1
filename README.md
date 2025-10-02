<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="description" content="اسألني سؤال — صفحة الأسئلة الخاصة بـ [اسمك].">
  <title>اسألني سؤال — [اسمك]</title>
  <!--
    تعليمات سريعة:
    1) استبدل [اسمك] باسمك الظاهر.
    2) لو عندك Google Form: انسخ رابط "Embed" من Google Forms ووضعه في iframe أدناه مكان YOUR_GOOGLE_FORM_EMBED_LINK
    3) لحفظ الصفحة كموقع حي مجاني: استخدم GitHub Pages أو Netlify أو Cloudflare Pages. إرشادات النشر مضافة تحت قسم "نشر" في هذا الملف.
  -->
  <style>
    :root{--bg:#0f172a;--card:#0b1220;--accent:#06b6d4;--text:#e6eef8}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,Segoe UI,Helvetica,Arial,sans-serif;background:linear-gradient(180deg,var(--bg),#071126);color:var(--text);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:24px}
    .wrap{max-width:900px;width:100%}
    .card{background:rgba(255,255,255,0.02);padding:24px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    h1{margin:0 0 8px;font-size:28px}
    p.lead{margin:0 0 18px;opacity:0.9}
    .instructions{background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;margin-bottom:18px}
    .form-frame{width:100%;height:520px;border-radius:8px;border:0}
    .actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:14px}
    .btn{padding:10px 14px;border-radius:8px;border:0;background:var(--accent);color:#022;cursor:pointer;text-decoration:none;font-weight:600}
    footer{opacity:0.7;margin-top:18px;font-size:13px}
    @media(min-width:720px){h1{font-size:34px}}
  </style>
</head>
<body>
  <main class="wrap card" role="main">
    <h1>اسألني سؤال — [اسمك]</h1>
    <p class="lead">ضع سؤالك هنا وسيصير جزء من فيديو الردود! 👇</p>

    <div class="instructions">
      <strong>ملاحظة:</strong> هذه الصفحة ثابتة (Static). لتخزين الأسئلة أو استقبالها في مكان واحد بسهولة، استخدم Google Forms وادمجه هنا.
    </div>

    <!-- استبدل قيمة src برابط الـ embed من Google Forms أو رابط خدمة نماذج أخرى -->
    <iframe class="form-frame" src="YOUR_GOOGLE_FORM_EMBED_LINK" title="نموذج اسألني"></iframe>

    <div class="actions">
      <a class="btn" href="#how-to-deploy">تعلّم كيف أنشر الموقع مجانا</a>
      <a class="btn" href="#seo">نصائح لظهور الموقع في جوجل</a>
    </div>

    <section id="how-to-deploy" style="margin-top:18px">
      <h2 style="font-size:18px;margin-bottom:8px">نشر مجاني سريع (GitHub Pages)</h2>
      <ol>
        <li>سجّل في <strong>GitHub</strong> (github.com) إن ما عندك حساب.</li>
        <li>أنشئ مستودع جديد repo وسمّه <code>username.github.io</code> (بدّل "username" باسم حسابك على GitHub).</li>
        <li>ادفع (upload) ملف <code>index.html</code> هذا للمستودع (يمكن سحب الملفات بالـ drag & drop من واجهة GitHub).</li>
        <li>ادخل Settings &gt; Pages ثم اختَر الفرع <code>main</code> والمجلد <code>/ (root)</code>، واضغط Save.
          بعد قليل سيصبح موقعك متاحاً على: <code>https://username.github.io</code>
        </li>
      </ol>
      <p style="margin-top:8px">بدائل: <strong>Netlify</strong>, <strong>Vercel</strong>, أو <strong>Cloudflare Pages</strong> — كلها تسمح بنشر صفحات ثابتة مجاناً وتدعم الربط بـ GitHub تلقائياً.</p>
    </section>

    <section id="seo" style="margin-top:14px">
      <h2 style="font-size:18px;margin-bottom:8px">كيف أخلي الموقع يطلع في بحث Google</h2>
      <ul>
        <li>تأكد من وجود <code>&lt;meta name="description"&gt;</code> وصديق للهواتف (هذا الموقع بسيط ومتلائم).</li>
        <li>أنشئ ملف <code>sitemap.xml</code> بسيط وأرفعه للمستودع (أمثلة في التعليقات أسفل الملف).</li>
        <li>سجّل موقعك في <strong>Google Search Console</strong> — ثم أضف موقعك وحقق الملكية (Verification) باتباع التعليمات، ثم أرسل ملف sitemap.</li>
        <li>ضع الرابط في البايوهات واطلب من المتابعين يزوروه — الروابط الخارجية (Backlinks) تزيد من فرص الأرشفة.</li>
      </ul>
      <p style="margin-top:6px;opacity:0.9">ملاحظة: الفهرسة في Google قد تأخذ من أيام إلى أسابيع. تأكد أن الملف <code>robots.txt</code> لا يمنع محركات البحث.</p>
    </section>

    <footer>
      تم تصميم الصفحة لتكون بداية سريعة. لو تبي أعدّل لك الصفحة بالاسم حقك وأدرج Google Form جاهز — قول اسمك وارفق رابط النموذج إن عندك.
    </footer>

    <!--
      أمثلة لملفات إضافية (ضعها في نفس المستودع):

      robots.txt
      -----------
      User-agent: *
      Allow: /
      Sitemap: https://username.github.io/sitemap.xml

      sitemap.xml (بسيط)
      -------------------
      <?xml version="1.0" encoding="UTF-8"?>
      <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
        <url>
          <loc>https://username.github.io/</loc>
          <changefreq>daily</changefreq>
          <priority>1.0</priority>
        </url>
      </urlset>

      استبدل "username.github.io" بعنوان موقعك الفعلي.
    -->
  </main>
</body>
<
