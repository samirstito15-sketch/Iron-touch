# Iron-touch
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>بيع لوازم الحفلات</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Cairo', sans-serif;
    background-color: #fafafa;
    margin: 0;
    padding: 0;
  }
  header {
    background-color: #6a1b9a;
    color: white;
    text-align: center;
    padding: 30px 20px;
  }
  header h1 {
    margin: 0;
    font-size: 2.2em;
  }
  .container {
    width: 90%;
    max-width: 1000px;
    margin: 20px auto;
  }
  .items {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  .item {
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    width: 300px;
    text-align: center;
    padding: 20px;
  }
  .item img {
    width: 80px;
    height: 80px;
    margin-bottom: 15px;
  }
  .item h3 {
    margin: 10px 0;
    color: #333;
  }
  .item p {
    color: #555;
    margin: 5px 0 15px 0;
  }
  .item button {
    background-color: #6a1b9a;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
  }
  .item button:hover {
    background-color: #4a148c;
  }
  footer {
    text-align: center;
    padding: 20px;
    color: #777;
    margin-top: 30px;
  }
</style>
</head>
<body>

<header>
  <h1>بيع لوازم الحفلات الطويلة</h1>
  <p>Buffet أنيق وديكور كلاسيكي</p>
</header>

<div class="container">
  <h2 style="text-align:center; color:#333;">منتجاتنا</h2>
  <div class="items">
    <div class="item">
      <img src="plate.png" alt="صحون">
      <h3>صحون كلاسيك</h3>
      <p>ثمن: 50 درهم لكل 10 صحون</p>
      <button>تواصل معانا</button>
    </div>
    <div class="item">
      <img src="glass.png" alt="كؤوس">
      <h3>كؤوس أنيقة</h3>
      <p>ثمن: 70 درهم لكل 10 كؤوس</p>
      <button>تواصل معانا</button>
    </div>
    <div class="item">
      <img src="table.png" alt="طاولات">
      <h3>طاولات Buffet</h3>
      <p>ثمن: 500 درهم للطاولة</p>
      <button>تواصل معانا</button>
    </div>
    <!-- تقدر تزيد منتجات أخرى هنا -->
  </div>
</div>

<footer>
  © 2026 بيع لوازم الحفلات - جميع الحقوق محفوظة
</footer>

<script>
  const buttons = document.querySelectorAll("button");
  buttons.forEach(btn => {
    btn.addEventListener("click", () => {
      alert("شكراً على اهتمامك! تواصل معنا على الرقم: 06XXXXXXXX");
    });
  });
</script>

</body>
</html>
