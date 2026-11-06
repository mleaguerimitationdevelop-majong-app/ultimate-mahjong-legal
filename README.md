# アルティメット麻雀 - Legal

麻雀アプリ「アルティメット麻雀」のプライバシーポリシー・利用規約・特定商取引法に基づく表記を、GitHub Pagesで公開するための専用リポジトリです。App Store、Google Playおよびアプリ内から参照する公開URLを提供します。

静的HTML / CSSのみで構成しています。ビルド、npm、JavaScript、外部フォント、Analyticsは不要です。アプリ本体のコードは含みません。

## 原稿の管理方針

- 利用規約・プライバシーポリシーの原稿の正本は、別のアプリ本体リポジトリにあります。
- このリポジトリは公開用HTMLを管理します。本文のMarkdown原稿は重複管理しません。
- 原稿更新時は、公開HTMLにも同じ内容を反映してください。

## 公開ファイル一覧

| ファイル | 内容 |
| --- | --- |
| `index.html` | Legal Informationトップ。3つの法務文書へのリンク |
| `privacy.html` | プライバシーポリシー |
| `terms.html` | 利用規約 |
| `commercial.html` | 特定商取引法に基づく表記 |
| `styles.css` | 全ページ共通のスタイル |
| `README.md` | 運用・公開手順（サイトのナビゲーションには表示しません） |

## 確定情報と個人情報の取扱い

2026年11月6日に、運営者表記・問い合わせ先・管轄裁判所を確定し、特定商取引法に基づく表記を追加しました。

- 運営者表記：アルティメット麻雀運営
- 問い合わせ先：mleaguer.imitation.contact@gmail.com
- 準拠法：日本法
- 第一審の専属的合意管轄裁判所：福岡地方裁判所
- 公開日・最終更新日：2026年11月6日

販売事業者の氏名・住所・電話番号は常時公開せず、請求時に遅滞なく開示する方式です。開示請求は上記メールアドレスで受け付け、遅滞なく回答できるよう運用してください。個人情報を推測して追加しないでください。

初回リリースは日本向け・iOS先行で、Androidは後日公開予定です。EU向けの配信予定はありません。Google Playの説明はAndroid版の公開後に適用されます。

広告SDKの収集情報、同意取得・追跡許可、購入復元、端末内保存・同期については、既存文書の説明を基にしています。本リポジトリにはアプリ本体がないため、SDK設定や実装との一致は別途確認が必要です。

## 更新手順

1. アプリ本体リポジトリで原稿の正本を更新・確定します。
2. 対応する `privacy.html` / `terms.html` / `commercial.html` に変更を反映します。段落、見出し、箇条書き、表を適切なHTMLで記述してください。
3. ブラウザで各HTMLを開き、本文、スマホ幅の表示、各ページへのリンクを確認します。
4. 外部ポリシーリンクの `target="_blank"` と `rel="noopener noreferrer"` を維持します。内部リンク・CSSの参照は相対パスを使います。
5. 変更をコミットしてGitHubの `main` ブランチへプッシュします。
6. GitHub Pagesへの反映後、公開URLで本文とリンクを確認します。

## GitHub Pages有効化手順

1. 公開ファイルをルート直下に置いた状態で、GitHubの `main` ブランチへプッシュします。
2. リポジトリの **Settings → Pages** を開きます。
3. **Source: Deploy from a branch** を選択します。
4. **Branch: main / フォルダー: / (root)** を選び、**Save** を押します。
5. 公開完了後、Pages設定画面に表示されるURLを確認します。

本リポジトリへのGitHub Actionsワークフローの追加や、ビルド設定は不要です。

## 公開URLとアプリ側の設定

現在のGitリモートに対応する、GitHub Pagesの公開URLは以下のとおりです。リポジトリの移転・改名や独自ドメインの設定を行う場合は、Pages設定画面の公開URLを基準にしてください。

| 用途 | 公開URL |
| --- | --- |
| トップ | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/` |
| Privacy Policy URL | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/privacy.html` |
| Terms URL | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/terms.html` |
| 特定商取引法に基づく表記 URL | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/commercial.html` |

App Store / Google Playのプライバシーポリシー欄およびアプリ内のPrivacy Policyリンクには `privacy.html` の公開URLを設定します。アプリ内のTermsリンクおよびストアの該当欄には `terms.html` の公開URLを設定します。
