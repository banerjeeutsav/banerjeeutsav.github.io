---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

<a href="https://banerjeeutsav.github.io" style="font-weight:bold">Home</a>

<a href="https://banerjeeutsav.github.io/portfolio" style="font-weight:bold">Research</a>

<a href="https://banerjeeutsav.github.io/publications" style="font-weight:bold">Publications</a>

<a href="https://banerjeeutsav.github.io/teaching" style="font-weight:bold">Teaching</a>

<a href="https://banerjeeutsav.github.io/talks" style="font-weight:bold">Talks</a>

<a href="https://banerjeeutsav.github.io/cv" style="font-weight:bold">CV</a>

<!--
A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ label }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% for post in collection.docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
-->
