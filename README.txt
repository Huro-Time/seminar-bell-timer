# ゼミ予鈴タイマー PWA版 v3

## 更新内容

- 発表時間を時間, 分, 秒で自由に指定可能
- ベル時間を0.5分単位で指定可能
- タイマー部の全画面表示を追加
- 30分発表プリセットを追加
- Service Workerのキャッシュ名を seminar-bell-timer-v3 に更新

## ファイル構成

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- README.txt

## GitHub Pagesでの更新方法

既存リポジトリの直下にある以下のファイルを上書きしてください.

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- README.txt

通常の機能更新だけなら, index.html と service-worker.js の上書きが最重要です.
スマホ側で古い画面が残る場合は, ホーム画面アプリを完全に閉じて再起動してください.
それでも反映されない場合は, ホーム画面アイコンを削除して追加し直してください.

## 注意

画面ロック中や完全なバックグラウンド状態では, スマホ側の制限で音が鳴らない場合があります.
ゼミ中は画面をつけたまま, マナーモードを解除し, 事前にベル音テストを押してください.
