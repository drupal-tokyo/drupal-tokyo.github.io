# Drupal Meetup Tokyo の Webページ

Drupal Meetup Tokyo の Webページ [drupal-tokyo.github.io](https://drupal-tokyo.github.io/) は Astro Starter Kit: Blog をベースに構築されています。

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

### 運用メモ

- `src/pages/blog/` 以下に活動記録などのコンテンツを作成していきます。
- ファイル形式は`.md`でお願いします。（要Front Matter）
- 拡張子を除くファイル名がブログ記事のURLになります。（`meetup-72.md` は `/blog/meetup-72`）


#### Front Matterサンプル

```yaml
---
layout: "../../layouts/BlogPost.astro"
title: "Drupal Meetup Tokyo #72"
description: "Drupal Meetup Tokyo #72がオンラインで開催されました。"
pubDate: "2022/10/06"
# heroImage: "/placeholder-hero.jpg" この様にコメントアウトも可能
---
```


## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
