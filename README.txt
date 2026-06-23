# ゼミ予鈴タイマー PWA版 v7

## 修正内容

- 開始, 一時停止, 再開を押した時にベル音が鳴るバグを修正
- 1鈴, 2鈴, 3鈴に古い電子音が混ざる問題を修正
- ベル音は bell.mp3 のみを再生
- Web Audio電子音フォールバックを廃止
- Service Workerのキャッシュ名を seminar-bell-timer-v7 に更新

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

今回とくに重要なのは index.html と service-worker.js です.
bell.mp3は前回から同じ音声ですが, 念のため一緒に上書きして構いません.

## 反映されない場合

1. GitHub PagesのDeploymentsが緑チェックになるまで待つ
2. Safariで公開URLを直接開いて再読み込みする
3. ベル音テストを押す
4. ホーム画面アプリを完全終了して開き直す
5. それでも古い場合は, ホーム画面アイコンを削除して追加し直す
