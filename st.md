---
layout: store
title: store
---

<br><br>
   <!-- Main hero unit for a primary marketing message or call to action -->
      <div class="hero-unit">
        <h1>Hello, world!</h1>
        <p>This is a template for a simple marketing or informational website. It includes a large callout called the hero unit and three supporting pieces of content. Use it as a starting point to create something more unique.</p>
        <p><a href="#" class="btn btn-primary btn-large">Learn more</a></p>
      </div>

      <!-- Example row of columns -->


 <div class="row">
{% assign product = site.product | sort: 'date' | reverse %}
{% for product in product %}

<div class="span4">
  {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        {{  <h2>{{product.title}}</h2>tweets.date | date: date_to_rfc822 }}
<p>{{ product.teaser | truncate: 445 }</p>
          <p><a class="btn" href="#">View details</a></p>
        </div>
{% endfor %}  
</div>
