---
layout: page
title: Garage Jagt werkplaats
sub: Werkzaamheden
img: /images/achtergronden/Werkplaats_header.png
btn: Direct een afspraak maken
blink: /contact.html
---
<div class="portfolio text-center pt-60 pt-lg-100 pb-45 pt-sm-30 pb-lg-70" id="portfolio-3">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1 class="mb-40">{{page.sub}}</h1>
      </div>
    </div>
    <div class="row">
      {% for page_werkplaats in site.page_werkplaats %}
      <div class="col-12 col-sm-6 col-lg-4 mb-15 mb-sm-30">
        <div class="card"><a href="{{page.werkplaats.link}}"><img class="image pic-md" src="{{page_werkplaats.img}}"/></a>
          <div class="p-30 ph-30">
            <h3 class="thumbstyle">{{page_werkplaats.content}}</h3>
          </div>
        </div>
      </div>
      {% endfor %}
</div>