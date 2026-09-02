---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---


Hi! I'm Wei-Tzu (Ruby) Lee, a recent graduate in Electrical and Computer Engineering with a minor in Applied Mathematics from the University of Washington. I'm broadly interested in machine learning systems, with a focus on efficient inference for large language models and multimodal models, particularly speech language models, as well as emerging agentic workloads.

From Fall 2024 to July 2026, I was fortunate to be an undergraduate researcher in the Systems for Future Intelligence (SyFI) Lab in the Paul G. Allen School of Computer Science & Engineering at the University of Washington, advised by Professor Baris Kasikci.

### Publications

{% for pub in site.data.publications %}
- **{{ pub.title }}**  
  {{ pub.authors }}  
  *{{ pub.venue }}*, {{ pub.year }}
  {% if pub.type == "preprint" %} **[Preprint]**{% endif %}  
  {% if pub.url != "" %}[[PDF]]({{ pub.url }}){% endif %}

{% endfor %}


### Talks

- **Towards Efficient Systems for Long Context ASR**  
  *MLSys Young Professionals Symposium*, 2026



