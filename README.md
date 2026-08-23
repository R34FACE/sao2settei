# SAO2 設定推測カウンター PWA版

GitHub Pages に置くだけで、Androidのホーム画面へアプリ風に追加できます。

## 公開手順
1. 新しいGitHubリポジトリ（例: `sao2-setting-tool`）を作成。
2. このフォルダ内の `index.html` / `manifest.webmanifest` / `sw.js` / `.nojekyll` / `icons` をリポジトリ直下へアップロード。
3. GitHub の Settings → Pages → Deploy from a branch → `main` / `(root)` → Save。
4. 公開された `https://<ユーザー名>.github.io/sao2-setting-tool/` をAndroidのChromeで開く。
5. 画面上の「ホームに追加」、またはChromeメニューの「アプリをインストール」「ホーム画面に追加」を選択。

## 特徴
- standalone表示（URLバーなし）
- ホーム画面アイコン対応
- オフライン起動対応
- 入力データはlocalStorageへ端末保存

※ GitHub Pages等のHTTPS環境で開いた時にPWAインストールが有効になります。ローカルHTMLを直接開くだけではインストール候補が出ない場合があります。
