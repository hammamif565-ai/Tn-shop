<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>متجر تونسي</title>
  <style>
    body {
      font-family: "Tahoma", sans-serif;
      margin: 0;
      background: linear-gradient(to bottom right, #fde2e4, #e0c3fc);
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    header h1 {
      color: #d63384;
      font-size: 22px;
    }
    header a {
      background: #25d366;
      color: white;
      padding: 10px 16px;
      border-radius: 8px;
      text-decoration: none;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 16px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      border-radius: 12px;
    }
    .card h2 {
      font-size: 18px;
      margin: 10px 0 5px;
    }
    .card p {
      font-weight: bold;
      color: #d63384;
    }
    .card a {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 14px;
      background: #d63384;
      color: white;
      text-decoration: none;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>🛍️ متجر تونسي</h1>
    <a href="https://wa.me/21612345678">تواصل واتساب</a>
  </header>

  <section class="products">
    <div class="card">
      <img src="https://via.placeholder.com/300x300.png?text=Handbag" alt="حقيبة يد">
      <h2>حقيبة يد أنيقة</h2>
      <p>85 د</p>
      <a href="https://wa.me/21612345678?text=مرحبا، نحب نشري حقيبة يد أنيقة">اطلب الآن</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x300.png?text=Watch" alt="ساعة">
      <h2>ساعة كلاسيكية</h2>
      <p>120 د</p>
      <a href="https://wa.me/21612345678?text=مرحبا، نحب نشري ساعة كلاسيكية">اطلب الآن</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x300.png?text=Shirt" alt="قميص">
      <h2>قميص رجالي</h2>
      <p>65 د</p>
      <a href="https://wa.me/21612345678?text=مرحبا، نحب نشري قميص رجالي">اطلب الآن</a>
    </div>
  </section>

  <footer>
    © 2025 متجر تونسي - بيع ملابس و اكسسوارات
  </footer>

</body>
</html>
