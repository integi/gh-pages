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
    alt: "Potwierdzona aktualnymi certyfikatami znajomość systemów Comarch ERP
          <br><br>Jesteśmy partnerem Comarch."      

feature_row: - image_path: assets/images/integration.svg image_w: 64 image_h: 64 alt: "Wdrożenia i integracje systemów ERP" title: "Wdrożenia i integracje" excerpt: "Wdrażamy i rozwijamy systemy ERP w oparciu o rzeczywiste potrzeby oraz procesy zachodzące w firmie. Integrujemy je z aplikacjami zewnętrznymi, platformami sprzedażowymi, systemami magazynowymi i innymi źródłami danych, ograniczając ręczną pracę oraz ryzyko błędów." - image_path: assets/images/code.svg image_w: 64 image_h: 64 alt: "Dedykowane oprogramowanie dla firm" title: "Oprogramowanie dedykowane" excerpt: "Tworzymy aplikacje, rozszerzenia i mechanizmy automatyzujące pracę tam, gdzie standardowe funkcje systemu nie są wystarczające. Projektujemy rozwiązania dopasowane do specyfiki firmy, jej procedur oraz wykorzystywanego środowiska informatycznego." - image_path: assets/images/support.svg image_w: 64 image_h: 64 alt: "Wsparcie i rozwój systemów ERP" title: "Wsparcie i rozwój" excerpt: "Zapewniamy wsparcie techniczne i merytoryczne użytkowników systemów ERP. Pomagamy w konfiguracji, rozwiązywaniu problemów, optymalizacji procesów oraz dalszym rozwoju wdrożonych rozwiązań wraz ze zmieniającymi się potrzebami firmy."
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
{% comment %}
{% include feature_row id="comarchxt" type="left" %}
{% include feature_row id="comarchopt" type="right" %}
{% include feature_row id="comarchxl" type="left" %}
{% endcomment %}

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

