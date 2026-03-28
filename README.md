# wdhsieh-blog

A Hexo blog scaffold inspired by the overall stack/style of `blog.kyomind.tw`.

## Stack
- Hexo
- Even theme
- GitHub Pages
- GitHub Actions deploy
- Atom feed
- Sitemap

## Local preview
```bash
npm install
npx hexo clean
npx hexo server
```

## Build
```bash
npx hexo generate
```

## Deploy
Push to `main`, then GitHub Actions will build and publish to GitHub Pages.

Expected site URL:
- https://mactone.github.io/wdhsieh-blog/
