---
title: "Contact"
date: 2025-10-10
toc: false
socialShare: false
tags: []
author: ""
enableReadingTime: false
hideMeta: true
---

<form action="https://formspree.io/f/mjkaarkk" method="POST" class="container px-3 px-sm-5 px-md-5 px-lg-5">
  <!-- Redirect after success -->
  <input type="hidden" name="_next" value="/nl/bedankt/">
  <!-- Email subject in notification -->
  <input type="hidden" name="_subject" value="Nieuw bericht van sc-analytics">

  <!-- Honeypot (spam trap) -->
  <div class="d-none" aria-hidden="true">
    <label>Laat dit veld leeg</label>
    <input type="text" name="_gotcha" tabindex="-1" autocomplete="off">
  </div>

  <div class="mb-3">
    <label for="name" class="form-label">Uw naam</label>
    <input id="name" name="name" type="text" class="form-control" required autocomplete="name">
  </div>

  <div class="mb-3">
    <label for="email" class="form-label">Uw e-mail</label>
    <input id="email" name="email" type="email" class="form-control" required autocomplete="email">
  </div>

  <div class="mb-3">
    <label for="message" class="form-label">Uw bericht</label>
    <textarea id="message" name="message" class="form-control" rows="6" required></textarea>
  </div>

  <!-- Optional GDPR consent -->
  <div class="form-check mb-3">
    <input class="form-check-input" type="checkbox" id="consent" name="consent" required>
    <label class="form-check-label" for="consent">
      Ik ga akkoord om gecontacteerd te worden over deze vraag.
    </label>
  </div>

  <button type="submit" class="btn">Verstuur</button>
</form>
