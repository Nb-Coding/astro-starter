# Astro Starter Kit: Minimal

> 🧑‍🚀 **Ready for launch?** Check your Astro version before you begin!

## 🚀 Getting started

プロジェクトのルートで依存パッケージをインストールし、Astroのバージョンを確認します。

```sh
npm install
npx astro --version
npm view astro version
```

`npx astro --version` はこのプロジェクトで使うバージョン、`npm view astro version` は公開されている最新版を表示します。更新する場合は、下の「Updating Astro」を参照してください。

確認が済んだら、開発サーバーを起動します。

```sh
npm run dev
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where you can put reusable components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

Run these commands from the root of your project:

| Command | Action |
| :-- | :-- |
| `npm install` | Install dependencies |
| `npm run dev` | Start the local server at `localhost:4321` |
| `npm run build` | Build the site to `./dist/` |
| `npm run preview` | Preview the built site |

## 🔄 Updating Astro

When you want to update Astro and its official integrations:

```sh
npx @astrojs/upgrade
npm run build
```

## 👀 Want to learn more?

Visit the [Astro documentation](https://docs.astro.build) or join the [Discord server](https://astro.build/chat).
