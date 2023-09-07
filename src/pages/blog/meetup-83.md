---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #83"
description: "Drupal Meetup Tokyo #83がオンラインで開催されました。"
pubDate: "2023/9/07"
---

## よもやま話

- プライベートでモジュール作ってる話
    - テーマのリージョンにHTMLタグをラップできるモジュール
    - ViewsとかコンテンツタイプにHTMLタグ付けられるモジュールはあるけど、リージョンに対してできるものは現状なかった
    - コントリビュートモジュールにしたい
    - [https://www.drupal.org/project/drupal/issues/3087036](https://www.drupal.org/project/drupal/issues/3087036)
- 将来的にDrupal.orgからサンドボックスプロジェクトがなくなるらしい

## Drupal.orgでのGitlab CI有効化について

- [https://www.drupal.org/node/3374527?no_cache=1694083479](https://www.drupal.org/node/3374527?no_cache=1694083479) DrupalCIからGitLabCIに移行
- Drupal CIとは？
    - 現状、Drupalが独自にCI機能を持っていて、例えばコントリビュートモジュールにパッチが提供されるとCIが回ってpass/failとか出てくる
    - これからCI機能もGitLabに移行していく
- DrupalのコントリビュートプロジェクトでGitLab CIを使うには
    - コントリビュートプロジェクトにテンプレートファイル(.gitlab-ci.yml)を追加する
- 上のモジュール作ってる話に関連して・・・
    - テーマにサードパーティー設定(third_party_settings)が含まれているとテストがこけるissue
    - [https://www.drupal.org/project/drupal/issues/3087036](https://www.drupal.org/project/drupal/issues/3087036)
- GitLab CIのテンプレートファイルの中身
    - [https://git.drupalcode.org/project/gitlab_templates/-/blob/1.0.x/gitlab-ci/template.gitlab-ci.yml?ref_type=heads](https://git.drupalcode.org/project/gitlab_templates/-/blob/1.0.x/gitlab-ci/template.gitlab-ci.yml?ref_type=heads)
- Drupal.orgとGitLabのインレグレーションが進んでいる
    - [https://twitter.com/DropIsMoving/status/1698744814110429568](https://twitter.com/DropIsMoving/status/1698744814110429568)
- GitLab CIをローカルで動かす
    - [https://github.com/firecow/gitlab-ci-local](https://github.com/firecow/gitlab-ci-local)
- ↑の話から脱線して、AWSをローカルで動かすツール
    - [localstack/localstack: 💻 A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline (github.com)](https://github.com/localstack/localstack)

## その他、よもやま

- ブラウザの話
- IDEの話
- プライベートでGithub Copilotを使ってUnity開発してる話
- [https://docs.github.com/ja/copilot/github-copilot-chat/using-github-copilot-chat](https://docs.github.com/ja/copilot/github-copilot-chat/using-github-copilot-chat)


## 次回
- [Drupal Meetup Tokyo #84](https://drupal-tokyo.connpass.com/event/295832/)
    - 10/5 (木) 19:30 〜 オフライン開催予定!
    - WeeklyDropを眺める
    - 最新モジュールを眺める
    - Drupalの求人情報を見てみる
