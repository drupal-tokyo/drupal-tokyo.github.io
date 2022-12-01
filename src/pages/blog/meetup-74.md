---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #74"
description: "Drupal Meetup Tokyo #74がオンラインで開催されました。"
pubDate: "2022/12/1"
---

## よもやま話

- Drupal Advent Calendar 2022
    - [https://qiita.com/advent-calendar/2022/drupal](https://qiita.com/advent-calendar/2022/drupal)

## おすすめモジュール・テーマ

- Twig Tweak
    - [https://www.drupal.org/project/twig_tweak](https://www.drupal.org/project/twig_tweak)
- Azure ADとつなぐ
    - [Guide for Drupal Single Sign On (SSO) using Azure AD as Identity Provider (IdP) | SAML SP Single Sign On (SSO) - SAML Service Provider | Drupal Wiki guide on Drupal.org](https://www.drupal.org/docs/contributed-modules/saml-sp-single-sign-on-sso-saml-service-provider/guide-for-drupal-single-sign-on-sso-using-azure-ad-as-identity-provider-idp)
    - LDAP、SAMLできる
    - Social Auth Microsoft
        - [https://www.drupal.org/project/social_auth_microsoft](https://www.drupal.org/project/social_auth_microsoft)
    - Drupalと他の認証システムと連携するモジュールはどれもそこそこ安定している
- Group
    - [https://www.drupal.org/project/group](https://www.drupal.org/project/group)
    - Version3.0 で大きく変わる。
- Subgroup
    - [https://www.drupal.org/project/subgroup](https://www.drupal.org/project/subgroup)

## Drupal の Blue/Green デプロイを考える

- updb時にメンテナンスモードになる
- Fastly(Varnish) キャッシュ. Webサーバから200でなかったら古いキャッシュを返す.という機能を利用する
- コード・DBともに2系統もって切り替える
- [【衝撃】AWSのRDSがデータを失わないBlue/Greenデプロイに対応しました #reinvent | DevelopersIO (classmethod.jp)](https://dev.classmethod.jp/articles/rds-bg-deploy/)

## 次回

1月12日(木) 19:30 〜 オンライン

- [Drupal Advent Calendar 2022](https://qiita.com/advent-calendar/2022/drupal) の振り返り
- Drupal10
- [DrupalCamp DEN 2023 Iwakuni](https://drupal-camp2023.den-japan.org/) のタイムテーブルをみよう
