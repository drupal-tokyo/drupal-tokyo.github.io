---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #100"
description: "Drupal Meetup Tokyo #100 が開催されました。"
pubDate: "2025/2/6"
---

## これまでのMeetup Tokyo振返り

- 祝・100回  
- これまでのMeetup, 会話したこと  
- 運営からのおしらせ  
  - これからは２ヶ月に１度に  
  - メンバ募集

## よもやま話

- 岩嵜さんのD7移行近況  
- 移行に伴って、検索結果が変わってしまうことによる影響は？  
  - 無料会員はGoogleの検索機能。有料会員だけDrupalの検索機能  
- Acquia SearchがApache Solrから変わる？  
  - [https://www.linkedin.com/posts/buytaert\_acquia-adds-ai-search-to-platform-with-searchstax-activity-7290496091601469440-a40T?utm\_source=share\&utm\_medium=member\_desktop](https://www.linkedin.com/posts/buytaert_acquia-adds-ai-search-to-platform-with-searchstax-activity-7290496091601469440-a40T?utm_source=share&utm_medium=member_desktop)

## アドベントカレンダー

- [Drupal/OpenAI/Pineconeで検索機能を作る](https://scrapbox.io/kazunoko/Drupal%E3%80%81OpenAI%E3%80%81Pinecone_%E7%94%9F%E6%88%90AI%E3%81%AE%E6%A4%9C%E7%B4%A2%E6%A9%9F%E8%83%BD%E3%82%92%E4%BD%9C%E3%82%8B)  
  - RAGのためのベクトルDBをDrupalで作るためのモジュールがある  
  - Search APIベース  
- [Search APIを拡張して日本語の正規化処理を適用するモジュールを開発しました](https://www.studio-umi.jp/blog/14/810)  
  - 表記揺れを解決するために正規化する  
  - Search APIのプロセッサーとして機能するモジュール公開  
- [DrupalCon Singapore 2024 参加レポート](https://www.studio-umi.jp/blog/186/808)  
  - DrupalCon Singapore 2024に参加した話  
- [Drupalの日本語検索、ちゃんと動いてる？N-gramの課題と自然言語処理での改善策](https://www.studio-umi.jp/blog/12/809)  
  - 日本語を意味のある単語に分割するのは難しい  
  - 自然言語処理をすることで解消。2つのアプローチ  
    - 機械学習  
    - 形態素解析  
- [Drupalの日本語検索を改善！自然言語処理を活用したSearch API Japanese Tokenizerモジュールの紹介](https://www.studio-umi.jp/blog/14/811)  
  - Search APIベースのトークナイザーをモジュールとして公開  
  - 各トークナイザーの検索性能の比較  
  - データセットのベンチマークを客観的に評価できるサイト  
    - [https://research.nii.ac.jp/ntcir/index-ja.html](https://research.nii.ac.jp/ntcir/index-ja.html)  
- [生成AIと管理者権限ないけど現場でキャッシュクリアさせたいお話](https://qiita.com/bassline121/items/1a0b4728a75890627803)  
  - コンテンツを更新してもブラウザキャッシュで反映されない  
  - ChatGPTを駆使して、管理者じゃなくてもキャッシュを全クリアできる権限を付与できるカスタムモジュールを作成  
- [ddev で drupal11 サイトを素直に立ち上げられなかった件](https://hyogo.dev/article/2025-02-03/ddev-te-drupal11-saitowosuzhinilichishangkerarenakatsutajian)  
  - 要件定義書を作る上でDrupal画面のスクショが欲しい時がある  
  - Finderが.DS\_Storeがあると composer createが実行できなかった  
  - ddevが立ち上がるまでFinderをみないことが大事\!

## 次回

- 4/3 (木) 19:30〜21:00
- DrupalCon Atlanta 2025 Recap!
- https://drupal-tokyo.connpass.com/event/345293/
