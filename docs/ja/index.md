---
layout: default
title: アプリ総合窓口
---
<section id="site-intro">
    <h2>このサイトについて</h2>
    <p>このサイトでは、わたしが個人的に開発したアプリを紹介しています。<br>
        日々の暮らしを少し豊かにするツールや、楽しみながら学べるゲームなど、シンプルで親しみやすいアプリを公開しています。<br> 興味のあるアプリがあれば、ぜひ詳細ページをご覧ください。
    </p>
</section>

<section id="meditation-timer">
    <img src="/images/meditation_timer/meditation_timer_icon.png" alt="瞑想タイマーのアイコン" class="app-icon">
    <h2>わたし時間 / Still Time</h2>
    <p>使いやすいインターフェース。呼吸をサポートするアニメーションと、穏やかなサウンドで、あなたの瞑想をサポートします。</p>
    <a href="/ja/meditation-timer-jp" class="detail-link">詳細を見る</a>
</section>

<section id="log-editor-tool">
    <h2>瞑想ログ編集ツール</h2>
    <p>「わたし時間」アプリでエクスポートしたJSONデータをブラウザ上で直接編集できる外部ツールです。手動でのデータ修正や、一括削除、復元などに便利です。</p>
    <a href="/ja/log_editor.html" class="detail-link">ツールにアクセスする</a>
</section>

<section id="updates">
    <h2>📣 更新情報</h2>

    <ul class="post-list" style="list-style: none; padding: 0;">
      {% for post in site.posts reversed limit: 5 %} 
        <li>
          <span class="post-meta" style="color: #666; font-size: 0.9em;">
            {{ post.date | date: "%Y年%m月%d日" }}
          </span>

          <h3 style="margin-top: 5px; margin-bottom: 5px;">
            <a class="post-link" href="{{ post.url | relative_url }}">
              {{ post.title }}
            </a>
          </h3>
          
          </li>
        <hr style="border: 0; border-top: 1px solid #eee; margin: 10px 0;">
      {% endfor %}
    </ul>
    <p><a href="/blog/">→ すべての記事を見る</a></p>
</section>

<section id="support-qa">
    <h2>サポート・Q&A</h2>
    <p>アプリについてご質問やご意見がございましたら、お気軽にお声がけください。</p>
    <a href="mailto:kazunakka.contact@gmail.com" class="x-link">
        お問い合わせメール
    </a>
</section>