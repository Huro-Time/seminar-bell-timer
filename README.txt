# ゼミ予鈴タイマー PWA版 v6

## 更新内容

- ベル音を添付MP3「呼び出しベル.mp3」ベースに変更
- 音声ファイルを bell.mp3 として同梱
- アプリ側は bell.mp3 を再生
- 1鈴, 2鈴, 3鈴は同じベル音を1回, 2回, 3回鳴らす
- ベルの連続再生間隔を約0.95秒に調整
- Service Workerのキャッシュ名を seminar-bell-timer-v6 に更新
- bell.mp3 もオフラインキャッシュ対象に追加

## ファイル構成

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- bell.mp3
- README.txt

## GitHub Pagesでの更新方法

既存リポジトリ直下の以下のファイルを上書きしてください.

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- bell.mp3
- README.txt

今回の更新では bell.mp3 が新規追加されています.
必ず bell.mp3 もリポジトリ直下にアップロードしてください.

## 音が古いままの場合

1. GitHub PagesのDeploymentsが緑チェックになるまで待つ
2. Safariで公開URLを直接開いて再読み込みする
3. ベル音テストを押す
4. ホーム画面アプリを完全終了して開き直す
5. それでも古い場合は, ホーム画面アイコンを削除して追加し直す
