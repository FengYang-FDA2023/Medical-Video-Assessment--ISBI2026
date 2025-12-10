---
title: Medical Video AI Assessment and Uncertainty Quantification: Bridging Research and Practice
---

# Workshop Template!

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

A minimal Jekyll theme for creating workshop websites.

*Add your workshop abstract here!*

Artificial Intelligence and Machine Learning (AI/ML)-enabled medical devices are advancing rapidly to address the evolving needs of patients, clinicians, and manufacturers in the MedTech industry.  However, the pace of technological innovation has outstripped the development of evaluation methods in some instances, creating uncertainty for developers, and posing challenges for regulatory bodies charged with ensuring safety, efficacy, and transparency.
The workshop aims to introduce regulatory science on AI-enabled devices to the ISBI community, with a particular focus on the assessment of medical video AI and uncertainty quantification. These areas present unique challenges, including frame-to-frame variability, motion artifacts, and temporal consistency. We aim to foster dialogue among researchers, clinicians, and regulators to discuss technical and regulatory challenges and help to reduce the gap between development of novel AI technologies and their clinical adoption. We will discuss the development of regulatory science tools, testing methods, and metrics for assessing AI-assisted devices. 
While this workshop will focus on medical video AI systems, assessment many of the concepts generalize to other device types. 

*See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
