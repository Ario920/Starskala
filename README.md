<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>استارز کالا | فروشگاه آنلاین</title>
  <style>
    /* تنظیمات کلی */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Tahoma', sans-serif;
      direction: rtl;
      background-color: #f4f4f4;
      color: #333;
    }
    a {
      text-decoration: none;
      color: inherit;
    }

    /* هدر */
    header {
      background: linear-gradient(90deg, #FF5722, #FFC107);
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    /* منو */
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
      padding: 10px;
    }
    nav a {
      color: white;
      padding: 10px 20px;
      margin: 0 10px;
      font-size: 1rem;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #FF5722;
      border-radius: 5px;
    }

    /* بنر */
    .banner {
      background: url('https://via.placeholder.com/1200x400') no-repeat center/cover;
      text-align: center;
      color: white;
      padding: 80px 20px;
    }
    .banner h2 {
      font-size: 2.5rem;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
    }
    .banner p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    .banner button {
      margin-top: 20px;
      padding: 10px 20px;
      font-size: 1rem;
      background-color: #FF5722;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .banner button:hover {
      background-color: #E64A19;
    }

    /* محصولات */
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 30px;
      gap: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      width: 300px;
      overflow: hidden;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product h3 {
      font-size: 1.5rem;
      margin: 15px 0;
    }
    .product p {
      font-size: 1rem;
      color: #666;
      padding: 0 10px;
    }
    .product button {
      margin: 15px 0;
      padding: 10px 20px;
      font-size: 1rem;
      background-color: #FF5722;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .product button:hover {
      background-color: #E64A19;
    }

    /* فوتر */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
    footer p {
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>استارز کالا</h1>
  <p>فروشگاه آنلاین محصولات با کیفیت</p>
</header>

<nav>
  <a href="#">خانه</a>
  <a href="#">محصولات</a>
  <a href="#">درباره ما</a>
  <a href="#">تماس با ما</a>
</nav>

<div class="banner">
  <h2>بهترین محصولات با قیمت عالی!</h2>
  <p>تخفیف‌های ویژه برای مدت محدود</p>
  <button>مشاهده محصولات</button>
</div>

<div class="products">
  <!-- محصول: گردوشکن پایه چوبی -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="گردوشکن پایه چوبی">
    <h3>گردوشکن پایه چوبی</h3>
    <p>طراحی زیبا و استحکام بالا</p>
    <button>خرید</button>
  </div>

  <!-- محصول: گردوشکن پایه MDF -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="گردوشکن پایه MDF">
    <h3>گردوشکن پایه MDF</h3>
    <p>مقاوم و اقتصادی</p>
    <button>خرید</button>
  </div>

  <!-- محصول: نبات پرده ۵ کیلویی -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="نبات پرده ۵ کیلویی">
    <h3>نبات پرده ۵ کیلویی</h3>
    <p>خالص و طبیعی</p>
    <button>خرید</button>
  </div>

  <!-- محصول: نبات قهوه‌ای ۵ کیلویی -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="نبات قهوه‌ای ۵ کیلویی">
    <h3>نبات قهوه‌ای ۵ کیلویی</h3>
    <p>طبیعی و ارگانیک</p>
    <button>خرید</button>
  </div>

  <!-- محصول: پتو شادیلون -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="پتو شادیلون">
    <h3>پتو شادیلون</h3>
    <p>گرم و نرم، طرح‌های متنوع</p>
    <button>خرید</button>
  </div>

  <!-- محصول: روفرشی سنتی -->
  <div class="product">
    <img src="https://via.placeholder.com/300x200" alt="روفرشی سنتی">
    <h3>روفرشی سنتی</h3>
    <p>زیبا و بادوام</p>
    <button>خرید</button>
  </div>
</div>

<footer>
  <p>© 2025 استارز کالا. تمامی حقوق محفوظ است.</p>
</footer>

</body>
</html>