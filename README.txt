AO 1st ANNIVERSARY INVITATION
=============================

GitHub Pages用のモバイルファースト招待状サイトです。

構成
----
01 Opening / 「君と見たい景色がある。」
02 Envelope / 招待状を開く
03 Anniversary / 蒼、1周年。 2026.10.28
04 Memory / 6つの1年間の記録
05 Secret / 「第二章 : 新たなステージへ」
06 Countdown / 10.28までのカウントダウン
07 Letter / 蒼への手紙
08 Closing / 1周年を一緒に迎える

画像
----
images/ao-logo.png   = 蒼のロゴ
images/photo-01.jpg = アップロードされた写真1
images/photo-02.jpg = アップロードされた写真2
images/photo-03.jpg = アップロードされた写真3
images/photo-04.jpg = アップロードされた写真4
images/night-bg.png  = 背景

手紙フォームについて
--------------------
GitHub Pagesだけではフォーム内容を保存するサーバー機能はありません。
現在はプレビュー用として、最後に入力した手紙をブラウザのlocalStorageに保存し、送信演出を再生します。

実際に受け取りたい場合は、script.js の先頭にある
FORM_ENDPOINT = ""
へ、Formspreeなどのフォーム送信先URLを設定してください。

例：
FORM_ENDPOINT = "https://formspree.io/f/あなたのID"

※URLは自分で取得した送信先を使ってください。

GitHub Pagesへの更新
--------------------
index.html / style.css / script.js / images フォルダをリポジトリへアップロードしてください。
imagesフォルダの中に画像5枚を置く必要があります。

今回のサイトでは「今の蒼について」のセクションは入れていません。
10月28日の特別発表の内容もサイト上では公開していません。
