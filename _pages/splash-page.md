---
title: "Platforma Integracyjna"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image.png
  actions:
    - label: "Dowiedz się więcej"
      url: "/pi/"
  caption: "NOWY PRODUKT"
excerpt: "Uniwersalne rozwiązanie dedykowane dla systemów ERP do importu i eksport danych."
intro: 
  - excerpt: 'Wśród firm wdrożeniowych krąży stare porzekadło:
              <br><br><b><i>"Nie ma złych systemów ERP, są tylko lepiej lub gorzej wdrożone"</i></b>.
              <br><br>Jeżeli masz problem z aktualną obsługą systemu, potrzebujesz pomocy przy wdrożeniu lub usprawnieniu procesów w Twojej firmie skontaktuj się z Nami.'

feature_row:
  - image_path: assets/images/integration.svg
    image_w: 64
    image_h: 64
    alt: "integracja"
    title: "Wdrożenia i integracje"
    excerpt: "Wdrażamy systemy ERP dostosowując je do potrzeb Twojego biznesu. Integrujemy istniejące rozwiązania z systemami ERP."
    url: "#test-link"
    btn_label: "Więcej"
    btn_class: "btn--primary"
  - image_path: assets/images/code.svg
    image_w: 64
    image_h: 64
    alt: "programowanie"
    title: "Programowanie"
    excerpt: "Tworzymy nowoczesne aplikacje bazodanowe pod konkretne branże, wykorzystując do tego najlepsze technologie i standardy kodowania."
    url: "#test-link"
    btn_label: "Więcej"
    btn_class: "btn--primary"
  - image_path: assets/images/support.svg
    image_w: 64
    image_h: 64
    alt: "obsługa"
    title: "Pomoc"
    excerpt: "Oferujemy wspracie techniczne oraz doradstwo w zakresie konfiguracji, wdrożenia i obsługi systemów ERP."
    url: "#test-link"
    btn_label: "Więcej"
    btn_class: "btn--primary"
contact:
  - #image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "Kontakt"
    title: "Kontakt"
    excerpt: "Wdrażamy systemy ERP dostosowując je do potrzeb Twojego biznesu. Integrujemy istniejące rozwiązania z systemami ERP."
  - alt: "Formularz kontaktowy"
    title: "Formularz kontaktowy"
    excerpt: "Formularz kontaktowy"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row %}

<h3>Formularz kontaktowy:</h3>
<script>
// javascript
window.onload = function() { 
  var el = document.getElementById('g-recaptcha-response'); 
  if (el) { 
    el.setAttribute('required', 'required'); 
  } 
}
</script>

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mleazawe" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Imię i Nazwisko</label>
    <input type="text" name="name" id="full-name" placeholder="imię i nazwisko" required="">
    <label for="email-address">Adres e-mail</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domena.pl" required="">
    <label for="message">Wiadomość</label>
    <textarea rows="5" name="message" id="message" placeholder="tekst wiadomości" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Wiadomość z integi.pl">
  </fieldset>
  <div class="g-recaptcha" data-sitekey="6LdmEoMcAAAAAKbg4gCnuwMoT-9Td64sjtXs9Xik"></div>
  <br/>
  <input type="submit" value="Wyślij">
</form>