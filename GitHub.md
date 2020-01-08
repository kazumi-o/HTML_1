GitHub
======================
+   格納先
+   記述
+   設定方法

格納先
------
$ cd Desktop/HTML_1/

ローカル：/Desktop/HTML_1 (master)

ブラウザ：https://github.com/kazumi-o/HTML_1

記述
------
$ cd　移動  
$ mk dir [フォルダ名]　新規フォルダ作成  
$ touch [ファイル名]　 新規ファイル作成  
$ git init　ローカルリポジトリ作成  
$ git add [ファイル名]  
$ git status　確認  
$ git commit -m "コメント"  
$ git push　プッシュ  
$ git log     確認  

$ git rm [削除したいファイル]  
$ git rm -r [削除したいディレクトリ]  
$ git rm --cached [削除したいファイル]　ファイルを残したまま管理対象から外す

https://fjord.jp/kuroigamen/7.html

設定方法
------
1. Git Bash(windows) https://gitforwindows.org/
2. GitHub登録　https://github.co.jp/
3. 初期設定
gitに登録しているアドレスと、ユーザーネームを指定

$git config --global user.email ここに自分のアドレス  
$git config --global user.name ここに自分の名前

4. Gitコミット

echo "# HTML_1" >> README.md（フォルダ作成⇒mdファイル作成）  
$ git init（ローカルリポジトリ作成）  
$ git add README.md（mdファイル追加）

**ここで、あなたは誰ですか状態のエラーが表示される場合**  
上記、gitの初期設定が完了していない、gitに登録しているアドレス、ユーザーネームを指定

$git config --global user.email ここに自分のアドレス  
$git config --global user.name ここに自分の名前

***
Please tell me who you are.

Run

  git config --global user.email "you@example.com"  
  git config --global user.name "Your Name"
***

$ git commit -m "first commit"  
$ git remote add origin https://github.com/kazumi-o/HTML_1.git  
$ git push -u origin master

5. ポップアップログインが開いたらサインイン  
登録しているアドレス、ユーザーネームを指定