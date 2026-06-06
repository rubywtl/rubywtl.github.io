---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---


Hi! I'm Ruby (Wei-Tzu Lee), a senior undergraduate in Electrical and Computer Engineering with a minor in Applied Mathematics at the University of Washington. My research focuses on machine learning systems, efficient inference, and hardware acceleration for AI workloads, spanning both cloud/datacenter infrastructure and resource-constrained edge devices. I am particularly interested in building systems that make modern AI models more efficient, scalable, and deployable in real-world settings. More recently, I have developed an interest in speech applications, including ASR, SpeechLMs, and speech-enabled agentic systems.

Since Fall 2024, I have been an undergraduate researcher in the Systems of Future Intelligence (SyFI) Lab in the Paul G. Allen School of Computer Science & Engineering at the University of Washington, advised by Professor Baris Kasikci.

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



