# 概要
このプログラムは**工学院大学**の学生向けに作られています.
CoursePowerから自動で教材をダウンロードします.
# 前提
This software is released under the MIT License, see LICENSE.txt.

本プロジェクトは[poetry](https://cocoatomo.github.io/poetry-ja/)でPythonのパッケージ管理をしています.
よくわからない人や環境を汚しても良い人は`python3 -m pip install selenium`を実行してください.

# 準備
1. まず、[ここ](http://chromedriver.chromium.org/downloads)から**自分が使用しているChromeのバージョンの**ChromeDriverをダウンロードしてください.
2. ダウンロードしたChromedriverを`main.py`と同じディレクトリに配置してください.
3. `setup.py`を実行し,ガイドに従って入力してください.

# 実行
* poetryを使っている方は`poetry run python3 main.py`を,それ以外の方は`python3 main.py`を実行すると自動的に教材をダウンロードします。

# 注意事項
* このプログラムを実行したことによって生じた如何なる他の損害に対して,作者は一切その責任を負いません.自己責任で実行してください.
* **Windows**でこのプログラムを実行する方は,ディレクトリ指定の際に'￥'ではなく,'￥￥'(または'\\')にする必要があります.詳しくはググってください.
* Windowsの**64bit版を使用している方も**ChromeDriverは'chromedriver_win32.zip'をダウンロードしてください.

# その他
* プログラムを実行すると授業名のフォルダが作成され,そのフォルダに教材がダウンロードされます。
* しばらく画面が動かないことがありますが,仕様です.1分以上動きが無い場合は何らかのバグが発生している可能性があるため,プログラムを停止し,エラーメッセージを確認してください.
* 動作確認はUbuntu18.04,Ubuntu20.04,Windows10で行いました. (2020/05/20)
* 重複したファイルは,ダウンロード後ゴミ箱に移動します.プログラムを実行した後はゴミ箱を確認してみてください.
* プログラムが中断されるとダウンロードディレクトリに`new_tmp.txt`が残ります.そのままにしても問題ありませんが,削除することをおすすめします.
* その他疑問点がありましたら`kake537@neko2.net`にご連絡いただければ幸いです.