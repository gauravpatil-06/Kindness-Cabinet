<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kindness Cabinet – Final Year IT Project</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Roboto:wght@300;500&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background: #f7f9fc;
      margin: 0;
      padding: 0;
      color: #333;
      line-height: 1.6;
    }
    h1, h2, h3 {
      font-family: 'Poppins', sans-serif;
      color: #2c3e50;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .title {
      text-align: center;
      font-size: 28px;
      font-weight: 600;
      margin-bottom: 20px;
      color: #1a73e8;
    }
    .intro, .section {
      background: #fff;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    }
    .section h2 {
      font-size: 22px;
      color: #1a73e8;
      margin-bottom: 10px;
    }
    .section p, .section li {
      font-size: 15px;
    }
    .features, .stack {
      list-style: none;
      padding: 0;
    }
    .features li, .stack li {
      margin: 8px 0;
    }
    .screenshots {
      margin-top: 30px;
    }
    table {
      border-collapse: collapse;
      margin: auto;
      width: 100%;
    }
    td {
      text-align: center;
      background: #fff;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    td:hover {
      transform: scale(1.03);
    }
    td img {
      border-radius: 8px;
      margin-top: 8px;
      background: #fff;
    }
    td b {
      font-family: 'Poppins', sans-serif;
      font-size: 16px;
      color: #2c3e50;
    }
  </style>
</head>
<body>
  <div class="container">

    <h1 class="title">🤝 𝗞𝗶𝗻𝗱𝗻𝗲𝘀𝘀 𝗖𝗮𝗯𝗶𝗻𝗲𝘁 – 𝗗𝗼𝗻𝗮𝘁𝗶𝗼𝗻 & 𝗥𝗲𝘀𝗮𝗹𝗲 𝗔𝗻𝗱𝗿𝗼𝗶𝗱 𝗔𝗽𝗽 | 𝗙𝗶𝗻𝗮𝗹 𝗬𝗲𝗮𝗿 𝗜𝗧 𝗣𝗿𝗼𝗷𝗲𝗰𝘁</h1>

    <div class="intro">
      <p>🌍 Kindness Cabinet is a digital donation & resale platform that enables users to share, donate, or resell unused items such as clothes, books, gadgets, toys, furniture, and household goods.</p>
      <p>♻️ It promotes sustainability by reducing waste and encouraging eco-friendly reuse.</p>
      <p>🤝 The platform connects donors, buyers, and underprivileged communities through a simple mobile app.</p>
      <p>📱 Users can securely list items, manage donations, chat in-app, and track history with ease using XAMPP server + PHP APIs + MySQL backend.</p>
      <p>🏫 Designed as a Final Year IT Project, it demonstrates real-world impact using Android, PHP, and MySQL technologies.</p>
      <p>🌐 Aimed at building a digital community, it combines affordability, accessibility, and social good in one solution.</p>
    </div>

    <div class="section">
      <h2>🔧 Key Features</h2>
      <ul class="features">
        <li>👤 Secure Authentication – Google Sign-In, OTP login, password protection, session management</li>
        <li>📦 Item Listing & Management – Add items with photos, category, price/donation toggle, and item condition</li>
        <li>🗂 18+ Categories – Clothes, Books, Gadgets, Furniture, Toys, Kitchenware, Shoes, Art, Sports, Personal Care, etc.</li>
        <li>🔎 Smart Search & Filters – Category, price, location, condition (new/used), donation-only</li>
        <li>📝 Wishlist & Favorites – Save items for later purchase or donation tracking</li>
        <li>💬 In-App Chat System – Secure communication between donor and recipient</li>
        <li>🔔 Real-Time Notifications – Alerts for new items, chat messages, donations, and offers</li>
        <li>🛒 Payment & Donation Flow – UPI/online payment for resale + digital donation tracking</li>
        <li>📊 Order History & Analytics – Track donated/resold items, reports, and personal contribution stats</li>
        <li>🛡 Admin Dashboard – User management, category control, item approval, fraud detection</li>
        <li>📂 Database Integration – Firebase Realtime DB + MySQL for hybrid data storage</li>
        <li>🌐 Location-Based Services – Google Maps API for nearby items and donors</li>
        <li>🔒 Security Features – Encrypted login, SQL injection prevention, session handling</li>
        <li>🌱 Eco-Friendly Digital Community – Encourages reusability and reduces environmental impact</li>
      </ul>
    </div>

    <div class="section">
      <h2>🎯 Ideal For</h2>
      <p>Colleges, NGOs, and local communities who want a digital donation & resale service to promote sustainability, sharing, and social good.</p>
    </div>

    <div class="section">
      <h2>📚 Skills Learned / Tech Stack Used</h2>
      <ul class="stack">
        <li>📱 Android Development: Java, XML, Android Studio</li>
        <li>🗄 Backend & Database: PHP, MySQL, XAMPP, RESTful APIs</li>
        <li>💾 Data Handling: POJO classes, JSON objects</li>
        <li>🛠 Tools & Testing: Postman, Sublime Text</li>
        <li>🎨 UI/UX & App Features: ListView, RecyclerView, Navigation Drawer, Material Design, custom components</li>
        <li>💬 App Functionality: Chat integration, push notifications, OTP & Google Sign-In authentication</li>
      </ul>
    </div>

    <div class="screenshots">
      <h2>📸 Project Screenshots</h2>
      <table cellspacing="15" cellpadding="15">
        <tr>
          <td>🚀 <b>Splash Screen</b><br><img src="https://github.com/user-attachments/assets/d5d970fc-9af6-4c44-b8e9-ce2463c61e2a" width="250"></td>
          <td>🔐 <b>Login Page</b><br><img src="https://github.com/user-attachments/assets/d2f03b85-365c-4085-bad5-8074bd00589c" width="250"></td>
          <td>📲 <b>OTP Verification</b><br><img src="https://github.com/user-attachments/assets/44a11339-ea3c-44b8-8ec1-cf848760a7f8" width="250"></td>
        </tr>
        <tr>
          <td>🏠 <b>Home Page</b><br><img src="https://github.com/user-attachments/assets/2608c99f-f90a-487e-8eb7-0b4a555e834b" width="250"></td>
          <td>📂 <b>Side Navigation Drawer</b><br><img src="https://github.com/user-attachments/assets/f8c8fd39-0826-4572-8d1b-ffb4b5fcd002" width="250"></td>
          <td>➕ <b>Add Product</b><br><img src="https://github.com/user-attachments/assets/6836ba4e-a2ca-49f6-af4d-0beb2f1c874c" width="250"></td>
        </tr>
        <tr>
          <td>🗂️ <b>Categories</b><br><img src="https://github.com/user-attachments/assets/8a05848d-b245-474f-a452-59e90e9955d1" width="250"></td>
          <td>⭐ <b>Favorite Product</b><br><img src="https://github.com/user-attachments/assets/fa5bca52-5345-4220-9f66-9aa28a20bae3" width="250"></td>
          <td>🔎 <b>Search Product</b><br><img src="https://github.com/user-attachments/assets/d3d44bce-69c8-4f43-964e-ade63844f8f1" width="250"></td>
        </tr>
        <tr>
          <td>💳 <b>Payment</b><br><img src="https://github.com/user-attachments/assets/42138d7a-e15d-4b22-8130-15197cac8341" width="250"></td>
          <td>📦 <b>Order Received</b><br><img src="https://github.com/user-attachments/assets/8db39542-d13d-40a2-9d66-1d90e9f93e02" width="250"></td>
          <td>👤 <b>Admin Module</b><br><img src="https://github.com/user-attachments/assets/01d99aa5-e25a-4448-bd9a-eb7e97b7be67" width="250"></td>
        </tr>
      </table>
    </div>

  </div>
</body>
</html>
