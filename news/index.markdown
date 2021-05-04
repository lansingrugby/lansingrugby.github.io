---
layout: default
---
<section class="section">
       <div class="content">
          <ul>
          {% for post in site.categories.news %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
          </ul>
        </div>
</section>
