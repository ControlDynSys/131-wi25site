---
layout: home
title: Home
nav_order: 0
description: >-
    Course website for CDS 131 Winter 2025
---
<!-- <div class="parallax-window" data-parallax="scroll" data-image-src="/assets/background.png" data-speed="0.1">/div> -->
# CDS 131 | Linear Systems Theory
{: .mb-2 }
Winter 2025 | Instructor: Professor John Doyle
{: .mb-0 .fs-6 .text-grey-dk-200 }

<hr>

{% if site.announcements %}
{{ site.announcements.last }}
<a href="{{ site.baseurl }}/announcements" class="btn btn-outline fs-3">
  All Announcements
</a>
{% endif %}

# Course Calendar

LN = Lecture Notes, CD = Callier & Desoer, Linear System Theory, DFT = Doyle, Francis, & Tannenbaum, Feedback Control Theory

<!-- #### All lecture videos can be found on [bCourses](https://bcourses.berkeley.edu/courses/1522763/external_tools/78985) -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
