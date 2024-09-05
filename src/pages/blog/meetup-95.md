---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #95"
description: "Drupal Meetup Tokyo #95 が開催されました。"
pubDate: "2024/9/5"
---

## 近況・よもやま話

- はじめて自社でテーマ作ってみた
  - Drupal 10 標準テーマをベーステーマ
  - ベーステーマにBarrioを使う人が多い
  - Tailwind CSS使ってる（iさん）
  - Twigはデザイナーに嫌われる
- D7 -> D10移行
  - ローカル環境で、コンテンツの移行に十何時間かかる
  - 70万ノードあるサイト
  - 本文内に残る自由なスタイル（HTML/CSS）問題
- Drupalコアの試験的モジュール「Package Manager」は、マルチサイト化では動かない
  - Add Alpha level Experimental Package Manager module [#3346707] | Drupal.org 
    - https://www.drupal.org/project/drupal/issues/3346707
  - コードが更新されて、updatedbを全部のサイトで行う必要があるが、その制御がないため
  - What’s Cooking with the Events Recipe for Drupal CMS
    - https://www.mandclu.com/blog/whats-cooking-events-recipe-drupal-cms	
- Drupal Associationの選挙
  - https://www.drupal.org/elections2024

## 次回

- [Drupal Meetup Tokyo #96](https://drupal-tokyo.connpass.com/event/330333)
- 10/3 (木) 19:30 〜 21:00
- DrupalCon Singapore 2024 のセッション
