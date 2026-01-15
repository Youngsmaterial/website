<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">

# 聯絡我們

如需產品規格、技術資料或報價，歡迎與我們聯繫。

<section style="max-width:1200px; margin:2rem auto; display:flex; gap:2rem; flex-wrap:wrap;">

  <!-- 左側公司資訊 -->
  <div style="flex:1; min-width:280px;">
    <h2>公司資訊</h2>
    <p><strong>公司名稱：</strong> 永旭材料貿易有限公司</p>
    <p><strong>地址：</strong> 臺南市北區大和路330巷21號1樓</p>
    <p><strong>Email：</strong> ray@youngs.com.tw</p>
    <p><strong>TEL：</strong> 06-2580502</p>
    <p><strong>FAX：</strong> 06-2116934</p>
    <p><strong>服務時間：</strong> 週一至週五 08:30–17:30</p>
    <p>📩 歡迎來信洽詢，我們將儘快回覆您。</p>
  </div>

  <!-- 右側聯絡表單 -->
  <form action="https://formsubmit.co/ray@youngs.com.tw" method="POST" style="flex:1; min-width:300px; padding:1rem; border:1px solid #dcdcdc; border-radius:8px; background:#fafafa;">
    <h2>聯絡表單</h2>

    <label for="company">公司名稱</label>
    <input type="text" id="company" name="company" placeholder="請輸入公司名稱" required>

    <label for="name">聯絡人</label>
    <input type="text" id="name" name="name" placeholder="請輸入姓名" required>

    <label>性別</label>
    <div>
      <input type="radio" id="male" name="gender" value="男性" required>
      <label for="male">男性</label>
      <input type="radio" id="female" name="gender" value="女性">
      <label for="female">女性</label>
      <input type="radio" id="other" name="gender" value="其他">
      <label for="other">其他</label>
    </div>

    <label for="phone">電話</label>
    <input type="tel" id="phone" name="phone" placeholder="請輸入聯絡電話" required>

    <label for="email">Email</label>
    <input type="email" id="email" name="email" placeholder="請輸入Email" required>

    <label for="message">留言內容</label>
    <textarea id="message" name="message" rows="5" placeholder="請輸入留言內容" required></textarea>

    <!-- 可選：自動回覆與感謝頁 -->
    <input type="hidden" name="_autoresponse" value="感謝您的來信，我們會盡快回覆您。">
    <input type="hidden" name="_next" value="https://yourwebsite.com/thank-you">

    <button type="submit">送出</button>
  </form>

</section>






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
