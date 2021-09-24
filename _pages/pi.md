---
title: "Platforma Integracyjna"
layout: splash
permalink: /pi/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image.png
---
<h1>Platforma integracyjna</h1>

Platforma integracyjna jest narzędziem, którego zadaniem jest dostarczyć różne mechanizmy integracyjne zachowując jednolity interfejs użytkownika w myśl zasady "jedna by wszystkimi zarządzać". 

Przy realizacjach wdrożeń mamy doczynienia z importerami i eksporterami danych z bardzo prostym interfejsem użytkownika. Każdy z mechanizmów wymaga sporządzenia osobnych założeń, konfiguracji oraz napisania aplikacji. Każdy z programistów podchodzi do projektowania interfejsu indywidualnie, tak naprawdę na nowo starając się wymyślić koło. Rodzi to problem zarządzania kodami źródłowymi oraz dokumentowania zmian, gdyż każda aplikacja może być napisana w różnych językach, technologiach, stosując różne wzorce i standardy kodowania. Ponadto z punktu widzenia użytkownika końcowego obsługa wielu aplikacji jest niekorzystna i może powodować dodatkowe błędy podczas pracy. 

Celem Platformy Integracyjnej jest ustandaryzowanie działań dostarczając jedną aplikację z interfejsem użytkownika - tak aby programista mógł skupić się tylko na projektowaniu logiki biznesowej importera / eksportera. Programista dostarczałby tylko plik "paczki" - na zasadzie wtyczki do aplikacji. Zyska z tej operacji jest taki, że posiadając tą samą aplikacje można dostarczyć wiele wtyczek realizujących różną logikę biznesową. Jedna wtyczka może realizować import not memoriałowych, inna może eksportować zamówienia, jeszcze inna wczytywać wyciągi bankowe. W wypadku zmian założeń nie trzeba kompilować całej aplikacji, a wyłącznie plik wtyczki. Ponadto umożliwia to dostarczanie gotowych rozwiązań do innych klientów bez dodatkowych kosztów związanych z przepisywaniem całego projektu na nowo, a tylko dostosowaniem wtyczki do indywidualnych potrzeb. 

Instalacja wtyczek jest bardzo prosta wystarczy tylko przeciagną plik z rozszerzeniem .integi do okna aplikacji, a program sam ją załaduje.

{% include figure image_path="/assets/gifs/pi_instalacja_wtyczek.gif" alt="Instalacja wtyczek" caption="Instalacja wtyczek"  %}

Każda z wtyczek posiada swoją bazową implementację, która składa się z podglądu zdarzeń, widoku (gdy potrzeba oprogramować dodatkowy interfejs) oraz ustawień.
Z prawej strony znajdują się wystajace ikony, które odpowiadaja za interakcje z wtyczką (w poniższym przykładzie są to ikony Uruchom oraz ikona Wskazania pliku).

{% include figure image_path="/assets/gifs/pi_uruchamianie_wtyczek.gif" alt="Interfejs wtyczki" caption="Interfejs wtyczki"  %}

W trakcie działania wtyczki użytkownik na bieżąco otrzymuje komunikaty o działaniu aplikacji. Użytkownik ma również możliwość filtrowania zdarzeń po piktogramach i frazie zawartej w komunikacie.

{% include figure image_path="/assets/gifs/pi_filtrowanie_komunikatow.gif" alt="Podgląd zdarzeń" caption="Podgląd zdarzeń" %}

Narzędzie jest w dalszym ciągu udoskonalane, a nowe funkcjonalności są wprowadzane zgodnie z potrzebami klientów.