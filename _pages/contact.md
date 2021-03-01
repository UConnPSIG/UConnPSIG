---
title: "Contact"
permalink: "/contact.html"
---

<!-- TODO: use https://formspree.io/{{site.email}} -->

<form action="https://getform.io/f/fe2e1100-dd16-44a8-aeeb-6618305e0aa9" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>