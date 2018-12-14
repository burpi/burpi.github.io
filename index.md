---
layout: default
title:  Garage Jagt Emmen
title2: DÉ GARAGE IN EMMEN EN OMGEVING
section1: Garage Jagt helpt u zorgeloos op weg
section2: Aanbiedingen
img: /images/headers/h15.png
btn: Direct een afspraak maken
blink: /contact.html
---
<section>
  <div class="container-fluid">
      <div class="link-block col-md-12 col-sm-12" style="width: 100%;">
        <ul>
          <li class="myhints"><a href="tel: 0591-614846">Direct Bellen</a></li>
          <li class="myhints"><a href="/occasions.html">Occasions bekijken</a></li>
          <li class="myhints"><a href="/contact.html">Afspraak inplannen</a></li>
        </ul>
      </div>
    </div>
</section>

<section class="contents text-center text-sm-left p-60 p-lg-100" id="contents-4">
  <div class="container">
    <div class="col-12 col-md-12 col-sm-12">
    <h2 class="mb-20 headerone">{{page.title2}}</h2>
    </div>
    <div class="row justify-content-between align-items-center">
      {% for section_platforma in site.section_platforma %}
      <div class="col-6 col-sm-6 col-lg-6 mb-30 mb-sm-0"><img class="image pic-md shadow marg-img" src="{{section_platforma.img}}" alt=""/>
      </div>
      <div class="col-6 col-sm-6 col-lg-6 left">
          <p>
            {{section_platforma.content}}
          </p>
      </div>
      {% endfor %}
    </div>
  </div>
</section>

<div class="portfolio text-center pt-60 pt-lg-100 pb-45 pt-sm-30 pb-lg-70" id="portfolio-3">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1 class="mb-40">{{page.section1}}</h1>
      </div>
    </div>
    <div class="row">
      {% for section_feature in site.section_feature %}
      <div class="col-12 col-sm-6 col-lg-4 mb-15 mb-sm-30">
        <div class="card"><img class="image pic-md" src="{{section_feature.img}}"/>
          <div class="p-30 ph-30">
            <h3 class="thumbstyle">{{section_feature.content}}</h3>
          </div>
        </div>
      </div>
      {% endfor %}
</div>