---
layout: default
title: Contact
permalink: /contact/
---

<style>
.contact-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  margin-top: 40px;
}
.contact-left h2 {
  font-size: 24px;
  font-weight: 900;
  margin-bottom: 24px;
  line-height: 1.3;
}
.contact-info {
  margin-bottom: 32px;
}
.contact-info p {
  margin: 6px 0;
  font-size: 14px;
}
.contact-info a {
  color: inherit;
  text-decoration: none;
}
.contact-right form {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.contact-right input,
.contact-right textarea {
  width: 100%;
  padding: 12px 0;
  border: none;
  border-bottom: 1px solid #333;
  background: transparent;
  font-size: 14px;
  font-family: inherit;
  outline: none;
  box-sizing: border-box;
}
.contact-right textarea {
  height: 120px;
  resize: none;
}
.contact-right button {
  margin-top: 8px;
  padding: 14px;
  background: #000;
  color: #fff;
  border: none;
  font-size: 13px;
  font-family: inherit;
  letter-spacing: 2px;
  cursor: pointer;
  text-transform: uppercase;
}
.contact-right button:hover {
  background: #333;
}
</style>

<div class="contact-wrapper">
  <div class="contact-left">
    <h2>I'm currently based in Berlin, working in events production and studying audio engineering. If you have any projects in mind, want to collaborate, or just want to talk, feel free to reach out.</h2>
    <div class="contact-info">
      <p><strong>Name:</strong> Akshat Nagar</p>
      <p><strong>Location:</strong> Berlin, Germany</p>
      <p><strong>Email:</strong> <a href="mailto:akshat.n02@gmail.com">akshat.n02@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/akshatnagar02/" target="_blank">akshatnagar02</a></p>
    </div>
  </div>
  <div class="contact-right">
    <form action="https://formspree.io/f/mqewkryk" method="POST">
      <input type="text" name="name" placeholder="Name" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="text" name="subject" placeholder="Subject">
      <textarea name="message" placeholder="Message" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </div>
</div>
