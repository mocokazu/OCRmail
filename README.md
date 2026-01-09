# OCRmail (現場スキャンWeb)

スマホのブラウザでバーコードを連続スキャンし、読み取ったリストをメールで送信するWebアプリです。
PWA（Progressive Web App）に対応しており、ホーム画面に追加してオフラインでも使用可能です。

## 機能

- **連続スキャン**: カメラで次々とバーコードを読み取り
- **重複防止**: 同じコードの連続読み取りを防止（設定でON/OFF可能）
- **データ保存**: ブラウザにデータを自動保存
- **メール連携**: 読み取ったリストを標準メーラーで送信

## 使い方

1. ブラウザでアプリを開く（HTTPS必須）
2. カメラ権限を許可
3. 「スキャン開始」ボタンで読み取り開始
4. 「メール送信」ボタンでメーラーを起動

## 開発構成

- HTML5 / CSS3 (Bootstrap 5) / JavaScript (Vanilla)
- ライブラリ: [html5-qrcode](https://github.com/mebjas/html5-qrcode)

## 公開方法 (GitHub Pages)

1. このリポジトリをGitHubにプッシュ
2. リポジトリの **Settings** > **Pages** を開く
3. **Source** を `Deploy from a branch` に設定
4. **Branch** を `main` に設定して **Save**
5. 表示されたURLにスマホでアクセス
