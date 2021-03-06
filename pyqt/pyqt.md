PyQtによるGUI開発
====

QtはC++でも広く利用されているクロスプラットフォームのGUIライブラリです．
ここでは，そのPython版であるPyQtを利用したGUI開発について解説していきます．

## PyQtのインストール

AnacondaからPythonをインストールすればデフォルトでついてきます．
特に，追加でインストールする必要はありません．

処理系がPython2.xとPython3.xで若干の記法の違いがあります．
通常は，Python3系で開発を進めればよいと思いますが，
使いたいライブラリによってはPython2系を選択した方が良いケースもあります．

プロジェクト毎に使用するPythonの処理系は分けておいた方が良いと思います．
例えば，本サイトでは，主にPython3.5の環境で実験していますが，
FBXモジュールの動作要件から[3Dプログラミングのチュートリアル](../fbx/fbx.md)では
Python2.7を使用しています．

## チュートリアル

* [PyQtのHello World](hello_world_qt.md)
* [シグナルとスロット](signal_slot.md)
* [イメージブラウザの作成](image_browser.md)
* [Webブラウザーの作成](web_browser.md)
* [メディアプレーヤーの作成](media_player.md)