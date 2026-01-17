# Shogi KIF Player for Notion

Notionに埋め込んで使える、将棋KIF棋譜ビューアです。  
GitHub内にkifを保存してしまって、URLさえ変えれば指定棋譜が表示されるという仕様です。

## 使い方

1. `kif/` フォルダを開く
2.  Add file → + Create New fileを押し、Name your file...に`任意のファイル名.kif`を入力
3.  画面大部分のEditのところに、入れたい棋譜（分岐あっても可）をkif形式で貼り付け
4.  Commit changes...を押す
5.  Commit changesを押す
6.  kifフォルダ内に新しいファイルができたはず（GitHubですることはこれでおしまい）
7. 以下の形式のURLをNotionに埋め込む：
https://qupffer.github.io/Shogi_kifplayer/?kif=任意のファイル名.kif

## フォルダ構成
Shogi_kifplayer/
index.html
kif/
example_1.kif
example_2.kif

## クレジット
Original UI by: tasogarexerion  
Modified and extended by: qupffer  

UIデザインは友人のプロジェクト  
`Shogi_kifplayer` をForkして使用しています。

## ライセンス

MIT License

