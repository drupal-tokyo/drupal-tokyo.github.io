---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #87"
description: "Drupal Meetup Tokyo #87 新年会！ がオフラインで開催されました。"
pubDate: "2024/1/11"
---
## よもやま相談

- GmailのDMARC(Domain-based Message Authentication, Reporting and Conformance)対応
  - https://www.m3tech.blog/entry/2023/10/24/110000
  - https://www.nikkei.com/article/DGXZQOUC157PB0V11C23A2000000/
  - GoogleのGmailとYahoo メール がこの対応しないとメールを破棄してしまう。
  - https://www.mailgun.com/blog/deliverability/implement-dmarc/
- D9 -> D10への移行時に、使っていないモジュールを削除するのが大変だった
   - その時に、drush cr を1回やってダメだったから諦めてたら、drush crを5回やるとうまく行った
   - キャッシュの再構築が途中で止まってしまう時がある
- Drush Launcher が使えなくなる話
  - https://scrapbox.io/kazunoko/Drush_Launcher_が使えなくなるよという話
- Dries来日記念イベント開催!
  - 開催日時: 2023/3/14 18:00 -21:00
  - 開催場所: LINEヤフー株式会社

## Drupal Advent Calendar
  - [Drupal.org へのモジュールプロジェクトの作成と編集](https://zenn.dev/tom_konda/articles/da043971719eff)

## 次回

- [Drupal Meetup Tokyo #88](https://drupal-tokyo.connpass.com/event/307520/)
- 2/1 (木) 19:30 〜
- [Advent Calendar 2023 の続き](https://qiita.com/advent-calendar/2023/drupal)
