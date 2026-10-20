# Ultimate Mahjong - Legal

麻雀アプリ「Ultimate Mahjong」のプライバシーポリシー・利用規約を、GitHub Pagesで公開するための専用リポジトリです。App Store、Google Playおよびアプリ内から参照する公開URLを提供します。

静的HTML / CSSのみで構成しています。ビルド、npm、JavaScript、外部フォント、Analyticsは不要です。アプリ本体のコードは含みません。

## 原稿の管理方針

- 利用規約・プライバシーポリシーの原稿の正本は、別のアプリ本体リポジトリにあります。
- このリポジトリは公開用HTMLを管理します。本文のMarkdown原稿は重複管理しません。
- 原稿更新時は、公開HTMLにも同じ内容を反映してください。

## 公開ファイル一覧

| ファイル | 内容 |
| --- | --- |
| `index.html` | Legal Informationトップ。両文書へのリンク |
| `privacy.html` | プライバシーポリシー |
| `terms.html` | 利用規約 |
| `styles.css` | 全ページ共通のスタイル |
| `README.md` | 運用・公開手順（サイトのナビゲーションには表示しません） |

## 公開前の確認

**公開前にTBDをすべて解消する必要があります。** 現在は提供された原案の表記をそのまま保持しています。

- `privacy.html` 第1項：運営者名、問い合わせ先、公開日、最終更新日
- `privacy.html` 第9項：問い合わせ先（TBD）への言及
- `terms.html` 第2項：運営者名、問い合わせ先、公開日、最終更新日
- `terms.html` 第15項：管轄裁判所

運営者情報などを推測して補完しないでください。「原案」の表記や冒頭の注意書き、第三者サービスの導入予定についても、正本の確定内容を確認し、公開HTMLに反映してください。

## 更新手順

1. アプリ本体リポジトリで原稿の正本を更新・確定します。
2. 対応する `privacy.html` / `terms.html` に変更を反映します。段落、見出し、箇条書き、表を適切なHTMLで記述してください。
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

現在のGitリモートに対応する、通常のプロジェクト用GitHub Pagesの想定URLは以下のとおりです。公開はまだ行っていません。リポジトリの移転・改名や独自ドメインの設定を行う場合は、Pages設定画面の公開URLを基準にしてください。

| 用途 | 想定URL |
| --- | --- |
| トップ | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/` |
| Privacy Policy URL | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/privacy.html` |
| Terms URL | `https://mleaguerimitationdevelop-majong-app.github.io/ultimate-mahjong-legal/terms.html` |

App Store / Google Playのプライバシーポリシー欄およびアプリ内のPrivacy Policyリンクには `privacy.html` の公開URLを設定します。アプリ内のTermsリンクおよびストアの該当欄には `terms.html` の公開URLを設定します。
