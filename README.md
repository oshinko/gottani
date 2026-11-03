# gottani

ブラウザーで使える小さなツール集。入口は [index.html](index.html)。

- [パスワード生成](password-generator.html)：長さと文字種を選んでランダムなパスワードを生成します。
- [Pwned Passwords Checker](pwned-password-checker.html)：パスワードが既知の漏洩データに含まれているか確認します。

## 公開版

[https://oshinko.github.io/gottani/](https://oshinko.github.io/gottani/)

## GitHub Pages

`main` ブランチへの push で、`.github/workflows/deploy-pages.yml` が GitHub Pages へ公開します。ドキュメントだけの変更でも実行されます。Actions の「Deploy to GitHub Pages」から `main` ブランチを選んで手動実行することもできます。

初回のみ、GitHubリポジトリの `Settings` → `Pages` → `Build and deployment` → `Source` で `GitHub Actions` を選択してください。
