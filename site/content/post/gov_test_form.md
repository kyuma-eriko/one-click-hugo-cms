---
title: フォーム送信
date: 2020-12-07T07:39:26.384Z
slug: gov_test_form
---
講習会申込フォーム
<form name="kosyukai" method="POST" netlify-honeypot="bot-field" data-netlify="true">
<input type="hidden" name="form-name" value="kosyukai" />
<p>Your Name: <input type="text" name="name" /></p>
<p>Your Email: <input type="email" name="email" /></p>
<p>メッセージ: <textarea name="message"></textarea>
</p>
<p><button type="submit">送信</button></p>
</form>