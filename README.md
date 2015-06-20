# Brewfile
新しいPCにBrewfileを元に同じパッケージで環境を構築したい場合は、以下の順番で実行する必要があります。

1. Homebrewをインストール
   http://brew.sh/index_ja.html
2. Homebrew-fileをインストール
   ```
   brew install rcmdnk/file/brew-file
   ```
3. Brewfileのリポジトリを登録
   ```
   brew file set_repo -r tigawa/Brewfile
   ```
4. brew file install を実行する
   ```
   brew file install
   ```
 

# 参考サイト
* http://www.task-notes.com/entry/20150316/1426474800


