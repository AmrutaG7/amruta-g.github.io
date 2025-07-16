---
layout: single
title: "Contact"
permalink: /contact/
---

<style>
.contact-hero {
  background: url('/assets/contact-bg.jpg') no-repeat center center;
  background-size: cover;
  padding: 80px 20px;
  color: white;
  text-align: center;
  text-shadow: 1px 1px 6px rgba(0,0,0,0.6);
  margin-bottom: 3rem;
}

.contact-hero h1 {
  font-size: 3rem;
  margin: 0;
}

.contact-section {
  max-width: 700px;
  margin: auto;
  padding: 0 20px;
}

.contact-section form {
  display: flex;
  flex-direction: column;
}

.contact-section label {
  margin-top: 1rem;
  font-weight: bold;
}

.contact-section input,
.contact-section textarea {
  padding: 10px;
  margin-top: 5px;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.contact-section button {
  margin-top: 1.5rem;
  padding: 10px 20px;
  background-color: #007acc;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.contact-section button:hover {
  background-color: #005fa3;
}
</style>

<div class="contact-hero">
  <h1>Let's Connect</h1>
  <p>Have a question or opportunity? Send me a message!</p>
</div>

<div class="contact-section">
  <form action="https://formspree.io/f/your-form-id" method="POST">
    <label for="name">Name</label>
    <input type="text" name="name" id="name" required>

    <label for="email">Email</label>
    <input type="email" name="_replyto" id="email" required>

    <label for="message">Message</label>
    <textarea name="message" id="message" rows="6" required></textarea>

    <button type="submit">Send Message</button>
  </form>

  <p style="margin-top: 2rem;">
    📧 Or reach out directly via <a href="mailto:amrutagandhe@gmail.com">email</a> or connect on
    <a href="https://www.linkedin.com/in/amruta-gandhe-1b1013207/">LinkedIn</a>.
  </p>
</div>
