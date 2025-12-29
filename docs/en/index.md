---
layout: default
lang: en
title: "Still Time Studio - English"
---


<section id="site-intro">
    <h2>About This Site</h2>
    <p>
    Welcome to Still Time Studio. This site features our simple and friendly meditation timer app, "Still Time."<br>
    The app is designed to help you integrate mindfulness into your daily routine and support your mental well-being.<br>
    Visit the detail page to learn more about the app's features and the developer's vision.
</p>
</section>

<section id="meditation-timer">
    <img src="/images/meditation_timer/meditation_timer_icon.png" alt="Still Time app icon" class="app-icon">
    <h2>Still Time / わたし時間</h2>
    <p>A user-friendly interface with breathing-support animation and gentle sounds to enhance your meditation practice.</p>
    <a href="/meditation_timer" class="detail-link">View Details</a>
</section>

<section id="log-editor-tool">
    <h2>Meditation Log Editor Tool</h2>
    <p>This external tool allows you to edit the JSON data exported from the "Still Time" app directly in your browser. Useful for manually correcting records, batch deletion, or restoring backups.</p>
    <a href="/en/log_editor_en.html" class="detail-link">Access the Tool</a>
</section>

<section id="updates">
    <h2>📣 Latest Updates & Dev Notes</h2>

    <ul class="post-list">
      {% assign english_posts = site.posts | where: "lang", "en" %} 
      {% for post in english_posts reversed limit: 5 %} 
        <li>
          <span class="post-meta">
            {{ post.date | date: "%B %d, %Y" }}
          </span>

          <h3>
            <a class="post-link" href="{{ post.url | relative_url }}">
              {{ post.title }}
            </a>
          </h3>
          
        </li>
      {% endfor %}
    </ul>
    
    <p><a href="/blog/">→ View All Posts</a></p>
</section>

<section id="support-qa">
    <h2>Support & Q&A</h2>
    <p>Have questions or feedback about the apps? Feel free to reach out.</p>
    <a href="mailto:kazunakka.contact@gmail.com" class="x-link">
        Contact via Email
    </a>
</section>