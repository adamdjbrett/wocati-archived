---
ID: 375
post_title: Participant Photos
author: adamdjbrett
post_excerpt: ""
layout: article
permalink: /resources/2011-wocati-consultation/2011-participant-photos/
published: true
post_date: 2012-06-26 04:52:09
---
*   At the 2011 Consultation, participants from around the globe interacted with one another in a wide variety of activities. These included collective reflection sessions, group discussions, and informal gatherings at meals and tea.
*   Special thanks to Dr. Victor Nakah for contributing these photos.

{% for image in site.static_files %}
  {% if image.path contains 'wp-content/uploads/2012/06/p' %}
    ![2014 event photos]({{ image.path }})
  {% endif %}
{% endfor %}
