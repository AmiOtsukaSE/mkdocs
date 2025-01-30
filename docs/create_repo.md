# リポジトリすらない状況でローカルからGitHubに上げる方法

## 1. GitHubで新規リポジトリを作成 (例: github-practice-docs)

「Initialize this repository with a README」はチェックを外しておく（空リポジトリ）

## 2. ローカルの、gitで管理したいフォルダで、Gitを初期化
このディレクトリは、gitで管理したいフォルダで、GitHubに載せるもの。

`cd project_directory`
`git init`


## 3. 必要ファイルをGit管理下に追加してコミット

`git add .` の"."は、「すべて」という意味。


`git add .` 
`git commit -m "Initial commit for this project"` 

## 4. GitHubで新規リポジトリを作成する
GitHubにログイン して、新規リポジトリ作成ページ を開く。

「Repository name」に リポジトリ名を入力し、プライベート／パブリックを選択して Create repository する。

「Initialize this repository with a README」はオフのまま(空リポジトリ)でも問題ない。

## 5. リモートを登録

`git remote add origin https://github.com/<ユーザー名>/<リポジトリ名>.git`

このリポジトリの場合

`git remote add origin https://github.com/AmiOtsukaSE/mkdocs.git`


## 6. コミットをGitHubへプッシュ

`git push -u origin main`


★詳細は随時加筆してください。
