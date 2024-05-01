---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also check out <a href="{{site.author.googlescholar}}">my Google Scholar profile</a> for more details and an up-to-date list.</div>
{% endif %}

{% include base_path %}


## Preprints

<!--
Coming soon. 
-->

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal Papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


