---
layout: moments
title: Moments of Empathy
description: A collection of links, videos, and stories that demonstrate the profound impact of empathy. 
twitter:
    title: Moments of Empathy
    description: A collection of people demonstrating deep understanding 
facebook:
    title: Moments of Great Empathy
    description: 
---


<div>
    {%- for moment in site.moments reversed -%} 
    <div class="moment item {{ moment.type }}">{{ moment.content }} </div>
    {%- endfor -%}
</div>

{%- include nav.md -%}