# ゼミ予鈴タイマー PWA版 v5

## 緊急修正内容

- iPhone/PWAでベル音が鳴らない問題への対策
- Web Audioの電子音だけでなく, 埋め込みWAV音声を使う方式に変更
- ベル音テストのタップ時に音声再生を明示的にアンロック
- 従来のWeb Audio電子音はバックアップとして残存
- Service Workerのキャッシュ名を seminar-bell-timer-v5 に更新

## v4から継続している機能

- スマホ横画面の全画面表示最適化
- 発表時間の自由指定
- 1鈴, 2鈴, 3鈴の個別設定
- 0.5分単位のベル指定
- ホーム画面PWA対応

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

特に重要なのは index.html と service-worker.js です.

## 音が鳴らない場合

1. アップロード後, GitHub PagesのDeploymentsが緑チェックになるまで待つ
2. Safariで公開URLを直接開いて再読み込みする
3. ベル音テストを押す
4. 音量ボタンでメディア音量を上げる
5. Bluetoothイヤホン等に音が飛んでいないか確認する
6. ホーム画面アプリを完全終了して開き直す
7. それでも古い画面なら, ホーム画面アイコンを削除して追加し直す
