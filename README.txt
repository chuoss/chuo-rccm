RCCM PWA 完全版

内容:
- index.html
- manifest.webmanifest
- sw.js
- icons/

利用方法:
1. このフォルダー一式を、HTTPS対応のWebサーバーへアップロードしてください。
2. index.htmlをブラウザで開きます。
3. Chrome / Edge / Androidでは表示される「インストール」から追加できます。
4. iPhone / iPadではSafariの共有メニューから「ホーム画面に追加」を選択してください。

注意:
- file:// で直接開いた場合、通常の学習ツールとしては動作しますが、Service WorkerとPWAインストールは有効になりません。
- ローカル確認には、フォルダー内で `python -m http.server 8000` を実行し、
  http://localhost:8000/ を開く方法があります。
