+++
author='Alix Pham'
title='Contact'
date='2024-01-01'
draft='false'
+++

<style>
.contact-form {
    max-width: 520px;
    margin-top: 1.5rem;
}
.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 0.6rem 0.8rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    font-family: inherit;
    box-sizing: border-box;
    background: inherit;
    color: inherit;
}
.contact-form textarea {
    height: 140px;
    resize: vertical;
}
.contact-form button {
    padding: 0.6rem 1.6rem;
    background: #268bd2;
    color: #fff;
    border: none;
    border-radius: 4px;
    font-size: 1rem;
    cursor: pointer;
}
.contact-form button:hover {
    background: #1a6fa8;
}
</style>

<form class="contact-form" action="https://formsubmit.co/alix.kl.pham@gmail.com" method="POST">
  <input type="hidden" name="_subject" value="Message from alix-pham.github.io">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://alix-pham.github.io/contact/?sent=true">
  <input type="text" name="name" placeholder="Your name" required>
  <input type="email" name="email" placeholder="Your email" required>
  <textarea name="message" placeholder="Your message" required></textarea>
  <button type="submit">Send</button>
</form>
