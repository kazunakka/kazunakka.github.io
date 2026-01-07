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

<section id="log-editor-tool">
    <h2>Data Management Tools</h2>
    <p>We provide two convenient tools for managing your meditation logs. Edit and convert JSON data exported from the app directly in your browser. Choose the right tool for your needs—bulk editing and analysis in spreadsheets, or quick edits to specific logs.</p>
    <a href="/en/tools/" class="detail-link">Access the Tools</a>
</section>

<section id="log-editor-tool">
    <h2>Meditation Log Editor Tool</h2>
    <p>This external tool allows you to edit the JSON data exported from the "Still Time" app directly in your browser. Useful for manually correcting records, batch deletion, or restoring backups.</p>
    <a href="/en/tools-portal-en.html" class="detail-link">Access the Tool</a>
</section>

<section id="updates">
    <h2>📣 Latest Updates & Dev Notes</h2>

    <ul class="post-list">
      {% assign english_posts = site.posts | where: "lang", "en" %} 
      {% for post in english_posts limit: 5 %} 
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