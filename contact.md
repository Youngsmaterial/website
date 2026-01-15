<!-- 右欄：聯絡表單 -->
<div style="flex:1 1 480px;">

  <h2>聯絡表單</h2>
  <p>請填寫以下資料，我們將盡快與您聯繫。</p>

  <form action="#" method="post">

    <label>
      公司名稱
      <input type="text" name="company" placeholder="請輸入公司名稱">
    </label>

    <label>
      聯絡人
      <input type="text" name="name" placeholder="請輸入聯絡人姓名" required>
    </label>

    <label>
      聯絡電話
      <input type="tel" name="phone" placeholder="請輸入電話">
    </label>

    <label>
      電子郵件
      <input type="email" name="email" placeholder="example@email.com" required>
    </label>

    <label>
      性別
      <select name="gender">
        <option value="">請選擇</option>
        <option value="male">先生</option>
        <option value="female">女士</option>
        <option value="other">其他</option>
      </select>
    </label>

    <label>
      詢問內容
      <textarea name="message" rows="5" placeholder="請輸入您的需求或問題"></textarea>
    </label>

    <button type="submit">送出表單</button>

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
