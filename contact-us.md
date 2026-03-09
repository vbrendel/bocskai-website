---
layout: page
title: Contact Us
subtitle: We'd love to hear from you. Get in touch about enrolments, classes, events or anything else.
description: Contact the Bocskai Hungarian School in Melbourne. Phone, email, or use our online contact form.
permalink: /contact-us/
---

<section class="section">
  <div class="container">
    <div class="contact-grid">

      <!-- Contact Info -->
      <div class="contact-info">
        <span class="section-label">Get In Touch</span>
        <h2>We're Here to Help</h2>
        <p style="color:var(--color-text-light);margin-bottom:2rem;">
          Whether you have questions about enrolments, classes, the library or upcoming events —
          don't hesitate to reach out. We aim to respond within 2 business days.
        </p>

        <div class="contact-item">
          <div class="contact-icon">📍</div>
          <div class="contact-detail">
            <strong>Address</strong>
            <p>
              Bocskai Community Centre<br>
              123 St Georges Road (corner of Watkins St)<br>
              Fitzroy North (Melbourne), VIC 3068
            </p>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-icon">📞</div>
          <div class="contact-detail">
            <strong>Phone</strong>
            <p><a href="tel:0408950491">0408 950 491</a></p>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-icon">✉️</div>
          <div class="contact-detail">
            <strong>Email</strong>
            <p><a href="mailto:bocskaischool@gmail.com">bocskaischool@gmail.com</a></p>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-icon">🌐</div>
          <div class="contact-detail">
            <strong>Website</strong>
            <p><a href="{{ site.url }}">www.bocskaihungarianschool.com.au</a></p>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-icon">📘</div>
          <div class="contact-detail">
            <strong>Facebook</strong>
            <p>
              <a href="{{ site.facebook_url }}" target="_blank" rel="noopener">
                Join our Facebook community group
              </a>
            </p>
          </div>
        </div>

        <div style="margin-top:2rem;padding:1.25rem;background:var(--color-bg-light);border-radius:8px;font-size:.9rem;">
          <strong>Class Schedule</strong><br>
          <span style="color:var(--color-text-light);">
            Classes run every second Sunday, 9:00am – 12:30pm.<br>
            We follow the Victorian school term calendar.
          </span>
        </div>

        <!-- Map placeholder -->
        <div class="map-placeholder">
          <span>📍</span>
          <span>
            123 St Georges Road, Fitzroy North VIC 3068<br>
            <small>Embed a Google Map here</small>
          </span>
        </div>
      </div>

      <!-- Contact Form -->
      <div class="contact-form">
        <h2 style="margin-bottom:0.25rem;">Send Us a Message</h2>
        <p style="color:var(--color-text-light);font-size:.9rem;margin-bottom:1.5rem;">
          Fill in the form below and we'll get back to you as soon as possible.
        </p>

        <form action="https://formspree.io/f/your-form-id" method="POST" novalidate>

          <div class="form-group">
            <label for="name">Full Name *</label>
            <input type="text" id="name" name="name" required placeholder="Your full name">
          </div>

          <div class="form-group">
            <label for="email">Email Address *</label>
            <input type="email" id="email" name="email" required placeholder="your@email.com">
          </div>

          <div class="form-group">
            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" placeholder="04xx xxx xxx">
          </div>

          <div class="form-group">
            <label for="subject">Subject</label>
            <select id="subject" name="subject">
              <option value="">Select a topic…</option>
              <option value="enrolment">Enrolment enquiry</option>
              <option value="classes">Class information</option>
              <option value="library">Library</option>
              <option value="events">Events &amp; community</option>
              <option value="volunteer">Volunteering</option>
              <option value="other">Other</option>
            </select>
          </div>

          <div class="form-group">
            <label for="message">Message *</label>
            <textarea id="message" name="message" required placeholder="How can we help you?"></textarea>
          </div>

          <button type="submit" class="btn btn-primary" style="width:100%;">Send Message</button>

        </form>
      </div>

    </div>
  </div>
</section>

<section class="section section-light">
  <div class="container text-center">
    <span class="section-label">Online Community</span>
    <h2>Connect on Social Media</h2>
    <p style="color:var(--color-text-light);max-width:500px;margin:0 auto 2rem;">
      Become an active member of our online community. Follow us on Facebook for the
      latest school news, event photos and community updates.
    </p>
    <a href="{{ site.facebook_url }}" target="_blank" rel="noopener" class="facebook-btn">
      Join Our Facebook Group
    </a>
  </div>
</section>
