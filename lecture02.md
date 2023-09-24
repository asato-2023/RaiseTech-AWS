# 第2回課題

## 第2回講座での学び

### Git/GitHubとSVNの違い
 - ローカルリポジトリの存在
 - ブランチの扱い
 - commitの意味の違い
 - ファイルをロックして編集ができないので複数人で同じファイル操作すると競合する
 
 ### GitとGitHubの関係（簡単に）
  - GitHubはバージョン管理データを格納するWebサービス
  - Gitはバージョン管理するツール
  - GitHubを介して開発者間でデータの共有ができる
 
 ### Gitコマンド（使ったもの）
  - バージョン確認：git --version
  - GitHubからクローン：git clone "GitHubで確認したclone用URLなど"
  - ブランチ作成や現在位置確認：git branch
  - ブランチの切り替え：git checkout
  - ユーザ名設定：git config --global user.name "設定するユーザー名"
  - メールアドレス設定：git config --global user.email "設定するメールアドレス"
  - configの設定確認：git config --global -list
  - ファイルの登録：git add
  - ファイルのコミット：git commit
  - リモートにプッシュ：git push

### 感想
　SVN以外を使ったことがなかったため、そのイメージがなかなか払拭できず
　ローカルリポジトリ、ブランチの扱いに混乱した。  
　UdemyのGit講座を視聴して、順を追って仕組みを学習したので課題開始時よりは
　理解できたと思う。  
　SVNと比較すると難しいと感じた。
　