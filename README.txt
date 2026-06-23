# ゼミ予鈴タイマー PWA版 v4

## 更新内容

- スマホ横画面の全画面表示を最適化
- 全画面時のスタート, 再開, 一時停止, リセットボタンを小型化
- 横画面時にボタン幅を中央寄せで制限
- 進捗バーを横画面で細くして, ボタンとの圧迫感を軽減
- 時刻表示の文字間を調整し, コロン部分の詰まりを軽減
- manifestのorientationをanyに変更
- Service Workerのキャッシュ名を seminar-bell-timer-v4 に更新

## ファイル構成

- index.html
- manifest.webmanifest
- service-worker.js
- icon.png
- README.txt

## GitHub Pagesでの更新方法

既存リポジトリ直下の以下のファイルを上書きしてください.

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
