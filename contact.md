<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">

<div style="background:#ffffff; border-bottom:1px solid #dcdcdc;">
  <div style="
    max-width:1280px;
    margin:0 auto;
    padding:1.25rem 1.5rem; /* 保留原本 padding，上下與導覽列平行 */
    display:flex;
    align-items:center; /* logo 與導覽列垂直置中 */
    justify-content:space-between;
    gap:2rem;
    flex-wrap:wrap;
  ">

    <!-- 左側 LOGO -->
    <a href="index" style="display:flex; align-items:center;">
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
      <a href="index">公司簡介</a>
      <a href="brands">代理品牌</a>
      <a href="products">產品列表</a>
      <a href="faq">FAQ</a>
      <a href="contact" style="font-weight:600;">聯絡我們</a>
    </nav>

  </div>
</div>





<section style="max-width:1200px; margin:3rem auto; padding:0 1rem;">
  <div style="display:grid; grid-template-columns:1fr 1fr; gap:3rem;">

    <!-- 左欄：聯絡資訊 -->
    <div>
      <h2>聯絡資訊</h2>

      <p>如需產品規格、技術資料或報價，歡迎與我們聯繫。</p>

      <p><strong>公司名稱：</strong> 永旭材料貿易有限公司</p>
      <p><strong>地址：</strong> 臺南市北區大和路330巷21號1樓</p>
      <p><strong>Email：</strong> ray@youngs.com.tw</p>
      <p><strong>TEL：</strong> 06-2580502</p>
      <p><strong>FAX：</strong> 06-2116934</p>
      <p><strong>服務時間：</strong> 週一至週五 08:30–17:30</p>
    </div>



<!-- 右欄：聯絡表單 -->
<div style="
  background:#f6f7f8;
  padding:2rem;
  border:1px solid #dcdcdc;      
  border-radius:6px;
">

  <h2 style="margin-top:0;">聯絡表單</h2>
  <p style="color:#555; margin-bottom:1.5rem;">
    請填寫以下資料，我們將儘快與您聯繫。
  </p>

  <form style="display:grid; gap:0.6rem; font-size:0.9rem;">

    <label>
      公司名稱
      <input type="text" placeholder="請輸入公司名稱" style="height:1.6rem; font-size:0.9rem; padding:0.2rem;">
    </label>

    <div style="display:grid; grid-template-columns:1fr 1fr; gap:0.6rem;">
      <label>
        聯絡人
        <input type="text" placeholder="請輸入姓名" style="height:1.6rem; font-size:0.9rem; padding:0.2rem;">
      </label>

      <label>
        性別
        <select style="height:1.6rem; font-size:0.9rem; padding:0.2rem;">
          <option>請選擇</option>
          <option>先生</option>
          <option>女士</option>
          <option>其他</option>
        </select>
      </label>
    </div>

    <label>
      聯絡電話
      <input type="tel" placeholder="" style="height:1.6rem; font-size:0.9rem; padding:0.2rem;">
    </label>

    <label>
      電子郵件
      <input type="email" placeholder="example@email.com" style="height:1.6rem; font-size:0.9rem; padding:0.2rem;">
    </label>

    <label>
      詢問內容
      <textarea rows="3" placeholder="請輸入您的需求或產品規格" style="font-size:0.9rem; padding:0.2rem;"></textarea>
    </label>

    <button type="submit" style="
      margin-top:0.8rem;
      background:rgba(47,58,65,0.5);
      border:none;
      padding:0.6rem 1.2rem;
      font-size:0.9rem;
      width:140px;
      color:#fff;
      border-radius:4px;
      cursor:pointer;
    "
    onmouseover="this.style.background='rgba(47,58,65,0.8)'"
    onmouseout="this.style.background='rgba(47,58,65,0.5)'"
    >
      送出表單
    </button>

  </form>
</div>









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
