### Site Generator

Automatically use the [root README.md](../README.md) as source and generate a styled static site (using nuxt.js) from it.

```
yarn install
yarn run dev
```

To generate the static site for deployment

```
yarn run generate:gh-pages
yarn run deploy:gh-pages
```

Running the deploy command automatically pushes the generated static site to a branch `gh-pages`
