・家で編集した。05/20

・Gitでできること
・基本のシェルコマンド
・Gitの基本コマンド
・vim（テキストエディタ）の使い方
・ブランチの作成、変更、マージ
・リポジトリのクローン
・クローンリポジトリへの取込


  
・GIT
  リボジトリ（バックアップしたいファイルを入れるフォルダ）に対してファイル登録を行うCUIシステム。
  ワーキングディレクトリにファイルを保存→ステージングエリアに登録→リポジトリに登録の順番で登録を行う。
  
  実際のプロジェクト現場では、
  サーバのリポジトリ内容をローカルに複製(clone or pull)し、変更をローカルリポジトリに対して行い(commit)、
  最終的にサーバのリポジトリに対して、ローカルリポジトリの内容を反映する(push)手順となる想定。

・主要なコマンド
git --version		バージョン確認
git config --global user.name "kirishima"				ユーザの登録
git config --global user.email"kirishima@paiza.jp"		メールアドレスの登録
リボジトリの作成
  mkdir mywork
  cd mywork
  git init			リボジトリ作成（カレントフォルダにリポジトリが生成される）
git config --list	設定情報を表示
git status			ファイル登録状態を表示
git status -s		ファイル登録状態を簡易表示
git add ﾌｧｲﾙ名		ファイルをステージングへ登録
git add .			ワーキングディレクトのファイルを一括でステージングへ登録
git commit			ステージングの内容をリポジトリへ反映
git commit -a		ステージング＋リポジトリへ一括反映
git commit -m "commit msg"		コミットメッセージを同時に指定する
git log				コミット履歴
git log --oneline 	コミットメッセージだけ表示
git log -1 			指定件数のコミットメッセージを表示
git diff			ステージングとワーキングディレクトリを比較
git diff --cached	最新コミットとステージングエリアを比較
git diff HEAD		最新コミットとワーキングディレクトリを比較
git branch			ブランチを確認
git branch ﾌﾞﾗﾝﾁ名	ブランチを作成
git checkout ﾌｧｲﾙ名	リボジトリ内容をワーキングディレクトリに戻す
git reset ﾌｧｲﾙ名	ステージング上のファイルを元に戻す
git revert HEAD		最新コミットの取り消し
git checkout ﾌﾞﾗﾝﾁ名	対象とするブランチを変更する
git merge ﾌﾞﾗﾝﾁ名	現在のブランチに指定ブランチを統合する

共同リボジトリを複製する
  mkdir neko_work
  cd neko_work
  git clone /gitﾊﾟｽ

git remote -v			複製した共同リボジトリの情報を表示する
git pull /gitﾊﾟｽ	    複製リポジトリに共同リボジトリ内容を反映する
git push origin master	複製リポジトリの内容を共同リボジトリにコミット反映する

・リボジトリとは  			GITでバックアップしたいファイルを入れるフォルダ
・ブランチとは				リボジトリとは別バージョンで管理したい場合に作成するフォルダ
・リモートレポジトリとは	サーバ上にあるGITの保存先
・ローカルリポジトリとは	自分のパソコン上にある保存先

・vim
	シェルで利用できるテキストエディタ
	- a 現在のカーソル位置の右から入力する
	- A 現在の行の末尾に入力する

	コマンドモード
	- 編集モードからコマンドモードに切り替える
	- u 元に戻す
	- :wq 保存して終了
	- :q! 保存しないで終了

・その他シェルコマンド
	・ファイル内容を表示する
	cat foo.txt

	・ファイル一覧を表示
	ls

	・ファイルコピー
	cp foo.txt bar.txt

	・ファイル名変更
	mv bar.txt new.txt		//ファイル名変更
	mv practice test		//フォルダ名変更

	・ディレクトリ作成
	mkdir test

	・ファイル削除
	rm new.txt

	・ディレクトリ移動
	cd ..
	cd practice

	・ルートディレクトリの一覧表示
	ls -al /

