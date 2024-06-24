---
title: "Co nowego w WCAG 2.1"
nav_title: "Nowe w  2.1"

description: Ta strona przedstawia listę nowych kryteriów sukcesu w Wytycznych dla dostępności treści internetowych (WCAG) 2.1. Zawiera ona cytaty z person (fikcyjnych osób), które pomagają zrozumieć niektóre aspekty kryteriów sukcesu.

teaser_text: WCAG 2.1 ma 17 dodatkowych wymagań („kryteriów sukcesu”), które odnoszą się do dostępności mobilnej, osób słabowidzącyvh oraz osób z problemami poznawczymi i trudnościami w uczeniu się. Strona Co nowego w WCAG 2.1 przedstawia nowe kryteria sukcesu. Zawiera ona cytaty z person, które pomagają zrozumieć te kwestie.

lang: pl
last_updated: 2024-02-28
permalink: /standards-guidelines/wcag/new-in-21/pl

translators:
  - name: "Stefan Wajda"
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-21.pl.md'

image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Data:</strong> Uaktualniono 5 października 2023.</p>
  <p><strong>Redaktor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Współpraca: Shadi Abou-Zahra, Jonathan Avila, Brent Bakken, Laura Carlson, Stéphane Deschamps, Eric Eggert, James Green, Becky Gibson, Marc Johlic, Robert Jolly, Howard Kramer, Chris O'Brien, Sharron Rush, Nic Steenhout, Glenda Sims, Bill Tyler.</p>
  <p>Opracowane z udziałem Grupy Roboczej ds. Edukacji i Promocji (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) oraz Grupy Roboczej ds. Wytycznych dla Dostępności (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin-right: 0; margin-bottom:40px;}
  .quotes {margin-bottom:40px;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row;}
  .quotes li>p span {display:table-cell;}
  .issue {font-weight: bold; display:table-cell; width: 6em;}
  q:before {content: open-quote;color: #005a6a;font-weight: bold;}
  q:after {content: close-quote;color: #005a6a;font-weight: bold;}
  .sc dt {
    display: list-item;
    list-style-type: disc;
    float: left;
    font-weight: bold;
    margin-left: 2em;
    margin-right: 1ex;
    margin-top: 0;
  }
  .sc dt:after {
    content: ":";
  }
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
ref: /standards-guidelines/wcag/new-in-21/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Podsumowanie" class="full" %}
{:/}

Ta strona przedstawia nowe kryteria sukcesu w Wytycznych dla dostępności treści internetowych (WCAG) 2.1.

**Zawiera ona cytaty z person (fikcyjnych osób)**, które pomagają zrozumieć niektóre aspekty kryteriów sukcesu. Ponadto znajdują się tu łącza do dokumentów objaśniających szczegółowo kryteria sukcesu i zawierających więcej przykładów.



{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}

{::nomarkdown}
{% include toc.html type="start" title="Treść strony" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Wprowadzenie

Wprowadzenie do Wytycznych dla dostępności treści internetowych (WCAG) i więcej informacji na temat wersji 2.0, 2.1 i 2.2 można znaleźć w artykule [Omówienie WCAG](/standards-guidelines/wcag/pl).

WCAG 2.1 wprowadza 17 dodatkowych kryteriów sukcesu, które dotyczą

- [dostępności mobilnej](/standards-guidelines/mobile/)
- osób słabowidzących
- [osób z problemami poznawczymi i trudnościami w uczeniu się](/cognitive/)

## Wytyczna 1.3 Możliwość adaptacji

Twórz treści, które mogą być prezentowane na różne sposoby bez utraty informacji czy struktury.

### 1.3.4 Orientacja (AA)

<blockquote class="sc">
  <p>Treść nie ogranicza swojego widoku i działania do jednej orientacji wyświetlania, takiej jak pionowa lub pozioma, chyba że określona orientacja wyświetlania jest <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-istotna">istotna</a>.</p>
</blockquote>
<p class="persona">Komik z porażeniem mózgowym poruszający się na wózku inwalidzkim:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Nie mogę obrócić tabletu – jest przymocowany do wózka inwalidzkiego.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Aplikacja działa niezależnie od tego, czy podłączę tablet poziomo, czy pionowo.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/orientation.html">Objaśnienie KS Orientacja</a></p>

### 1.3.5 Określenie pożądanej wartości (AA)

<blockquote class="sc">
  <p>Cel każdego pola zbierającego informacje o użytkowniku może być <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-programowo-okreslone">programowo określony</a>, gdy:</p>
  <ul>
    <li>Pole zbierające dane służy celowi określonemu w sekcji <a href="https://www.w3.org/Translations/WCAG21-pl/#input-purposes">Przeznaczenie pól danych w komponentach interfejsu użytkownika</a>; oraz</li>
    <li>Treść jest implementowana za pomocą technologii obsługującej określanie w polach formularza typu oczekiwanych danych.</li>
  </ul>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Asystentka w supermarkecie</a> z dysleksją i dyskalkulią:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Mój adres jest bardzo skomplikowany. Jest mnóstwo liczb i długich słów. Trudno to wszystko przepisać bez popełniania błędów.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Uwielbiam strony internetowe, które mogą automatycznie wypełnić to wszystko za mnie. Wtedy nie muszę tak ciężko pracować, aby uzyskać poprawną pisownię i liczby.</q><br/>
      <em>Uwaga: </em> to działa, ponieważ pola używają autouzupełniania. </span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html">Objaśnienie KS Określenie pożądanej wartości</a></p>

### 1.3.6 Określenie przeznaczenia (AAA)

<blockquote class="sc">
  <p>W treściach zaimplementowanych przy użyciu języków znaczników przeznaczenie <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-komponentu-interfejsu-uzytkownika">komponentów interfejsu użytkownika</a>, ikon i <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-obszaru-kluczowego">obszarów kluczowych/a> może zostać <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-programowo-okreslone">określone programowo</a>.</p>
</blockquote>
<p class="persona">Gracz z zaburzeniami przetwarzania języka:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Mam oprogramowanie, które zamienia słowa w nawigacji na symbole. W przypadku niektórych stron internetowych w ogóle to nie działa.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Z niektórymi stronami internetowymi działa całkiem nieźle.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/identify-purpose.html">Objaśnienie KS Określenie przeznaczenia</a></p>

## Wytyczna 1.4 Rozróżnialność

Ułatwiaj oglądanie i słuchanie treści oraz oddzielanie informacji od tła.

### 1.4.10 Dopasowanie do ekranu (AA)

<blockquote class="sc">
  <p>Treść może być prezentowana bez utraty informacji lub funkcjonalności, bez konieczności przewijania w dwóch wymiarach dla:</p>
  <ul>
    <li>Pionowego przewijania treści o szerokości odpowiadającej 320 <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-pikselom-css">pikselom CSS;</a>;</li>
    <li>Poziomego przewijania treści na wysokości odpowiadającej 256 <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-pikselom-css">pikselom CSS</a>;</li>
  </ul>
  <p>Wyjątkiem są te części treści, które wymagają dwuwymiarowego układu ze względu na sposób używania lub znaczenie.</p>
  
</blockquote>
<p class="persona">Rodzic słabowidzący – 20/400:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Czytanie tekstu jest prawie niemożliwe, jeśli muszę przewijać w prawo i w lewo, aby przeczytać każdą linię. To dezorientujące i tracę orientację. Utrudnia to zrozumienie tego, co czytam.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Zwiększyłem rozmiar tekstu o 400%, a tekst został ponownie wyświetlony w szerokości okna. Mogę go łatwo przeczytać bez przewijania w przód i w tył.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/reflow.html">Objaśnienie KS Dopasowanie do ekranu</a></p>

### 1.4.11 Kontrast elementów nietekstowych (AA)

<blockquote class="sc">
  <p>Wizualna <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-prezentacja" data-link-type="dfn">prezentacja</a> następujących elementów ma <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-wspo-czynnikiem-kontrastu" data-link-type="dfn">współczynnik kontrastu</a> co najmniej 3:1 względem sąsiednich kolorów:</p>
  <dl>
    <dt>Komponenty interfejsu użytkownika</dt>
    <dd>Informacje wizualne wymagane do identyfikacji <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-komponentu-interfejsu-uzytkownika" data-link-type="dfn">komponentów interfejsu użytkownika</a> i ich <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-stanow" data-link-type="dfn">stanów</a>, z wyjątkiem nieaktywnych składników lub gdy wygląd komponentu jest określony przez agenta użytkownika i nie jest modyfikowany przez autora;</dd>
    <dt>Obiekty graficzne</dt>
    <dd>Części grafiki wymagane do zrozumienia treści, z wyjątkiem sytuacji, gdy konkretna prezentacja grafiki ma <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-istotna" data-link-type="dfn">istotne</a> znaczenie dla przekazywanych informacji.</dd>
  </dl>
  
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Senior</a> z małą wrażliwością na kontrast::</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Nie mogłem użyć »Formularza zamówienia« — nie było pól tekstowych. Po długiej rozmowie z działem obsługi klienta dowiedziałem się, że obramowania pól tekstowych były zbyt jasne, bym mógł je zobaczyć.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Łatwo jest mi zobaczyć wszystkie ikony, przyciski i wszystko — nawet w świetle słonecznym.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html">Objaśnienie KS Kontrast elementów nietekstowych</a></p>

### 1.4.12 Odstępy w tekście (AA)

<blockquote class="sc">
  <p>W treściach tworzonych za pomocą języków znaczników, umożliwiających ustawienie poniższych <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-w-asciwosci-stylu" data-link-type="dfn">właściwości stylu</a>, nie następuje utrata żadnych treści lub funkcjonalności, gdy <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-tekstu" data-link-type="dfn">tekst</a> ustawiony zostanie tak, aby uwzględniał wszystkie poniższe parametry oraz gdy wprowadzone zostaną zmiany w jakiejkolwiek innej właściwości stylu:</p>
  <ul>
    <li>Wysokość linii (odstęp między wierszami) do co najmniej 1,5-krotności rozmiaru czcionki;</li>
    <li>Odstęp między akapitami co najmniej 2 razy większy od rozmiaru czcionki;</li>
    <li>Odstępy między literami (tracking) do co najmniej 0,12-krotności rozmiaru czcionki;</li>
    <li>Odstępy między wyrazami do co najmniej 0,16 wielkości czcionki.</li>
  </ul>
  <p>Wyjątek: Języki naturalne i skrypty, które nie wykorzystują jednej lub więcej z tych właściwości stylu tekstowego w tekście pisanym, mogą być zgodne przy użyciu tylko tych właściwości, które istnieją dla tej kombinacji języka i skryptu.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent">Student</a> z dysleksją:<br/>
  oraz <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Senior</a> ze słabym wzrokiem:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Większość tekstu jest trudna do odczytania. Jest tak zaśmiecony, że nie mogę się skupić. Samo zwiększenie odstępów między wierszami robi różnicę. Kiedy jestem naprawdę zmęczony, zwiększam również odstępy między słowami. Jednak niektóre strony internetowe nie działają poprawnie — część tekstu zostaje ucięta, a nawet przyciski znikają.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>OK, wiem, że jestem trochę maniakiem, ale udoskonaliłem arkusz stylów użytkownika, aby odstępy w tekścir były dla mnie odpowiednie. To ulga, gdy strony internetowe dobrze współpracują z moim CSS.</q></span></p></li>
  </ul>
</div>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/text-spacing.html">Objaśnienie KS Odstępy w tekście</a>

### 1.4.13 Treść spod kursora lub fokusu (AA)

<blockquote class="sc">
  <p>Gdy jakaś treść staje się widoczna po otrzymaniu kursora lub fokusu klawiatury, a po ich usunięciu znika, spełnione są poniższe warunki:</p>
  <dl>
    <dt>Odrzucone</dt>
    <dd>Istnieje a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-mechanizmu" data-link-type="dfn">mechanizm</a> umożliwiający odrzucenie dodatkowej treści bez przesuwania wskaźnika myszy lub fokusu klawiatury, chyba że dodatkowa treść przekazuje <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-b-ad-wprowadzonych-danych" data-link-type="dfn">błąd wprowadzanych danych</a> lub nie przesłania ani nie zastępuje innej treści;</dd>
    <dt>Wskazywane</dt>
    <dd>Jeśli wskaźnik myszy (hover) może wyzwolić dodatkową treść, wówczas wskaźnik może zostać przeniesiony na dodatkową treść bez znikania dodatkowej treści;</dd>
    <dt>Trwałe</dt>
    <dd>Dodatkowa treść pozostaje widoczna do momentu usunięcia wyzwalacza aktywacji lub fokusu, użytkownik odrzuca go lub jego informacje nie są już ważne.</dd>
  </dl>
  <p>Wyjątek: Wizualna prezentacja dodatkowej treści jest kontrolowana przez program użytkownika i nie jest modyfikowana przez autora.</p>
</blockquote>
<p class="persona">Nauczyciel ze słabym wzrokiem korzystający z oprogramowania do powiększania ekranu:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Poruszałem myszką, aby śledzić, na co patrzę na stronie internetowej. Pomaga mi to utrzymać koncentrację. Wtedy - bum - pojawiło się to małe okienko. Zasłaniało to, co próbowałem przeczytać i nie mogłem go usunąć.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Najechałem kursorem na słowo i wyskoczyło okienko z definicją, ale przy moim powiększeniu było ono w większości poza ekranem. Przesunąłem wskaźnik myszy na pole definicji i przewinąłem powiększony obszar do pola definicji, które pozostało wyświetlone i mogłem je przeczytać.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/content-on-hover-or-focus.html">Objaśnienie KS  Treść spod kursora lub fokusu</a></p>

## Wytyczna 2.1 Dostępność z klawiatury

Zapewnij dostępność wszystkich funkcjonalności za pomocą klawiatury.

### 2.1.4 Jednoznakowe skróty klawiaturowe (A)

<blockquote class="sc">
  <p>Jeśli <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-keyboard-shortcuts" data-link-type="dfn">skrót klawiaturowy</a> jest zaimplementowany w treści tylko przy użyciu jednego znaku (litery, w tym wielkiej i małej, cyfry lub symbolu), to przynajmniej jedno z poniższych jest prawdziwe:</p>
  <dl>
    <dt>Wyłączanie</dt>
    <dd>Istnieje <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-mechanizm" data-link-type="dfn">mechanizm</a> wyłączania skrótu;</dd>
    <dt>Mapowanie</dt>
    <dd>Istnieje mechanizm zmiany mapowania skrótu w celu użycia jednego lub więcej niedrukowalnych znaków klawiatury (np. Ctrl, Alt, itp.);</dd>
    <dt>Aktywny tylko po otrzymaniu fokusu</dt>
    <dd>Skrót klawiaturowy dla <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-user-interface-components" data-link-type="dfn">komponentu interfejsu użytkownikat</a> jest aktywny tylko wtedy, gdy ten komponent ma fokus.  </dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">reporter</a> z powtarzającymi się urazami stresowymi, który korzysta z oprogramowania do rozpoznawania głosu:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Kiedy korzystałem z aplikacji poczty za pomocą poleceń głosowych, ciągle usuwała ona wiadomości zamiast je otwierać.</q><br/>
      <em>Uwaga: </em>Istniał klawisz skrótu do usuwania, który był wyzwalany przez coś, o czym mówił dziennikarz, i nie było możliwości wyłączenia skrótów klawiszowych.</span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>W mojej aplikacji arkusza kalkulacyjnego istnieje ustawienie umożliwiające wyłączenie lub modyfikację skrótów klawiszowych.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/character-key-shortcuts.html">Objaśnienie KS Jednoznakowe skróty klawiaturowe</a></p>

## Wytyczna 2.2 Wystarczający czas

Zapewnij użytkownikom wystarczająco dużo czasu na przeczytanie i skorzystanie z treści.

### 2.2.6 Ostrzeżenie o limicie czasu (AAA)

<blockquote class="sc">
  <p>Użytkownicy muszą być ostrzeżeni o limicie czasu <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-user-inactivity" data-link-type="dfn">bezczynności użytkownika</a>, którego przekroczenie mogłoby spowodować utratę danych, chyba że dane te są przechowywane przez ponad 20 godzin, gdy uczestnik nie podejmie żadnych działań.</p>
</blockquote>
<p class="persona">Pomocnik na placu szkolnym z niepełnosprawnością intelektualną:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Wybierałem świadczenia pracownicze i porównywałem różne plany. Kiedy wróciłem, aby wybrać plan zdrowotny, upłynął limit czasu i utraciłem wszystkie informacje, które już wprowadziłem.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Kiedy uruchomiłem aplikację Employee Benefits, aplikacja poinformowała mnie, ile minut zostało mi na wypełnienie formularzy.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/timeouts.html">Objaśnienie KS Ostrzeżenie o limicie czasu</a></p>


## Wytyczna 2.3 Ataki padaczki

Prezentuj treść tak, aby nie wywoływała napadów padaczkowych.

### 2.3.3 Animacja po interakcji (AAA)

<blockquote class="sc">
  <p><a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-motion-animation" data-link-type="dfn">Animacja ruchowa </a> wyzwalana przez interakcję może być wyłączona, chyba że animacja jest istotna <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-essential" data-link-type="dfn">istotna</a> dla funkcjonalności lub przekazywanych informacji.</p>
</blockquote>
<p class="persona">Artysta z zaburzeniami przedsionkowymi:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>W aplikacji podatkowej online, gdy poruszam myszką lub przechodzę do różnych pól, podąża za mną po ekranie mały dymek z aktualnym saldem. Przyprawia mnie to o zawroty głowy i mdłości. </q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Bardzo się ucieszyłem, że istnieje możliwość wyłączenia animacji.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/animation-from-interactions.html">Objaśnienie KS Animacja po interakcji</a></p>

## Wytyczna 2.5 Metody obsługi

Ułatwiaj użytkownikom obsługę funkcji za pomocą różnych sposobów poza klawiaturą.

### 2.5.1 Gesty dotykowe (A)

<blockquote class="sc">
  <p>Wszystkie <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-funkcjonalnosci" data-link-type="dfn">funkcjonalności</a> wykorzystujące do obsługi gesty wielopunktowe lub oparte na ścieżkach mogą być obsługiwane za pomocą <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-dotyku-jednopunktowego" data-link-type="dfn">dotyku jednopunktowego</a> bez gestu opartego na ścieżce, chyba że <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-istotna" data-link-type="dfn">istotny</a> jest gest wielopunktowy lub oparty na ścieżce.</p>
</blockquote>
<p class="persona">Komik z porażeniem mózgowym, który ma ograniczenia ruchu w palcach :</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Nie mogę poruszać palcami w ten sposób. Potrzebuję innego sposobu na powiększenie mapy.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Dobrze, że są przyciski do powiększania i pomniejszania.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/pointer-gestures.html">Objaśnienie KS Gesty dotykowe</a></p>

### 2.5.2 Rezygnacja ze wskazania (A)

<blockquote class="sc">
  <p>W przypadku <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-funkcjonalnosci" data-link-type="dfn">funkcjonalności</a>, które są wywoływane za pomocą <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-dotyku-jednopunktowego" data-link-type="dfn">dotyku jednopunktowego</a>, co najmniej jedno z poniższych twierdzeń jest prawdziwe:</p>
  <dl>
    <dt>Brak zdarzenia</dt>
    <dd><a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-down-event" data-link-type="dfn">Naciskanie</a> nie wywołuje jakiejkolwiek części zdarzenia;</dd>
    <dt>Przerwanie lub cofnięcie</dt>
    <dd>Zdarzenie jest zależne od <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-up-event" data-link-type="dfn">zwolnienia nacisku</a> i istnieje <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-mechanizmu" data-link-type="dfn">mechanizm</a>, którym można je przerwać lub cofnąć po zwolnieniu nacisku;</dd>
    <dt>Odwrócenie zdarzenia</dt>
    <dd>Zwolnienie nacisku cofa wywołane zdarzenie i przywraca stan sprzed zdarzenia;</dd>
    <dt>Istotne</dt>
    <dd>Wciśnięcie jest  <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-istotna" data-link-type="dfn">niezbędne</a> do wywołania zdarzenia.</dd>
  </dl>
</blockquote>
<p class="persona"> Polityk z niepełnosprawnością ruchową i słabym wzrokiem:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Chciałem nacisnąć przycisk « »Wycisz» i przypadkowo zamiast tego przycisku  dotknąłem «Zakończ połączenie». Połączenie natychmiast się rozłączyło.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>W innej aplikacji do konferencji internetowych, jeśli przypadkowo dotknę przycisku «Zakończ połączenie», mogę po prostu zsunąć palec z przycisku «Zakończ połączenie» i połączenie nie zostanie zakończone.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation.html">Objaśnienie KS  Pointer Cancellation</a></p>


### 2.5.3 Etykieta w nazwie (A)

<blockquote class="sc">
  <p> W przypadku <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-komponentu-interfejsu-uzytkownika" data-link-type="dfn">komponentów interfejsu użytkownika</a> z <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-etykiety" data-link-type="dfn">etykietami</a> zawierającymi <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-tekstu" data-link-type="dfn">tekst</a> lub  <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-obrazu-tekstu" data-link-type="dfn">obrazy tekstu</a>, <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-nazwa" data-link-type="dfn">nazwa</a> zawiera tekst, który jest prezentowany wizualnie.</p>

</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> z powtarzającym się urazem stresowym, który używa oprogramowania do rozpoznawania głosu:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Rozumiał większość moich poleceń głosowych, dopóki nie dotarłem do przycisku Wyślij. Powtarzałem "Wyślij" i nie działało.</q><br/>
      <em>Uwaga:  </em>Wizualnie było to oznaczone jako „wyślij”, ale „nazwa” w kodzie brzmiała „prześlij”. Działałoby, gdyby „nazwa” zaczynała się od „wyślij”.</span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/label-in-name.html">Objaśnienie KS Etykieta w nazwie</a></p>

### 2.5.4 Aktywowanie ruchem (A)

<blockquote class="sc">
  <p><a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-funkcjonalnosci" data-link-type="dfn">Funkcjonalność</a>, którą można obsługiwać za pomocą ruchu urządzenia lub ruchu użytkownika, można również obsługiwać za pomocą <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-komponentu-interfejsu-uzytkownika" data-link-type="dfn">komponentów interfejsu użytkownika</a>, a reagowanie na ruch można wyłączyć, aby zapobiec przypadkowemu uruchomieniu, z wyjątkiem sytuacji, gdy:</p>
  <dl>
    <dt>Obsługiwany interfejs</dt>
    <dd>Ruch służy do obsługi funkcjonalności poprzez interfejs <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-obs-ugujaca-dostepnosc" data-link-type="dfn">obsługiwany przez dostępność</a>;</dd>
    <dt>Istotny</dt>
    <dd>Ruch jest <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-istotna" data-link-type="dfn">niezbędny</a> niezbędny dla funkcji, a to spowodowałoby unieważnienie działania.</dd>
  </dl>
  
</blockquote>
<p class="persona">Komik z porażeniem mózgowym poruszający się na wózku inwalidzkim:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Nie mogę potrząsnąć telefonem; jest podłączony do mojego wózka inwalidzkiego. Musi więc istnieć inny sposób aktywacji tej funkcji, na przykład przycisk</q></span></p></li>
    <li><p><span class="issue">Problem:</span><span><q>Mam trzęsące się ręce, więc muszę wyłączyć aktywację ruchem — a następnie móc robić rzeczy bez aktywacji ruchem.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Moja przyjaciółka ma taką fajną aplikację, która wygląda jak fizyczna blokada obrotu. Obraca telefonem, by wybrać kombinację. Mogę użyć tej samej aplikacji, wpisując numery bezpośrednio.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/motion-actuation.html">Objaśnienie KS Aktywowanie ruchem</a></p>

### 2.5.5 Rozmiar celu dotykowego (AAA)

<blockquote class="sc">
  <p>Rozmiar <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-target" data-link-type="dfn">celu</a><a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-pointer-inputs" data-link-type="dfn">punktu dotykowego</a> wynosi co najmniej 44 na 44 <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-css-pixels" data-link-type="dfn">piksele CSS</a>, chyba że:</p>
  <dl>
    <dt>Odpowiednik</dt>
    <dd>Cel jest dostępny za pośrednictwem równoważnego łącza lub kontrolki na tej samej stronie, która ma co najmniej 44 na 44 piksele CSS;</dd>
    <dt>Śródliniowe</dt>
    <dd>Cel znajduje się w zdaniu lub w bloku tekstu;</dd>
    <dt>Kontrola programu użytkownika</dt>
    <dd>Rozmiar obiektu docelowego jest określony przez program użytkownika (przeglądarkę) i nie jest modyfikowany przez autora;</dd>
    <dt>Istotny</dt>
    <dd>Szczególna prezentacja celu ma <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-essential" data-link-type="dfn">istotne</a> znaczenie dla przekazywanych informacji. </dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Senior</a> z drżeniem rąk (i dużymi palcami):</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Wtedy muszę zacząć wszystko od nowa.Przyciski są tak blisko, że wybierając «Prześlij», klikam «Anuluj». Wtedy muszę zacząć wszystko od nowa.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Pomiędzy przyciskami jest więcej miejsca, więc nie nacisnę niewłaściwego przycisku, nawet gdy jadę autobusem po wyboistej drodze.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/target-size.html">Objaśnienie KS Rozmiar celu dotykowego</a></p>

### 2.5.6 Równoległy mechanizm wprowadzania danych (AAA)

<blockquote class="sc">
  <p>Treści internetowe nie ograniczają możliwości korzystania z trybów wprowadzania danych dostępnych na platformie, z wyjątkiem sytuacji, w których ograniczenie jest <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-essential" data-link-type="dfn">istotne</a>, wymagane do zapewnienia bezpieczeństwa treści lub wymagane do przestrzegania ustawień użytkownika.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> z powtarzającymi się urazami stresowymi, który korzysta z oprogramowania do rozpoznawania mowy:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Kiedy dopada mnie RSI, często przełączam się między klawiaturą, myszą, rysikiem i głosem. Ta aplikacja nie pozwala mi używać rysika, gdy mam podłączoną klawiaturę.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/concurrent-input-mechanisms.html">Objaśnienie KS Równoległy mechanizm wprowadzania danych</a></p>

## Wytyczna 4.1 Kompatybilność

Zapewnij jak największą zgodność z aktualnymi i przyszłymi programami użytkownika, w tym z technologiami asystującymi.

### 4.1.3 Komunikaty o stanie (AA)

<blockquote class="sc">
  <p>W treści wprowadzonej przy użyciu języka znaczników <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-status-messages" data-link-type="dfn">komunikaty o stanie</a>  mogą być <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-programmatically-determinable" data-link-type="dfn">programowo określane</a> poprzez <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-role" data-link-type="dfn">rolę</a> lub właściwości, dzięki czemu mogą być prezentowane użytkownikowi za pomocą <a href="https://www.w3.org/Translations/WCAG21-pl/#dfn-assistive-technologies" data-link-type="dfn">technologii wspomagających</a> bez uzyskiwania fokusu.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#accountant">Księgowy</a>, który nie widzi i korzysta z czytnika ekranu:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Wybrałem zajęcia na konferencję, ale nie wiem, czy zostały dodane do mojego harmonogramu.</q></span></p></li>
    <li><p><span class="issue">Poprawne działanie:</span><span><q>Gdy dodam spotkanie do kalendarza, słyszę potwierdzenie.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/status-messages.html">Objaśnienie KS Komunikaty o stanie</a></p>

## O personach
Persony te to reprezentacje osób z niepełnosprawnościami opracowane na podstawie danych jakościowych dotyczących prawdziwych ludzi.

Podlinkowane role person prowadzą do [Historii użytkowników Internetu](https://www.w3.org/WAI/people-use-web/user-stories/). Na tej stronie znajdują się też inne persony z różnymi niepełnosprawnościami.

Po wystarczającym przejrzeniu cytatów z person planujemy dodać je do dokumentów objaśniających.





