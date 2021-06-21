---
layout: page
title: Share a Meme
permalink: /memeform/
---

<form name="submitMeme" netlify-honeypot="bot-field" action="/thanks.html" netlify>
  <p style="display:none;">
    <label>Don't fill this out: <input name="bot-field"></label>
  </p>
  <p>
    <label>Name: <input type="text" name="name" size="40"></label>
  </p>
  <p>
    <label>Email: <input type="text" name="email" size="40"></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

