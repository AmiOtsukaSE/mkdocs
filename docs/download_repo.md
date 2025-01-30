# GitHub上のリポジトリをダウンロードして使う方法

## 1. リポジトリのページを開く
例：https://github.com/ユーザー名/リポジトリ名

私の場合は、 https://github.com/AmiOtsukaSE/mkdocs

## 2. "Code" ボタンを押す

HTTPS または SSH のURLが表示されます
（例: https://github.com/ユーザー名/リポジトリ名.git など）

## 3. ターミナルで`git clone` 
### HTTPSの場合
git clone https://github.com/ユーザー名/リポジトリ名.git

### SSHの場合
git clone git@github.com:ユーザー名/リポジトリ名.git

## 4. ローカルに展開して使う
`cd リポジトリ名`
ここで `ls -a` などをすると `.git` ディレクトリが含まれていることを確認できます

詳細手順をここに自由に書いてください。


