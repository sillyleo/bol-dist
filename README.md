# book-of-light dist bundle

expo export --public-url https://sillyleo.github.io/bol-dist

然後把 dist 內容放到這個資料夾裡。

expo build:android --public-url https://sillyleo.github.io/bol-dist/android-index.json

expo build:ios --public-url https://sillyleo.github.io/bol-dist/ios-index.json

從本機端讀取 github self hosting url 網址是：

exps://sillyleo.github.io/bol-dist/android-index.json
exps://sillyleo.github.io/bol-dist/ios-index.json

貼上瀏覽器就可以。

開發的時候還是用 local。只有要出版才要這樣。
