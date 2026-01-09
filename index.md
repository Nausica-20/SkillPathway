---
layout: splash
title: "SkillPathway"
header:
  overlay_color: "#1A2A40"
  overlay_filter: "0.35"
  overlay_image: /SkillPathway/assets/images/header.png
excerpt: "Your pathway to better skills and a better career."
permalink: /SkillPathway/
---

<div class="hero-sp">
  <h1>Build Skills. Grow Your Career.</h1>
  <p>Free tools, curated learning paths and practical guidance to help you thrive in the modern workplace.</p>
  [Explore Paths](/SkillPathway/#){: .btn-sp }
  [Browse Resources](/SkillPathway/resources/){: .btn-sp }
</div>

---

## Start Your Journey

<div class="section-sp">
  <h2>{: .fa-solid .fa-compass } Start Here</h2>
  Choose a learning path tailored to your goals and start building practical skills today.
  <br><br>
  [Explore Learning Paths](/SkillPathway/#){: .btn-sp }
</div>

---

## Popular Skill Categories

<div class="card-grid">

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-laptop-code }</div>
    <h3>Digital Skills</h3>
    <p>Hands-on tutorials and projects to master web, data and automation tools.</p>
    [Learn More](/SkillPathway/digital-skills/){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-briefcase }</div>
    <h3>Career Development</h3>
    <p>CV, interviews, networking and strategies to accelerate your professional growth.</p>
    [Start Growing](/SkillPathway/career-development/){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-comments }</div>
    <h3>Soft Skills</h3>
    <p>Communication, leadership and teamwork exercises you can practice every day.</p>
    [Improve Skills](/SkillPathway/soft-skills/){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-graduation-cap }</div>
    <h3>Free Courses</h3>
    <p>Curated list of free, high-quality courses from trusted platforms.</p>
    [Browse Courses](/SkillPathway/free-courses/){: .btn-sp }
  </div>

</div>

---

## Featured Resources

<div class="section-sp-dark">
  <h2>{: .fa-solid .fa-star } Top Tools & Resources</h2>
  A curated selection of tools, cheat sheets and platforms to accelerate your learning.
  <br><br>
  [View Resources](/SkillPathway/resources/){: .btn-sp }
</div>

---

## Latest Articles

{% if site.posts.size > 0 %}
  <div class="latest-posts">
    {% for post in site.posts limit:3 %}
      <div class="post-preview">
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
        <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
      </div>
    {% endfor %}
  </div>
{% else %}
  <div class="section-sp">
    <p>No articles yet — start your first post in <code>_posts/</code> to show up here.</p>
  </div>
{% endif %}

---

<footer class="site-footer" style="margin-top:40px; text-align:center; font-size:0.95rem;">
  <p>© {{ site.time | date: "%Y" }} SkillPathway. Powered by Jekyll & Minimal Mistakes.</p>
  <p>
    <a href="/SkillPathway/feed.xml" title="Feed">{: .fa-solid .fa-rss } Feed</a>
    &nbsp;•&nbsp;
    <a href="/SkillPathway/about/">About</a>
    &nbsp;•&nbsp;
    <a href="/SkillPathway/resources/">Resources</a>
  </p>
</footer>    <h3>Digital Skills</h3>
    <p>Build essential digital abilities for modern careers.</p>
    [Learn More](#){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-briefcase }</div>
    <h3>Career Development</h3>
    <p>Grow your professional profile and unlock new opportunities.</p>
    [Start Growing](#){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-comments }</div>
    <h3>Soft Skills</h3>
    <p>Improve communication, leadership, and teamwork.</p>
    [Improve Skills](#){: .btn-sp }
  </div>

  <div class="card-sp">
    <div class="card-icon">{: .fa-solid .fa-graduation-cap }</div>
    <h3>Free Courses</h3>
    <p>Access curated free courses from trusted platforms.</p>
    [Browse Courses](#){: .btn-sp }
  </div>

</div>

---

## Featured Resources

<div class="section-sp-dark">
  <h2>{: .fa-solid .fa-star } Top Tools & Resources</h2>
  Discover the best tools to accelerate your learning and career growth.
  <br><br>
  [View Resources](#){: .btn-sp }
</div>
