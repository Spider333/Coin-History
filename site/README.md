### Site Generator

Use the root README.md as source and generate a styled static site (using nuxt.js)

```
cd site
yarn install
yarn run dev
```

To generate the static site for deployment

```
yarn run generate:gh-pages
yarn run deploy:gh-pages
```

Running the deploy command automatically pushes the generated static site to a branch `gh-pages`
