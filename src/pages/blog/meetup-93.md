---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #93"
description: "Drupal Meetup Tokyo #93 が開催されました。"
pubDate: "2024/7/4"
---

## よもやま話

- Ployfillの対応
    - [https://gigazine.net/news/20240702-namecheap-polyfill-io-supply-chain-attack/](https://gigazine.net/news/20240702-namecheap-polyfill-io-supply-chain-attack)
- Display Suite
    - [https://www.drupal.org/project/ds](https://www.drupal.org/project/ds)
    - Layout Builderよりも機能が多くて、サイトビルダーが喜ぶ


## Drupal11の話

- State APIのキャッシュ有効化
    - Drupal 11でデフォルトで有効
    - 副作用が気になる -> Drupal 10.3で動作検証した方が良さそう
- ログアウトのCSRF導入
    - Twigでベタ書きしているリンクがあると確認画面が発生する -> ユーザーマニュアル更新するか、Twig修正する
- Navigationモジュールの登場
    - Admin toolbarではキャッシュクリアのURL(Controller)が提供されていたことが知った
- Workspacesモジュール
    - 新しいサイトで、ワークフローの代替として使えそう
- DrupalのプロファイルがUIから削除できるようになった
    - [https://www.drupal.org/blog/drupal-10-3-0](https://www.drupal.org/blog/drupal-10-3-0)
- Drupal 11のアップグレード
    - PHP 8.3とDrupal 10.3は早めにアップデートして、様子を見る
    - 2025年後半〜2026年前半がDrupal 11へのアップグレード好機かも
    - Redhat系 -> MariaDB、linux系 -> MySQL が多い印象
    - Drupal 11はまだjQueryに依存。Form APIの#statesとか


## 次回

- [Drupal Meetup Tokyo #94](https://drupal-tokyo.connpass.com/event/324461)
- 8/1 (木) 19:30 〜 21:00
- Drupal Starshotイニシアチブを追ってみる
