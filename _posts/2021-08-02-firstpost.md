---
layout: post
title: "ブログ作成"
date: 2021-08-02 22:00
---

# ブログ作成
2021-08-02 22:00  

Githubを使ってブログを作ってみようと思います。  
調べながらjekyllで管理してみます。  
更新環境はこんな感じです  
- PC:dell studio 1537
- CPU:Core™2 Duo CPU P8400
- メモリ:4GB
- OS:Pop!_OS 20.04 LTS
- editor:Atom

2009年に購入したパソコンを現在も使用しています。  
HDDをSSDにした以外は何もしていません。何年使えるんだろ。  

[TOP](https://mgrsn.github.io)  

記事一覧  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
