---
layout: default
title: アプリ総合窓口
---
<section id="site-intro">
    <h2>このサイトについて</h2>
    <p>
    このサイトでは、シンプルで使いやすい瞑想タイマーアプリ「Still Time」を紹介しています。<br>
    日々の生活に静かな時間を取り戻し、心を整えるサポートを目的としたアプリです。<br>
    詳細ページでは、アプリの機能や開発者の想いについて詳しく紹介しています。
</p>
</section>

<section id="meditation-timer">
    <img src="/images/meditation_timer/meditation_timer_icon.png" alt="瞑想タイマーのアイコン" class="app-icon">
    <h2>Still Time</h2>
    <p>使いやすいインターフェース。呼吸をサポートするアニメーションと、穏やかなサウンドで、あなたの瞑想をサポートします。</p>
    <a href="/ja/meditation-timer-jp" class="detail-link">詳細を見る</a>
</section>

<section id="log-editor-tool">
    <h2>データ管理ツール</h2>
    <p>瞑想ログの管理に便利な2つのツールをご用意しています。アプリでエクスポートしたJSONデータをブラウザ上で編集・変換できます。大量データの一括編集やスプレッドシートでの分析、特定ログの素早い修正など、用途に応じてお選びいただけます。</p>
    <a href="/ja/tools/" class="detail-link">ツールにアクセスする</a>
</section>

<section id="updates">
    <h2>📣 更新情報</h2>

    <ul class="post-list">
      {% assign japanese_posts = site.posts | where: "lang", "ja" %} 
      {% for post in japanese_posts limit: 5 %}
        <li>
          <span class="post-meta">
            {{ post.date | date: "%Y年%m月%d日" }}
          </span>

          <h3>
            <a class="post-link" href="{{ post.url | relative_url }}">
              {{ post.title }}
            </a>
          </h3>
          
        </li>
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