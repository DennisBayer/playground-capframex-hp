<h1>Announcements</h1>

<section class="main-content">
  {% for post in site.posts %}
  <article>
    <header>
      <small><time>{{ post.date | date: "%b %-d, %Y" }}</time></small>
    </header>
    <section>
      <p>{{ post.content}}</p>
    </section>
  </article>
  <hr>
  {% endfor %}
</section>