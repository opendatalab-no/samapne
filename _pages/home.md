---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header.svg
  caption:
excerpt: 'Samskaping og næringsutvikling med åpne kommunale data'
feature_row:
  - image_path: /assets/images/publish-icons.png
    alt: "publishing"
    title: "Publishing open data"
    excerpt: "Information and tools for owners and providers of open data."
    url: "/publish/intro/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/use-icons.png
    alt: "using"
    title: "Using open data"
    excerpt: "Information and tools for innovators and developers using open data."
    url: "/use/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/research-icons.png
    alt: "survey"
    title: "Research on open data"
    excerpt: "[Help us learn more](/news/survey) about what makes open data easy or difficult to use, and learn more about our research."
    url: "/research/intro/"
    btn_class: "btn--primary"
    btn_label: "More info"
    
---

SamÅpne er et innovasjonsprosjekt i offentlig sektor under FORKOMMUNE-programmet til Forskningsrådet.

Prosjektet mål er å bidra til at kommuner kan etablere kostnadseffektive og standardiserte prosesser for åpning og forvaltning av innovasjonsfremmende åpne data, og "knekke koden" for å skape innovasjon og næringsutvikling gjennom samskaping basert på åpne data. Les mer om prosjektet her.

Prosjektpartnere er Trondheim kommune, Bodø kommune og SINTEF. I tillegg er det flere kommuner som følger prosjektet.

[Les mer om prosjektet](/om){: .btn .btn--inverse}
## Workshops og seminarer
I løpet av prosjektet vil vi arrangere en rekke workshops og seminarer hvor vi inviterer næringsliv og andre interesserte får anledning til å ha en dialog og samskape ideer med  fagpersoner fra kommunene. Om dette er interessant for deg, ta gjerne kontakt med oss! 

De første arrangementene vil finne sted i Trondheim og Bodø. Datoer og flere detaljer vil bli annonsert her senere.
## Nyheter fra prosjektet
{% for post in site.posts limit:1 %}
{% capture notice-2 %}
#### [{{post.title}}]({{post.url}})
{{post.excerpt}}
{% endcapture %}
<div class="notice--primary">{{ notice-2 | markdownify }}</div>
{% endfor %}

[Flere nyheter](/nyheter){: .btn .btn--inverse}
