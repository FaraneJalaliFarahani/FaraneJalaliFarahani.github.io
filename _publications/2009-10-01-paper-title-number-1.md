
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /publications
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
'This paper is about 66666666  Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).the number 1. [Download paper here](http://academicpages.github.io/files/paper1.pdf) The number 2 is left for fut

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


