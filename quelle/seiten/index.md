---
title: Startseite
---
Willkommen in meinem digitalen Garten.

<section id="teasers">
{{# pages }}
  {{^ is_index }}
    {{> teaser }}
  {{/ is_index }}
{{/ pages }}
</section>
