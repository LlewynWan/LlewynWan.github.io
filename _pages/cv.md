---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
&nbsp;

<object data="files/CV.pdf" type="application/pdf" width="700px" height="1000px">
    <embed src="files/CV.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="http://yoursite.com/the.pdf">Download PDF</a>.</p>
    </embed>
</object>

Education
======
* PhD candidate in Computer Science, __City University of Hong Kong__, 2021-2025 _(expected)_
* Bachelor of Engineering in Computer Science, __Wuhan University__, 2017-2021 _(Yes, I was there when COVID broke out)_

&nbsp;

Work experience
======
* Oct. 2020 - May. 2021: Microsoft Research Asia
  * Reseaerch Intern
  * Mentor: Xiao Li

&nbsp;

Publications
======
  <ul style="list-style-type:none;padding-left:0;">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

&nbsp;

Skills
======
* Coding
  * JavaScript
    * React
  * TypeScript
  * Python
    * Django
    * AI stuff (PyTorch, TensorFlow, ...)
  * C / C++ (best in the world)
* Design: Figma
* Language
  * Mandarin (native)
  * English
  * Cantonese

  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
