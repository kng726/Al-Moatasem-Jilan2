# Al-Moatasem-Jilan2 <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>المعتصم هاوي - موقع برمجي</title>
  <style>
    /* إعادة ضبط التنسيق */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f7f9;
      color: #333;
      line-height: 1.6;
      direction: rtl;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      letter-spacing: 2px;
      user-select: none;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-right: 25px;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #18bc9c;
    }

    main {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      background: white;
      padding: 25px 30px;
      margin-bottom: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    section h2 {
      margin-bottom: 15px;
      color: #2c3e50;
    }

    section p {
      font-size: 1rem;
      color: #555;
      margin-bottom: 12px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #2c3e50;
      color: white;
      font-size: 0.9rem;
    }

    /* استجابة الشاشات الصغيرة */
    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav {
        margin-top: 15px;
      }

      nav a {
        margin-right: 0;
        margin-left: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">المعتصم هاوي</div>
    <nav>
      <a href="#about">من أنا</a>
      <a href="#services">خدماتي</a>
      <a href="#projects">مشاريعي</a>
      <a href="#contact">تواصل معي</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>من أنا</h2>
      <p>مرحبا بكم في عالم البرمجة مع المعتصم هاوي!</p>
      <p>سعيدون بزيارتكم لموقعي، حيث الإبداع والتقنية يلتقيان.</p>
      <p>أهلاً وسهلاً بكم في منصة التطوير والابتكار.</p>
      <p>مرحبًا بكم في رحلتنا لاكتشاف أفضل حلول البرمجة.</p>
      <p>معًا نبني المستقبل الرقمي بأيدي مبدعة.</p>
      <p>يشرفني تواجدكم هنا، دعونا نبدأ مغامرة البرمجة معًا.</p>
      <p>مرحبًا بكم في مكان يلهم الأفكار ويحولها إلى واقع.</p>
      <p>أهلًا بكم في موقع المعتصم هاوي، حيث تتحقق طموحات البرمجة.</p>
      <p>نسعد بتواجدكم بيننا، لنتعلم ونطور ونبدع.</p>
      <p>أهلاً بكم في وجهتكم الأمثل لعالم البرمجة الحديثة.</p>

      <p>أنا المعتصم هاوي، مطور شغوف أعمل على بناء تطبيقات ويب نظيفة وفعالة وعصرية. أتخصص في تطوير الواجهة الأمامية والخلفية مع التركيز على تجربة المستخدم.</p>
    </section>

    <section id="services">
      <h2>خدماتي</h2>
      <p>أقدم مجموعة متنوعة من الخدمات البرمجية مثل تطوير المواقع، تطوير التطبيقات، مراجعة الأكواد، والاستشارات التقنية لمساعدتك على تحويل أفكارك إلى واقع باستخدام أحدث التقنيات.</p>
    </section>

    <section id="projects">
      <h2>مشاريعي</h2>
      <p>تعرف على بعض مشاريعي الحديثة التي تظهر مهاراتي في تطوير الواجهات والخلفيات باستخدام أُطُر مثل React، Node.js، وPython Django.</p>
    </section>

    <section id="contact">
      <h2>تواصل معي</h2>
      <p>لا تتردد في التواصل معي لأي تعاون أو استفسار عن المشاريع أو حتى لإلقاء التحية. يمكنك مراسلتي عبر البريد الإلكتروني: <a href="mailto:almoatasem@example.com">almoatasem@example.com</a>.</p>
    </section>
  </main>

  <footer>
    &copy; 2025 المعتصم هاوي. جميع الحقوق محفوظة.
  </footer>
</body>
</html>
