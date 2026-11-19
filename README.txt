ゆいなデイサービスセンター 出退勤PWA

【GitHubへの配置】
1. GitHubで yuina-dayservice-attendance リポジトリを開く
2. Add file → Upload files を選ぶ
3. このZIPを解凍し、中の index.html / manifest.json / sw.js / icons フォルダをまとめてアップロード
4. Commit changes
5. Settings → Pages → Build and deployment で Deploy from a branch、Branch: main、Folder: /(root) を選び Save
6. 公開URL（https://belltree20251001-crypto.github.io/yuina-dayservice-attendance/）を開いて確認

【スマートフォンへの追加】
Android: Chromeで公開URLを開き、メニューから「アプリをインストール」または「ホーム画面に追加」
iPhone: Safariで公開URLを開き、共有ボタン →「ホーム画面に追加」

このPWAはGitHub Pages上のホーム画面アイコンから、既存のGoogle Apps Scriptアプリを表示します。出退勤の記録にはインターネット接続が必要です。GitHubリポジトリは公開設定のため、ここには個人情報・パスワード・勤務記録を置かないでください。Googleスプレッドシート自体は公開しないでください。
