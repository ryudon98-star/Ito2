ito DUO - GitHub Pages用ファイル

【アップロードするファイル】
index.html
manifest.json
sw.js
thumbnail.png
icons/icon-192.png
icons/icon-512.png

【GitHubでの公開手順】
1. GitHubで新しいリポジトリを作成（Publicがおすすめ）
2. このZIPを解凍する
3. ZIP内のファイルと icons フォルダを、リポジトリの一番上（root）にアップロード
4. Commit changes
5. Settings → Pages
6. Build and deployment の Source を「Deploy from a branch」にする
7. Branch を「main」、フォルダを「/(root)」にして Save
8. 数分待ち、Settings → Pages の公開URLを開く

【仕様】
・スマートフォン縦画面を前提にした2人協力ゲーム
・横向きでは縦向きに戻す案内を表示
・テーマとランキングは同じブラウザ内に保存（別端末とは同期しません）
・ホーム画面追加用 manifest と簡易オフラインキャッシュを同梱
・テーマは初期収録分に加えて自由に追加・削除できます

【注意】
GitHub Pagesへのアップロード・公開操作は利用者のGitHubアカウント上で行ってください。
