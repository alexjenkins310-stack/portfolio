---
layout: default
title: Contact
permalink: /contact/
---

<section class="page-header contact-header">
  <p class="eyebrow">Contact</p>
  <h1>Let's start a conversation.</h1>
  <p class="lede">Whether you would like to discuss a professional opportunity, a project, or a shared interest in finance and accounting, I would be glad to hear from you.</p>
</section>

<section class="section contact-section" id="contact">
  <div class="contact-layout">
    <div class="card contact-form-card">
      <h2>Send a message</h2>
      <p>Complete the form below and I will respond as soon as possible.</p>

      <form class="contact-form" action="https://formspree.io/f/mzdnoovo" method="POST" target="_blank" rel="noopener">
        <div class="form-field">
          <label for="contact-name">Name</label>
          <input id="contact-name" name="name" type="text" autocomplete="name" required>
        </div>

        <div class="form-field">
          <label for="contact-email">Email</label>
          <input id="contact-email" name="email" type="email" autocomplete="email" required>
        </div>

        <div class="form-field">
          <label for="contact-subject">Subject</label>
          <input id="contact-subject" name="subject" type="text" required>
        </div>

        <div class="form-field">
          <label for="contact-message">Message</label>
          <textarea id="contact-message" name="message" required></textarea>
        </div>

        <div class="form-honeypot" aria-hidden="true">
          <label for="contact-website">Leave this field blank</label>
          <input id="contact-website" name="_gotcha" type="text" tabindex="-1" autocomplete="off">
        </div>

        <button class="button contact-submit" type="submit">Send Message</button>
      </form>
    </div>

    <aside class="contact-sidebar" aria-label="Additional contact information">
      <article class="card contact-card">
        <h3>Email</h3>
        <p><a href="mailto:alex.jenkins310@gmail.com">alex.jenkins310@gmail.com</a></p>
      </article>
      <article class="card contact-card">
        <h3>LinkedIn</h3>
        <p><a href="https://www.linkedin.com/in/alexjenkins04" target="_blank" rel="noopener noreferrer">linkedin.com/in/alexjenkins04</a></p>
      </article>
      <article class="card contact-card">
        <h3>Graduation</h3>
        <p>May 2027</p>
      </article>
      <article class="card contact-card">
        <h3>Geographic Availability</h3>
        <p>Willing to relocate.</p>
      </article>
    </aside>
  </div>
</section>
