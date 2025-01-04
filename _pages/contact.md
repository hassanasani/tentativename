---
permalink: /contact/
title: "Contact Us"
layout: single
---

## We'd Love to Hear From You!

Please fill out the form below to get in touch with us.

<form action="https://formspree.io/f/your_form_id" method="POST">
  <label for="name">Your Name:</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Your Email:</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="reason">Reason for Contact:</label><br>
  <select id="reason" name="reason" required>
    <option value="">Select an option</option>
    <option value="general">General Inquiry</option>
    <option value="collaboration">Collaboration</option>
    <option value="support">Support</option>
    <option value="other">Other</option>
  </select><br><br>

  <label for="phone">Phone Number (Optional):</label><br>
  <input type="tel" id="phone" name="phone"><br><br>

  <label for="message">Your Message:</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <button type="submit">Send Message</button>
</form>

<style>
  form {
    max-width: 600px;
    margin: 0 auto;
    font-family: Arial, sans-serif;
  }
  label {
    font-weight: bold;
    margin-top: 10px;
    display: block;
  }
  input, select, textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  button {
    background-color: #007BFF;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  button:hover {
    background-color: #0056b3;
  }
</style>

