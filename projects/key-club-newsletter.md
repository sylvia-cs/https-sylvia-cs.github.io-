---
layout: post
title: 'Key Club Division Newsletter'
---

As News Editor of Key Club Division 42 East, I developed 11 issues from scratch using <a style="font-weight: 400">Photoshop</a>, with original graphics and designs. Below is a sampling of excerpts from the newsletter.

<div class="flex-container">
    {% for graphic in site.data.settings.newsletter-covers %}
        <img style="width: 185px; margin: 10px" src="{{ site.baseurl }}/assets/img/projects/key-club-newsletter/{{ graphic.file }}" alt="newsletter covers">
    {% endfor %}
</div>
<div>
    {% for graphic in site.data.settings.newsletter-layouts %}
        <img style="width: 800px; margin: 10px" src="{{ site.baseurl }}/assets/img/projects/key-club-newsletter/{{ graphic.file }}" alt="newsletter covers">
    {% endfor %}
</div>
<div style="align-content: center">
    {% for graphic in site.data.settings.newsletter-graphics %}
        <img style="width: 285px; margin-left: 10px; margin-right: 0;" src="{{ site.baseurl }}/assets/img/projects/key-club-newsletter/{{ graphic.file }}" alt="newsletter covers">
    {% endfor %}
</div>
<a></a>
<p style="text-align: center; color: black; size: 10px">Read the full publications (May 2017- March 2018) on <a href="https://issuu.com/d42enarwhals/docs/d42e_dnews_12_1718">issuu.com</a></p>