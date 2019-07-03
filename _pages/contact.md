---
title: "Связаться"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Если у Вас есть какие-то вопросы, то Вы всегда можете обратиться через форму ниже. Мы ответим так быстро, как только сможем!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Имя *" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail адрес *" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Ваше сообщение *" required></textarea>    
<input class="btn btn-success" type="submit" value="Отправить">
</form>
