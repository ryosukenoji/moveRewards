# Calshe Static Site (Noto Sans + Royal Blue)

Firebase Hosting でそのまま公開できる静的サイト一式です。

## デプロイ（最短）
```bash
npm i -g firebase-tools
firebase login
firebase init hosting   # public を選択（既存プロジェクトに紐づけ）
firebase deploy         # https://<project-id>.web.app で公開
```

## 構成
- public/index.html … サイト本体
- public/404.html … 404ページ（任意）
- firebase.json … Hosting 設定（キャッシュ最適化）
- .firebaserc … デフォルトのプロジェクトID（置き換えてください）
