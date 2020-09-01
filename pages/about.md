---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I am **{{ site.author.name }}**))<br>
I'm a software engineer who enjoys learning and solving interesting problems. I enjoy working on diverse teams and collaborating to create innovative software. Most recently I've been working on a remote team to bring to life a framework called Maestro.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>