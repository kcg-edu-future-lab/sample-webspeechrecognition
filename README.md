# sample-webspeechrecognition

ブラウザのAPIを使って音声認識を行うサンプルです。

まずはこのリポジトリをcloneしてください。
```
git clone https://github.com/kcg-edu-future-lab/sample-webspeechrecognition
```

htmlファイルがあるディレクトリでHTTPサーバを起動し，ブラウザで表示してください。例えばpython3がインストールされていれば，以下のコマンドでサーバを起動できます。
```
python3 -m http.server
```

HTTPサーバが起動したら，ブラウザで以下のアドレスにアクセスしてください(ポートはサーバの設定に応じて変えてください)。
```
http://localhost:8000
```


表示された画面の"音声認識"チェックボックスをチェックすると，音声認識が開始されます。結果はログ表示部分に表示されます。
