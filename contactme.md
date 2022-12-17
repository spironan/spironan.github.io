---
layout: page
title: Contact Me
subtitle: Here's how you can reach out to me!
social-share: false
---
<style>
/* .form__input {
  border: 2px solid black;
  border-radius: 12px;
  padding: 5px;
} */
:root {
  --heading-font-color: : rgb(17, 16, 22);
  --background-alt-color: #ffffff;
  --dark: #000000;
  --button-background-color: DarkCyan;
}

.form-box {
  margin-bottom: 100px;
}
.form__group {
  margin-bottom: 20px;
}
.form__input {
  width: 100%;
  padding: 20px;
  font-size: 16px;
  font-weight: 400;
  border: 2px solid black;
  border-radius: 12px;
  outline: 0;
  transition: .2s ease-in-out;
  resize: vertical;
  color: var(--heading-font-color);
  background-color: var(--background-alt-color);
}
.screen-reader-text {
  clip: rect(1px, 1px, 1px, 1px);
  height: 1px;
  overflow: hidden;
  position: absolute !important;
  width: 1px;
  word-wrap: normal !important;
}

.button--primary {
  color: var(--dark);
  background-color: var(--button-background-color);
  font-weight: bold;
}

.button {
  padding:20px;
  border-radius: 12px;
  border: none;
    border-top-color: currentcolor;
    border-top-style: none;
    border-top-width: medium;
    border-right-color: currentcolor;
    border-right-style: none;
    border-right-width: medium;
    border-bottom-color: currentcolor;
    border-bottom-style: none;
    border-bottom-width: medium;
    border-left-color: currentcolor;
    border-left-style: none;
    border-left-width: medium;
    border-image-outset: 0;
    border-image-repeat: stretch;
    border-image-slice: 100%;
    border-image-source: none;
    border-image-width: 1;
  text-decoration: none;
    text-decoration-line: none;
    text-decoration-style: solid;
    text-decoration-color: currentcolor;
    text-decoration-thickness: auto;
}
</style>

<div class="form-box">
  <!-- <div class="contact-head">
    {% if site.data.settings.contact.description %}
      <p class="contact-description">{{site.data.settings.contact.description}}</p>
    {% endif %}
  </div> -->
  <form class="form" action="https://getform.io/f/1b03ecc4-13c8-45fb-8a71-4c2162a779a5" method="post" enctype="multipart/form-data" target="_blank">
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-name"></label>
      <input class="form__input" id="form-name" type="text" name="name" placeholder="Name" required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-email"></label>
      <input class="form__input" id="form-email" type="email" name="email" placeholder="Email" required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-text"></label>
      <textarea class="form__input" id="form-text" name="message" rows="10" placeholder="Message" required></textarea>
    </div>
    <!-- <div class="g-recaptcha" data-sitekey="6LewWJQeAAAAANq6ile3eaEPiFIJamg59yXFHRBY"></div><br /> -->
    <div class="form__group">
      <button class="button button--primary" type="submit">Send Message</button>
    </div>
  </form>
</div> 