---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{%
  include button.html
  type="email"
  text="xlab@kennesaw.edu"
  link="https://mail.google.com/mail/?view=cm&to=yxie11@kennesaw.edu"
%}
{%
  include button.html
  type="phone"
  text="+1 (470) 578-3803"
  link="+1-470-578-3803"
%}
{%
  include button.html
  type="address"
  tooltip="Our location"
  link="https://maps.app.goo.gl/XaZddjDP3k7rcPzz6"
%}

{% include section.html %}

<!-- Calendly inline widget begin -->
<div id="calendly-embed" style="min-width:320px;height:700px;"></div>

<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js"></script>

<script>
Calendly.initInlineWidget({
url: 'https://calendly.com/ksuchloexie/dr-chloe-xie-s-individual-meeting-15-mins?',
parentElement: document.getElementById('calendly-embed')
});
</script>
<!-- Calendly inline widget end -->


<!-- Interactive Google Map -->
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3310.1064383674875!2d-84.52102052248156!3d33.9383904237305!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f5115510312027%3A0x81ce76f9703afb9c!2sKennesaw%20State%20University!5e0!3m2!1sen!2sus!4v1704409890375!5m2!1sen!2sus" width="800" height="600" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>


{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

<!-- {% include cols.html col1=col1 col2=col2 %} -->

<!-- {% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->
