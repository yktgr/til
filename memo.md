#環境設定
    -   xcode:開発ツール  
    -   homebrew:パッケージ管理
        - シェルパス通す
    -   rbenv:ルビーバージョン管理
        - rubyインストール
#git
    - git branch hoge
    - git checkout
    - git checkout -b hoge
    - git log
    - git branch
    - git add .
    - git commit -m "hoge"

#linux
04 復習する
lshw	ハードウェアの一覧を表示する
pwd     現在のディレクトリの表示
ls      ファイル・ディレクトリの一覧の表示
cd      現在のディレクトリの変更
mkdir	ディレクトリの作成
rm	    ファイルやディレクトリの削除
cp	    ファイルやディレクトリのコピー
        cp -r ファイルも
mv	    ファイルやディレクトリの移動
find	ファイル・ディレクトリの検索

#05標準出力
コマンド＋　> hoge.txt　出力内容がファイルに保存される
cat ファイルの中身
less ファイルの中身（ページ送り）

head 最初の10行
tail 最後の10行

｜　パイプコマンドを繋ぐ

ls /bin | grep ss /binの一覧のなかのssという文字

#vim