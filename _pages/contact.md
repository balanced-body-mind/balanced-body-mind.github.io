---
layout: page
title: "Contact"
permalink: "/contact.html"
---

<form id="contact-form">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<input type="hidden" name="contact_number">
<div class="col-md-6">
<input class="form-control" type="text" name="user_name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="user_email" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>   
<div class="g-recaptcha" data-sitekey="{{site.google_recaptcha_site}}" data-callback="enableBtn"></div>
<br/> 
<input class="btn btn-success" type="submit" value="Send" id="contact-form-btn" disabled="disabled">
</form>