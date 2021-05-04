---
layout: default
active: home
---
<section class="section">
<div class="columns">

  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title">
          News
        </p>
      </header>
      <div class="card-image">
        <figure class="image">
          <img src="{{site.url}}/assets/images/news_link.png" alt="Rugby News">
        </figure>
      </div>
      <div class="card-content">
        <p>Recent Crisis Rugby News</p>
        <div class="content">
          <ul>
          {% for post in site.categories.news %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
          </ul>
        </div>
      </div>
      <!--footer class="card-footer">
        <a href="{{site.url}}/news/" class="card-footer-item">All News</a>
      </footer-->
    </div>
  </div>
  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title">
          Events
        </p>
      </header>
      <div class="card-image">
        <figure class="image">
          <img src="{{site.url}}/assets/images/events_link.png" alt="Team Events">
        </figure>
      </div>
      <div class="card-content">
        <p>Upcoming Events</p>
        <div class="content">
          <ul>
          {% for post in site.categories.events %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
          </ul>
        </div>
      </div>
      <!--footer class="card-footer">
        <a href="{{site.url}}/events/" class="card-footer-item">All Events</a>
      </footer-->
    </div>
  </div>
  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title">
          Games
        </p>
      </header>
      <div class="card-image">
        <figure class="image">
          <img src="{{site.url}}/assets/images/games_link.png" alt="Games">
        </figure>
      </div>
      <div class="card-content">
        <p>Upcoming Games and Recaps</p>
        <div class="content">
          <ul>
          {% for post in site.categories.games %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
          </ul>
        </div>
      </div>
      <!--footer class="card-footer">
        <a href="{{site.url}}/games/" class="card-footer-item">All Games</a>
      </footer-->
    </div>
  </div>
</div>
</section>
