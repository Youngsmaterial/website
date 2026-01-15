<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">

<div style="background:#ffffff; border-bottom:1px solid #dcdcdc;">
  <div style="
    max-width:1280px;
    margin:0 auto;
    padding:1.25rem 1.5rem;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:2rem;
    flex-wrap:wrap;
  ">

    <!-- 左側 LOGO -->
    <a href="index.html" style="display:flex; align-items:center;">
      <img src="images/logo-brand-youngs.png"
           alt="永旭材料貿易有限公司"
           style="height:80px; max-width:none; object-fit:contain;"> 
    </a>

    <!-- 右側 導覽列 -->
    <nav style="
      display:flex;
      gap:1.5rem;
      font-size:0.95rem;
      align-items:center;
      white-space:nowrap;
    ">
      <a href="index.html">公司簡介</a>
      <a href="brands.html">代理品牌</a>
      <a href="products.html">產品列表</a>
      <a href="faq.html">FAQ</a>
      <a href="contact.html" style="font-weight:600;">聯絡我們</a>
    </nav>

  </div>
</div>

# 聯絡我們

如需產品規格、技術資料或報價，歡迎與我們聯繫。

**公司名稱：** 永旭材料貿易有限公司  

**地址：** 臺南市北區大和路330巷21號1樓  

**Email：** ray@youngs.com.tw  

**TEL：** 06-2580502  

**FAX：** 06-2116934  

**服務時間：** 週一至週五 08:30–17:30  

---

## 線上聯絡表單

<form id="contactForm" action="https://formspree.io/f/你的formid" method="POST">
  <label for="name">姓名</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email</label>
  <input type="email" id="email" name="email" required>

  <label for="message">訊息</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">送出</button>
</form>

<div id="successMessage" style="display:none; margin-top:1rem; color:green;">
  ✅ 您的訊息已送出，我們將儘快回覆您！
</div>

<script>
  const form = document.getElementById('contactForm');
  const successMessage = document.getElementById('successMessage');

  form.addEventListener('submit', async (e) => {
    e.preventDefault();
    const formData = new FormData(form);

    const response = await fetch(form.action, {
      method: form.method,
      body: formData,
      headers: { 'Accept': 'application/json' }
    });

    if (response.ok) {
      form.style.display = 'none';
      successMessage.style.display = 'block';
    } else {
      alert('送出失敗，請稍後再試。');
    }
  });
</script>









<footer style="
  margin-top:4rem;
  padding:1.5rem 1rem;
  border-top:1px solid #e5e5e5;
  font-size:0.85rem;
  color:#555;
">
  <div style="
    max-width:1200px;
    margin:0 auto;
    display:flex;
    flex-direction:column;
    gap:0.25rem;
    text-align:center;
  ">
    <div>永旭材料貿易有限公司 ©</div>
    <div>YOUNGS MATERIAL CO., LTD.</div>
    <div>電話：06-2580502 ｜ 地址：臺南市北區大和路330巷21號1樓</div>
  </div>
</footer>
