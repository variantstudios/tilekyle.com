---
layout: page
title: Contact Us
subtitle: Give us a call or send an email.
permalink: /contact/
header_image_path: /assets/images/work/wendys/003.jpg
---


Contact content goes here.

<form action="#" method="post" class="contact-form">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='' />
  <!-- all your input fields here.... -->
    <div class="webform-component">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" required="">
    </div>
    <div class="webform-component">
        <label for="email">Email</label>
        <input type="email" name="email" id="email" required="">
    </div>
    <div class="webform-component">
        <label for="Message">Message</label>
        <textarea id="message" name="message" rows="6" cols="25"></textarea>
    </div>
    <input class="sendButton" type="submit" name="Submit" value="Send">
</form>