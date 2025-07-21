<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ร้านไก่ทอดสุดฟิน</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #fff8f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background-color: #ffc0cb;
      padding: 20px 0;
    }

    header img {
      width: 120px;
      border-radius: 50%;
    }

    h1 {
      color: #d63384;
      margin-top: 10px;
    }

    .menu-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 30px;
    }

    .menu-item {
      background-color: white;
      border: 2px solid #ffd6e0;
      border-radius: 15px;
      padding: 15px;
      width: 250px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .menu-item img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 10px;
    }

    .menu-item h2 {
      color: #c2185b;
    }

    .price {
      font-size: 18px;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="โลโก้ไก่สีชมพู">
    <h1>ร้านไก่ทอดสุดฟิน</h1>
  </header>

  <div class="menu-container">
    <div class="menu-item">
      <img src="https://www.themealdb.com/images/media/meals/x0lk931587671540.jpg" alt="ไก่ทอดสูตรดั้งเดิม">
      <h2>ไก่ทอดสูตรดั้งเดิม</h2>
      <p class="price">ราคา: 59 บาท</p>
    </div>
    <div class="menu-item">
      <img src="https://www.themealdb.com/images/media/meals/wvpsxx1468256321.jpg" alt="ไก่ทอดเผ็ดจัดจ้าน">
      <h2>ไก่ทอดเผ็ดจัดจ้าน</h2>
      <p class="price">ราคา: 69 บาท</p>
    </div>
    <div class="menu-item">
      <img src="https://www.themealdb.com/images/media/meals/wyxwsp1486979827.jpg" alt="ไก่ทอดเกาหลีหวาน">
      <h2>ไก่ทอดเกาหลีหวาน</h2>
      <p class="price">ราคา: 75 บาท</p>
    </div>
  </div>

</body>
</html>
