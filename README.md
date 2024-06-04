## How do I use this?

Create a new folder for your project and run the following command:

```
git clone https://github.com/dachendev/odin-webpack-starter [folder-name]
```

## How do I publish to GitHub Pages?

If you'd like to publish your dist folder to GitHub pages, do the following:

1. Remove dist from your gitignore file
2. Run `npm run build`
3. Commit & push the latest build
4. Run `git subtree push --prefix dist origin gh-pages`