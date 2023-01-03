---
title: "Contacte"
draft: false
weight: 3
---

Envia'm un missatge directament i et respondré per correu electrònic.

<form name="contact" class="column is-three-fifths is-offset-one-fifth" action="/gracies/" method="POST" data-netlify="true" netlify-honeypot="subject">
    <input type="hidden" name="form-name" value="contact" />
    <!-- Honeypot -->
    <div class="hidden">
        <label class="" for="subject"></label>
        <div class="">
            <input id="contact-form-subject" name="subject" type="text" placeholder="Subject" class="" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="field">
        <label class="label" for="Nom"></label>
        <div class="control">
            <input id="contact-form-name" name="Nom" type="text" placeholder="Nom" class="input" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="field">
        <label class="label" for="Email"></label>
        <div class="control">
            <input id="contact-form-email" name="Email" type="email" placeholder="Adreça email" class="input" required="" autocomplete="off">
        </div>
    </div>
    <!-- Phone input-->
    <div class="field">
        <label class="label" for="Telefon"></label>
        <div class="control">
            <input id="contact-form-phone" name="Telefon" type="tel" placeholder="Telèfon" class="input" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div class="field">
        <label class="label" for="Missatge"></label>
        <textarea class="textarea" id="contact-form-message" name="Missatge" placeholder="Escriu el teu missatge..." rows="8"></textarea>
    </div>
    <!-- Button -->
    <div class="field">
        <button type="submit" class="button" value="Submit" id="Form-submit">Envia</button>
    </div>
</form>

**Telèfon:**

<span class="telf-big">609120101</span>