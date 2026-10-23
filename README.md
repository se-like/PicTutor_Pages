# PicTutor - GitHub Pages

PicTutor アプリの利用規約・プライバシーポリシー等を公開するための GitHub Pages 用リポジトリです。

- [利用規約](terms.html) / Terms of Service
- [プライバシーポリシー](privacy.html) / Privacy Policy

本リポジトリの GitHub Pages を有効にすると、上記ページが公開されます。

## 依存関係のセキュリティ（GitHub）

private リポジトリでも **Dependabot alerts** と **Dependabot security updates** は無料で使える。このリポジトリでは両方を有効にしている。既知の脆弱性が GitHub Advisory Database に載り、lockfile の版が該当すると Security タブに出る。パッチがある場合は修正 PR が開く。

やらないこと:

- 定期の無差別バージョン bump（`dependabot.yml` による version updates は入れない）
- private 向けの Code scanning / Secret scanning（GitHub Advanced Security の有料機能）

通知は GitHub の [Notification settings](https://github.com/settings/notifications) で Dependabot alerts がオンであること、リポジトリを Watch していることが前提。新しいリポジトリにも自動で付けるなら [Security analysis](https://github.com/settings/security_analysis) の「Automatically enable for new repositories」を自分で入れる。
