---
layout: base
---
<div class="main-col" aria-label="Content">
  <h2>Hi, We are a group of students from Sunway University.</h2>
  <p>Here we share our thoughts and process while contributing to the community.</p>

  <h1 class="title has-text-centered">Posts</h1>
  <table class="table">
  {% for post in site.posts %}
    {% include component/post_title.html post=post %}
  {% endfor %}
  </table>
</div>

