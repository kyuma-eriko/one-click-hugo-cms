---
title: フォーム送信
date: 2020-12-07T07:39:26.384Z
slug: gov_test_form
---
<form name="contact" method="POST" netlify>
  <p>
    <label>氏名: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">送信</button>
  </p>
</form>