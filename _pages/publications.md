---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

*Click on the titles of articles for abstracts.*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Manuscripts under Review

{% for post in site.inreviews reversed %}
  {% include archive-single.html %}
{% endfor %}
