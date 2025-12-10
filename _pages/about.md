---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I'm Tim, I'm currently doing my PhD in Robotics at the [Multi-robot-systems Group](https://mrs.fel.cvut.cz/) at the Czech Technical University in Prague supervised by [Martin Saska](https://mrs.fel.cvut.cz/members/martin-saska). My research focuses on mutual relative localization for agile UAV teams, enabling autonomous cooperation in challenging real-world environments.

In the next stage of my research, I am working on intention-based swarming using implicit optical camera communication, aiming to make decentralized UAV teams more resilient and agile. 
I am currently interested in a research stay of about 4 to 6 months and would be happy to explore collaborations on decentralized UAV swarms, particularly in the areas of mutual relative localization, intention-based swarming, and resilient multi-agent coordination.

Outside of research, I enjoy road cycling, running, and bouldering. I started climbing during my studies in Würzburg and have recently begun exploring rope climbing as well.
<section class="news-section">
  <h2>Featured News</h2>
  <div class="news-list">
    {% if site.data.news and site.data.news.size > 0 %}
      {% for item in site.data.news %}
      <div class="news-item">
        <div class="news-date">{{ item.date | date: "%b %Y" }}</div>
        <div class="news-body">{{ item.text | markdownify | replace: '<a ', '<a target="_blank" rel="noopener noreferrer" ' }}</div>
      </div>
      {% endfor %}
    {% else %}
      <!-- Fallback sample items if no `_data/news.yml` present -->
      <div class="news-item">
        <div class="news-date">May 12, 2025</div>
        <div class="news-body">NA.</div>
      </div>
    {% endif %}
  </div>
</section>

    
## Publications

{% include publications-content.html %}
