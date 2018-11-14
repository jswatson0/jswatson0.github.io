---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: maintenance
---
<div>
  {% for post in site.posts %}
    
      <div>
      <h1>{{post.title}}</h1>
      {{ post.content }}
      </div>
  <hr>
  {% endfor %}
</div>

