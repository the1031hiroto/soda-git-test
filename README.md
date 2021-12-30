# githhub練習
## ターゲット
githubでレポジトリ作成、ブランチ作成、プルリクエスト作成をやってみたい or 練習したい人

## 新規追加練習
※ (sh) = コマンド, (bw) = ブラウザ (あくまで参考なので違う方法で行っても可)
### githubでレポジトリを作成する(bw) 
Add a README fileはチェックしない。
CF. https://docs.github.com/ja/repositories/creating-and-managing-repositories/creating-a-new-repository

### レポジトリ作成後に表示されるページのコマンドを参考にREADME.mdのみをコミットする。(sh)
README.md以外のを絶対にコミットに含めない。
CF. https://docs.github.com/ja/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line

### ブランチを作成(sh)
ブランチ名は何をするのか分かりやすくする。ex) feature/add_html_with_bootstrap, feature/create_vue_app, etc
命名規則はプロジェクトによるが"feature/*"にしとけばおkだと思ってる。(個人の感想)
CF. https://qiita.com/c6tower/items/fe2aa4ecb78bef69928f

### 何か追加
出来るだけフレームワークの使用をおすすめします。
https://getbootstrap.jp/docs/5.0/getting-started/download/
https://github.com/vuejs/vue-cli/tree/v2#vue-cli--


### 作成したブランチにコミットする(sh)
コミット単位は出来るだけ小さくする。ex) add html, add css, update header, fix get function, etc
file uploadは使用しないこと
練習や学習の意味でSSHでコマンドで行うことをおすすめするが、VSCodeの拡張機能やGithub Descktopを使うのもなしではない

### リモートにプッシュする(sh)

### プルリクエスト(以後PR)を作成する(bw) 
レビュワーに追加して貰えればレビューします。
ID: the1031hiroto

PRに含めるもの
- 概要の記載
```
# 修正内容

# 困ったこと(追加内容以外のgithubの操作なども含む)

# 参考にしたもの
```
- 動作確認した時のスクリーンショット

CF. https://github.com/the1031hiroto/soda-git-test/pull/1

