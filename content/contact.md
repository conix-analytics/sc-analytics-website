---
title: "Contact"
date: 2025-10-10
---


<form action="https://formspree.io/f/mjkaarkk" method="POST" class="container px-3 px-sm-5 px-md-5 px-lg-5">
  <!-- Redirect after success -->
  <input type="hidden" name="_next" value="/thanks/">
  <!-- Email subject in notification -->
  <input type="hidden" name="_subject" value="New message from sc-analytics">

  <!-- Honeypot (spam trap) -->
  <div class="d-none" aria-hidden="true">
    <label>Leave this field empty</label>
    <input type="text" name="_gotcha" tabindex="-1" autocomplete="off">
  </div>

  <div class="mb-3">
    <label for="name" class="form-label">Your name</label>
    <input id="name" name="name" type="text" class="form-control" required autocomplete="name">
  </div>

  <div class="mb-3">
    <label for="email" class="form-label">Your email</label>
    <input id="email" name="email" type="email" class="form-control" required autocomplete="email">
  </div>

  <div class="mb-3">
    <label for="message" class="form-label">Your message</label>
    <textarea id="message" name="message" class="form-control" rows="6" required></textarea>
  </div>

  <!-- Optional GDPR consent -->
  <div class="form-check mb-3">
    <input class="form-check-input" type="checkbox" id="consent" name="consent" required>
    <label class="form-check-label" for="consent">
      I consent to being contacted about this inquiry.
    </label>
  </div>

  <button type="submit" class="btn">Send</button>
</form>
