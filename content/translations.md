---
title: WCAG 2 Translations
nav_title: "Translations"
lang: en
last_updated: 2023-12-13
description: Links to translations of Web Content Accessibility Guidelines (WCAG) 2.2, 2.1 and 2.0.

github:
  repository: w3c/wai-intro-wcag
  path: 'content/translations.md'

permalink: /standards-guidelines/wcag/translations/
ref: /standards-guidelines/wcag/translations/

image: /content-images/wai-intro-wcag/wcag-intro-social.jpg
footer: >
  <p><strong>Date:</strong> Updated 13 December 2023. First published 2 March 2009.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>, Shadi Abou_Zahra, Xueyuan Jia, Rémi Bétin.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>). Updated as part of the <a href="https://www.w3.org/WAI/about/projects/wai-coop/">WAI-CooP project</a>, co-funded by the European Commission.</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page lists translations of Web Content Accessibility Guidelines (WCAG) 2.2, 2.1 and 2.0. Translations of other accessibility resources are listed in **[All WAI Translations](https://www.w3.org/WAI/translations/)**.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Types of Translations

Two types of translations are listed on this page:

-   _[Authorized Translations](https://www.w3.org/2005/02/TranslationPolicy)_ follow a formal review process and are endorsed by W3C.
-   _Unofficial translations_ are not reviewed and are not endorsed by W3C.

{% assign wcag = site.data.standards-translations | where_exp: "item", "item.standard == 'wcag'" | map: "versions" %}
{% assign wcag20 = wcag[0] | where_exp: "item", "item.version == 2.0" | first %}
{% assign wcag21 = wcag[0] | where_exp: "item", "item.version == 2.1" | first %}
{% assign wcag22 = wcag[0] | where_exp: "item", "item.version == 2.2" | first %}

## WCAG 2.2

### Available Translations

<table class="quiet">
  <thead>
    <tr>
      <th scope="col">Language</th>
      <th scope="col">Link</th>
      <th scope="col">Type</th>
    </tr>
  </thead>
  <tbody>
    {%- for trans in wcag22.translations -%}
    <tr>
      <th id="{{ trans.lang }}22">{{ site.data.lang[trans.lang].name }}</th>
      {%- if trans.title -%}<td lang="{{ trans.lang }}">{%- else -%}<td>{%- endif -%}
        <strong><a href="{{ trans.url }}" hreflang="{{ trans.lang }}">
        {%- if trans.title -%}{{ trans.title}}{%- else -%}{{ wcag22.en_title }}{%- endif -%} {% include_cached external.html %}</a></strong>
      </td>
      <td>{%- if trans.type == "authorized" -%}Authorized{%- elsif trans.type == "external" -%}Unofficial{%- endif -%}</td>
    </tr>
    {%- endfor -%}
  </tbody>
</table>

{::nomarkdown}
{% include excol.html type="start" %}
{:/}

### Planned Translations

{::nomarkdown}
{% include excol.html type="middle" %}

<table class="quiet">
  <thead>
    <tr>
      <th scope="col">Language</th>
      <th scope="col">Type</th>
      <th scope="col">Notes and e-mail notifications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th id="ar22">Arabic</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2023OctDec/0026.html">Notification of intent (17 November 2023)</a></td>
    </tr>
    <tr>
      <th id="ca22">Catalan</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2023OctDec/0036.html">Notification of intent (13 December 2023)</a></td>
    </tr>
    <tr>
      <th id="nl22">Dutch</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2023AprJun/0016.html">Notification of intent (5 June 2023)</a></td>
    </tr>
    <tr>
      <th id="fr22">French</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2022JulSep/0001.html">Notification of intent (25 July 2022)</a></td>
    </tr>
    <tr>
      <th id="pt22">Brazilian Portuguese</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2023OctDec/0011.html">Notification of intent (17 October 2023)</a></td>      
    </tr>
    <tr>
      <th id="zh-hans22">Simplified Chinese</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2023OctDec/0006.html">Notification of intent (8 October 2023)</a></td>
    </tr>
  </tbody>
</table>

{% include excol.html type="end" %}
{:/}

## WCAG 2.1

### Available Translations

<table class="quiet">
  <thead>
    <tr>
      <th scope="col">Language</th>
      <th scope="col">Link</th>
      <th scope="col">Type</th>
    </tr>
     </thead>
  <tbody>  
  {%- for trans in wcag21.translations -%}
    <tr>
      <th id="{{ trans.lang }}21">{{ site.data.lang[trans.lang].name }}</th>
      {%- if trans.title -%}<td lang="{{ trans.lang }}">{%- else -%}<td>{%- endif -%}
        <strong><a href="{{ trans.url }}" hreflang="{{ trans.lang }}">
        {%- if trans.title -%}{{ trans.title}}{%- else -%}{{ wcag22.en_title }}{%- endif -%} {% include_cached external.html %}</a></strong>
      </td>
      <td>{%- if trans.type == "authorized" -%}Authorized{%- elsif trans.type == "external" -%}Unofficial{%- endif -%}</td>
    </tr>
  {%- endfor -%}
  </tbody>
</table>

{::nomarkdown}
{% include excol.html type="start" %}
{:/}

### Planned Translations

{::nomarkdown}
{% include excol.html type="middle" %}

<table class="quiet">
  <thead>
    <tr>
      <th scope="col">Language</th>
      <th scope="col">Type</th>
      <th scope="col">Notes and e-mail notifications</th>
    </tr>
     </thead>
  <tbody>
    <tr>
      <th id="bg21">Bulgarian</th>
      <td>Unofficial</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2021OctDec/0000.html">Draft Bulgarian unofficial translation of WCAG 2.1 (1 October 2021)</a></td>
    </tr>
    <tr>
      <th id="es21">Spanish</th>
      <td>Unofficial</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2019AprJun/0004.html">Notification of intent (12 April 2019)</a></td>
    </tr>
    <tr>
      <th id="il21">Hebrew</th>
      <td></td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2020JanMar/0025.html">Hebrew Intention of translation (21 March 2020)</a></td>
    </tr>
    <tr>
      <th id="pt21">Portuguese, Brazilian</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2018AprJun/0026.html">notification of intent for Brazilian Portuguese Authorized Translation of WCAG 2.1 (25 June 2018)</a></td>      
    </tr>
    <tr>
      <th id="pt3">Portuguese, European</th>
      <td>Authorized</td>
      <td><a href="https://lists.w3.org/Archives/Public/w3c-translators/2018OctDec/0023.html">Notification of intent for European Portuguese Authorized Translation of WCAG 2.1 (2 November 2018)</a></td>
    </tr>
    <tr>
      <th id="sk21">Slovak</th>
      <td>Authorized</td>
      <td><a href="https://s3.eu-central-1.amazonaws.com/w3c-wcag-2.1-sk/index.html">Slovak Candidate Authorized Translation of WCAG 2.1  {% include_cached external.html %}</a><br />Review  — <a href="https://lists.w3.org/Archives/Public/w3c-translators/2021AprJun/0002.html">notification of review of Slovak Candidate Authorized Translation of WCAG 2.1 (13 April 2021)</a></td>
    </tr>
    <tr>
      <th id="zh-hant21">Traditional Chinese</th>
      <td>Authorized</td>
      <td>Authorized Translation — <a href="https://lists.w3.org/Archives/Public/w3c-translators/2023JulSep/0010.html">notification of intent for Traditional Chinese Authorized Translation of WCAG&nbsp;2.1 (5 September 2023)</a></td>
    </tr>
  </tbody>
</table>

{% include excol.html type="end" %}
{:/}

## WCAG 2.0

### Available Translations

<table class="quiet">
  <thead>
    <tr>
      <th scope="col">Language</th>
      <th scope="col">Link</th>
      <th scope="col">Type</th>
    </tr>
  </thead>
  <tbody>
    {%- for trans in wcag20.translations -%}
    <tr>
      <th id="{{ trans.lang }}22">{{ site.data.lang[trans.lang].name }}</th>
      {%- if trans.title -%}<td lang="{{ trans.lang }}">{%- else -%}<td>{%- endif -%}
        <strong><a href="{{ trans.url }}" hreflang="{{ trans.lang }}">
        {%- if trans.title -%}{{ trans.title}}{%- else -%}{{ wcag22.en_title }}{%- endif -%} {% include_cached external.html %}</a></strong>
      </td>
      <td>{%- if trans.type == "authorized" -%}Authorized{%- elsif trans.type == "external" -%}Unofficial{%- endif -%}</td>
    </tr>
    {%- endfor -%}
  </tbody>
</table>

{::nomarkdown}
{% include excol.html type="start" %}
{:/}

### Planned Translations

{::nomarkdown}
{% include excol.html type="middle" %}

<table class="quiet">
  <thead>
     <tr>
        <th scope="col">Language</th>
        <th scope="col">Type</th>
        <th scope="col">Notes and e-mail notifications</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <th class="changed"><a id="ar">Arabic</a></th>
        <td class="changed">Authorized</td>
        <td class="changed">
        <a href="http://www.alecso.org/wcag2.0/">Arabic Candidate Authorized Translation of WCAG 2.0 {% include_cached external.html %}</a>
        Review — <a href="https://lists.w3.org/Archives/Public/w3c-wai-ig/2013AprJun/0106.html">Notification of review (11 April 2013)</a><br>
        Authorized Translation — <a href="http://lists.w3.org/Archives/Public/w3c-translators/2010JulSep/0113.html">Notification of intent (12 September 2010)</a></td>
     </tr>
     <tr>
        <th><a id="be">Belarusian</a></th>
        <td>Unofficial</td>
        <td><a href="http://www.fatcow.com/resources/wai-be.html">Belarusian unofficial translation of WCAG 2.0 {% include_cached external.html %}</a></td>
     </tr>
     <tr>
        <th><a id="cs">Czech</a></th>
        <td>Authorized</td>
        <td><a href="http://lists.w3.org/Archives/Public/w3c-translators/2010OctDec/0022.html">Launch of Czech Authorized Translation of WCAG 2.0 (15 October 2010)</a></td>
     </tr>
     <tr>
        <th class="changed"><a id="es">Spanish</a></th>
        <td class="changed">Authorized</td>
        <td class="changed"><ul>
              <li><a href="http://www.sidar.org/traducciones/wcag20/es/">Spanish Candidate Authorized Translation of WCAG 2.0 {% include_cached external.html %}</a></li>
              <li>Review — <a href="https://lists.w3.org/Archives/Public/w3c-wai-ig/2009OctDec/0122.html">notification of review of Spanish Candidate Authorized Translation of WCAG 2.0 (17 December 2009)</a></li>
              <li>Authorized Translation — <a href="http://lists.w3.org/Archives/Public/w3c-translators/2009OctDec/0280.html">announcement of Spanish Candidate Authorized Translation of WCAG 2.0 review period (17 December 2009)</a></li>
              <li><a href="http://www.codexexempla.org/traducciones/pautas-accesibilidad-contenido-web-2.0.htm">Spanish unofficial translation of WCAG 2.0 completed {% include_cached external.html %}</a></li>
              <li>Unofficial translation —  <a href="http://lists.w3.org/Archives/Public/w3c-translators/2012OctDec/0019.html">notification if intent for Spanish unofficial translation of Understanding WCAG 2.0 (2 November 2012)</a> </li>
           </ul></td>
     </tr>
     <tr>
        <th><a id="hi">Hindi</a></th>
        <td>Authorized</td>
        <td><a href="http://lists.w3.org/Archives/Public/w3c-translators/2009AprJun/0147.html">Notification of intent (21 May 2009)</a></td>
     </tr>
     <tr>
        <th><a id="hr">Croatian</a></th>
        <td>Unofficial</td>
        <td><a href="http://lists.w3.org/Archives/Public/w3c-translators/2009OctDec/0188.html">Notification of intent (20 November 2009)</a></td>
     </tr>
     <tr>
        <th><a id="ko">Korean</a></th>
        <td>Authorized</td>
        <td><a href="http://archi.ssu.ac.kr/WCAG20/">Korean unofficial translation of WCAG 2.0 {% include_cached external.html %}</a> Authorized Translation — <a href="http://lists.w3.org/Archives/Public/w3c-translators/2009JanMar/0077.html">notification of intent for Korean Authorized Translation of WCAG 2.0 (30 January 2009)</a></td>
     </tr>
     <tr>
        <th><a id="lt">Lithuanian</a></th>
        <td>Unofficial</td>
        <td><a href="http://lists.w3.org/Archives/Public/w3c-translators/2011JulSep/0063.html">Notification of intent (6 September 2011)</a></td>
     </tr>
     <tr>
        <th><a id="mk">Macedonian</a></th>
        <td>Authorized</td>
        <td>Authorized Translation — notification of intent for Macedonian Authorized Translation of WCAG 2.0</td>
     </tr>
     <tr>
        <th class="changed"><a id="pl">Polish</a></th>
        <td class="changed">Authorized</td>
        <td class="changed">
        <a href="http://fdc.org.pl/wcag2/">Polish Candidate Authorized Translation of WCAG 2.0 {% include_cached external.html %}</a>
        Review — <a href="https://lists.w3.org/Archives/Public/w3c-wai-ig/2013AprJun/0259.html">Notification of review (03 June 2013)</a><br>
        Authorized Translation — <a href="http://lists.w3.org/Archives/Public/w3c-translators/2010JanMar/0100.html">Notification of intent (8 March 2010)</a></td>
     </tr>
     <tr>
        <th><a id="ro">Romanian</a></th>
        <td>Unofficial</td>
        <td><a href="http://lists.w3.org/Archives/Public/w3c-translators/2010JanMar/0031.html">Notification of intent (20 January 2010)</a></td>
     </tr>
  </tbody>

</table>

{% include excol.html type="end" %}
{:/}


## More Information

### About WCAG

For information on WCAG, see the [[Web Content Accessibility Guidelines (WCAG) Overview]](/standards-guidelines/wcag/).

### Other Translations

For other translations lists, see:
* **[All WAI Translations](https://www.w3.org/WAI/translations/)** for translations of other accessibility resources
* **[Translations of Current W3C Technical Reports](https://www.w3.org/Translations/)**

### About Translating

For information on translating W3C documents, see:
* [Translating WAI Resources](/about/translating/) for accessibility resources
* [Contributing to W3C Translations](http://www.w3.org/Consortium/Translation/) for W3C Technical Reports

**Note:** If you are interested in translating a specific document, make sure to announce it (as instructed in the links above) to facilitate collaboration, to avoid duplication of effort, to ensure that you have the latest version, and to appropriately address pending updates and errata.

For additional information on WCAG translations, contact Shawn Lawton Henry <shawn@w3.org>.
