---
layout: moments
title: Moments of Empathy
description: A collection of links, videos, and stories that demonstrate the profound impact of empathy. 
---

<h1>Moments of Empathy</h1>
<hr />
<div>
    {%- for moment in site.moments -%} 
    <div class="moment item">{{ moment.content }} </div>
    {%- endfor -%}
</div>
