---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---

<p class="date">
  Published, on <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
    <p>
      - CNCF Kochi Community
      <!-- [Join our Meetup Group 👍](https://www.meetup.com/Cloud-Native-Computing-Kochi/) -->
    </p>
  </div>
</main>
