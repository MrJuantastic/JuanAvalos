+++
comments = false
draft = false
noauthor = true
share = false
title = "Contact Me"
type = "page"
[menu.main]
weight = 197
+++

<form name="contact" id="contact" netlify>
  <p>
    <label>Name <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message <input type="textarea" name="message" /></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
<textarea name="comment" form="contact" placeholder="Enter message here!"></textarea>