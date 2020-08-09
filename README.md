# blog
## 概容
このレポジトリはpythonライブラリpelicanを使用して備忘録を残しています。
https://ta2gawa.github.io/blog/ から閲覧できます。

## 更新方法
1. content/以下にmdファイルを作成する
1. `$ pelican content`
1. ローカル検証するならば `$ pelican --listen`
1. gh-pagesブランチにoutputを反映 `$ ghp-import output -b gh-pages`
1. `git push origin gh-pages`

