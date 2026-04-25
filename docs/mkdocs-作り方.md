# MkDocsの始め方
## MkDocsのインストール
### ubuntu
```
sudo apt install mkdocs
```
もしくは
```
pip install mkdocs
```
公式ドキュメントではpipを使用したインストールが示されているが，環境によってはpipでインストールしたあとに自力でPATHを設定する必要がある．

## プロジェクトの作り方

プロジェクトを置きたい場所で`mkdocs new`コマンドを実行する．
プロジェクト名でフォルダが作成され，初期状態のドキュメントが生成される．
```Bash
cd <Path to Project Location>
mkdocs new <Project Name>

cd <Project Name>
code .
```