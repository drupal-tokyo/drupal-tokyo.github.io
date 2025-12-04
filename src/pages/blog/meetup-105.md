---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #105"
description: "Drupal Meetup Tokyo #105 が開催されました。"
pubDate: "2025/12/4"
---
## よもやま話

* [CVE-2025-55182](https://www.cve.org/CVERecord?id=CVE-2025-55182)  
  * [Next.js](https://www.drupal.org/project/next) モジュールもクリティカルがあった[https://www.drupal.org/sa-contrib-2025-122](https://www.drupal.org/sa-contrib-2025-122)  
* セキュリティ通知がきた時の対応はどうする?  
  * 古いシステムでSQLインジェクションが検知された段階でサイト停止、すぐ対策して公開  
  * セキュリティ通知がきたら即対応 or まず判断、定期リリースに載せる、よく使う機能は即対応 など  
  * WAF があれば安心  
* 過度なクローリング発生 → コスト感をユーザーに公開して、有志の自警団のおかげで解決したことがある  
* Drupalログイン画面を閉じる、閉じない?  
  * CDNで社内からのみアクセス可能にしている  
  * 管理サーバーを分けてログインは管理サーバー側だけ開ける.  
  * [README.md](http://README.md) とかが公開されているのがイマイチと思いつつ、対費用効果が・・・  
  * [drupal-paranoia](https://github.com/drupal-composer/drupal-paranoia)  
* セキュリティ強化  
  * [https://www.drupal.org/steward](https://www.drupal.org/steward)  
* OWASP ZAP  
* AI チャットボットよりGoogleのように検索させて結果とまとめを表示する方が、体感が良さげ

## DrupalCon Nara行ってきた話

* Youtube [https://www.youtube.com/playlist?list=PLpeDXSh4nHjSb2nYlToJvaD84PKoouf7c](https://www.youtube.com/playlist?list=PLpeDXSh4nHjSb2nYlToJvaD84PKoouf7c)  
* 写真 [https://www.flickr.com/groups/drupalconnara2025/](https://www.flickr.com/groups/drupalconnara2025/)  
* 記憶に残ったセッション  
  * 多言語化の課題 https://events.drupal.org/nara2025/session/global-reach-one-platform-journey-implementing-multilingual-drupal-cms  
  * Drupal Canvas

## 次回

* 2025/02/05(木) 19:30 〜 21:00   
* テーマ  
  * みんなの開発環境をシェア  
* https://drupal-tokyo.connpass.com/event/378051/