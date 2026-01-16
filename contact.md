---
layout: default
title: 聯絡我們
---

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
      padding:1.5rem;
      border:1px solid #dcdcdc;
      border-radius:6px;
    ">
      <h2 style="margin-top:0;">聯絡表單</h2>

      <p style="color:#555; margin-bottom:1.2rem;">
        請填寫以下資料，我們將儘快與您聯繫。
      </p>

      <form
        action="https://formsubmit.co/ray@youngs.com.tw"
        method="POST"
        style="display:grid; gap:0.6rem; font-size:0.9rem;"
      >
        <input type="hidden" name="_subject" value="官網聯絡表單詢問">
        <input type="hidden" name="_captcha" value="false">
        <input type="hidden" name="_template" value="table">

        <label>
          公司名稱
          <input type="text" name="company">
        </label>

        <label>
          聯絡人
          <input type="text" name="contact_name">
        </label>

        <label>
          聯絡電話
          <input type="tel" name="phone">
        </label>

        <label>
          電子郵件
          <input type="email" name="email" required>
        </label>

        <label>
          詢問內容
          <textarea name="message" rows="3"></textarea>
        </label>

        <button type="submit" style="
          margin-top:0.8rem;
          background:rgba(47,58,65,0.5);
          border:none;
          padding:0.6rem 1.2rem;
          width:140px;
          color:#fff;
          border-radius:4px;
        ">
          送出表單
        </button>
      </form>
    </div>

  </div>
</section>
