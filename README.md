# book-of-light dist bundle

expo export --public-url https://sillyleo.github.io/bol-dist

然後把 dist 內容放到這個資料夾裡。

expo build:android --public-url https://sillyleo.github.io/bol-dist/ios-index.json

expo build:ios --public-url https://sillyleo.github.io/bol-dist/ios-index.json
