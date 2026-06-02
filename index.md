---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---


Hi! I'm Ruby (Wei-Tzu Lee), a senior undergraduate in Electrical and Computer Engineering with minor in Applied Mathematics at the University of Washington. My work focuses on machine learning systems and hardware acceleration. I research in the UW Systems of Future Intelligence (SyFI) lab under Professor Baris Kasikci.

### Publications

{% for pub in site.data.publications %}
- **{{ pub.title }}**  
  {{ pub.authors }}  
  *{{ pub.venue }}*, {{ pub.year }}
  {% if pub.type == "preprint" %} **[Preprint]**{% endif %}  
  {% if pub.url != "" %}[[PDF]]({{ pub.url }}){% endif %}

{% endfor %}

