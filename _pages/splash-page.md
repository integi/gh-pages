---
title: "Integi Wojciech Kurpanik"
layout: splash
permalink: /
override_splash: true

intro: 
  - excerpt: 'Wśród firm wdrożeniowych krąży stare porzekadło:
              <br><br><b><i>"Nie ma złych systemów ERP, są tylko lepiej lub gorzej wdrożone"</i></b>.
              <br><br>Jeżeli masz problem z aktualną obsługą systemu, potrzebujesz pomocy przy wdrożeniu lub usprawnieniu procesów w Twojej firmie skontaktuj się z Nami.
              <br><br>Jesteśmy partnerem Comarch.'
  - image_path: assets/images/partner.png
    image_w: 180
    image_h: 120
    alt: "Potwierdzona aktualnymi certyfikatami znajomość systemów Comarch ERP"
          <br><br>Jesteśmy partnerem Comarch.'
    image_path: assets/images/partner.png


feature_row:
  - image_path: assets/images/integration.svg
    image_w: 64
    image_h: 64
    alt: "integracja"
    title: "Wdrożenia i integracje"
    excerpt: "Wdrażamy systemy ERP dostosowując je do potrzeb Twojego biznesu. Integrujemy istniejące rozwiązania z systemami ERP."
    #url: "#test-link"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
  - image_path: assets/images/code.svg
    image_w: 64
    image_h: 64
    alt: "programowanie"
    title: "Programowanie"
    excerpt: "Tworzymy nowoczesne aplikacje bazodanowe pod konkretne branże, wykorzystując do tego najlepsze technologie i standardy kodowania."
    #url: "#test-link"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
  - image_path: assets/images/support.svg
    image_w: 64
    image_h: 64
    alt: "obsługa"
    title: "Pomoc"
    excerpt: "Oferujemy wsparcie techniczne oraz doradztwo w zakresie konfiguracji, wdrożenia i obsługi systemów ERP."
    #url: "#test-link"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
comarchxt: 
  - image_path: assets/images/XT_mockup_logo.png
    image_w: 1920
    image_h: 1080
    alt: "Comarch ERP XT"
    title: "Comarch ERP XT"
    excerpt: "Comarch ERP XT to program do sprawnego fakturowania online, kontroli magazynu, prowadzenia księgowości (KPiR i pełnej księgowości), raportowania oraz prowadzenia e-sklepu przeznaczony <b>dla mikro i małych firm</b>. W zależności od Twoich potrzeb możesz wybrać i płacić za te usługi, których potrzebujesz."
    #url: "erpxt/"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
comarchopt:
  - image_path: assets/images/OPT_mockup_logo.png
    image_w: 1920
    image_h: 1042
    alt: "Comarch ERP OPTIMA"
    title: "Comarch ERP OPTIMA"
    excerpt: "Comarch ERP Optima to najpopularniejszy w Polsce program przeznaczony <b>dla małych i średnich firm</b> z każdej branży. Dzięki modułom dedykowanym każdemu obszarowi biznesowemu (faktury, płace, kasa/bank, sprzedaż, handel z magazynem itd.) jest optymalnym systemem ERP do zarządzania firmą."
    #url: "erpoptima/"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
comarchxl:
  - image_path: assets/images/XL_mockup_logo.png
    image_w: 1920
    image_h: 1042
    alt: "Comarch ERP XL"
    title: "Comarch ERP XL"
    excerpt: "Comarch ERP XL to rozbudowany funkcjonalnie system klasy ERP przeznaczony <b>dla średnich i dużych firm</b>. Charakteryzuje się elastyczną budową modułową. Funkcjonalności systemu zgrupowane są w kilkunastu współpracujących ze sobą obszarach. Optymalna konfiguracja i ilość modułów dobierana jest na podstawie wnikliwej analizy potrzeb i specyfiki funkcjonowania firmy."
    #url: "erpxl/"
    #btn_label: "Więcej"
    #btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
{% include feature_row id="comarchxt" type="left" %}
{% include feature_row id="comarchopt" type="right" %}
{% include feature_row id="comarchxl" type="left" %}

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
    <label for="full-name">Imię i nazwisko</label>
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

