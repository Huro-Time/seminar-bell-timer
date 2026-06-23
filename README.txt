# ゼミ予鈴タイマー PWA版 v8

## 修正内容

- 開始, 一時停止, 再開時にベル音が鳴る原因を除去
- 古いWeb Audio電子音を完全削除
- ベル音は bell.mp3 のみ
- ベル音テストは1回だけ再生
- 1鈴, 2鈴, 3鈴は bell.mp3 を1回, 2回, 3回再生
- 連続再生間隔0.95秒は維持
- 画面上に「現在の版: v8 MP3専用」を表示
- Service Workerをv8化し, 古いキャッシュをより強く更新

## ファイル構成

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- bell.mp3
- README.txt

## GitHub Pagesでの更新方法

既存リポジトリ直下の以下の6ファイルを上書きしてください.

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- bell.mp3
- README.txt

## 更新確認

公開URLをSafariで直接開き, 画面上に「現在の版: v8 MP3専用」と出ているか確認してください.
出ていなければ古いキャッシュを見ています.
