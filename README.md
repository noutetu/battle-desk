# バトルデスク 公式サイト

iOSアプリ「**バトルデスク**（BattleDesk）」の公式サイトです。GitHub Pages で静的サイトとして公開します。

バトルデスクは、ポケモン対戦向けのダメージ計算・型管理・パーティ管理を行う **非公式のファンツール** です。本アプリおよび本サイトは、任天堂株式会社、株式会社ポケモン、Game Freak Inc.、Creatures Inc. とは関係ありません。

## ファイル構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | トップページ（アプリ概要・特徴・使い方・広告・サポート・免責） |
| `privacy.html` | プライバシーポリシー（App Store Connect 申告用） |
| `style.css` | 共通スタイル（白背景＋紫アクセント／モバイル優先） |
| `README.md` | このファイル |

ビルドツールは不要です。HTML / CSS のみで構成されています。

## GitHub Pages の有効化手順

1. このリポジトリ（リポジトリ名の想定：`battle-desk`）を GitHub に push します。
2. リポジトリの **Settings** → **Pages** を開きます。
3. **Build and deployment** の **Source** で **Deploy from a branch** を選択します。
4. **Branch** で `main`（公開したいブランチ）と `/ (root)` を選び、**Save** をクリックします。
5. 数分待つと、以下の URL で公開されます。
   - トップページ：`https://<GitHubユーザー名>.github.io/battle-desk/`
   - プライバシーポリシー：`https://<GitHubユーザー名>.github.io/battle-desk/privacy.html`

`index.html` がトップページとして自動的に表示されます。

## App Store Connect への設定

公開後、App Store Connect の **プライバシーポリシー URL** には、以下を設定します。

```
https://<GitHubユーザー名>.github.io/battle-desk/privacy.html
```

## 公開前に差し替えること（TODO）

公開前に、以下のプレースホルダーを必ず実際の値へ差し替えてください。

- **問い合わせ先メールアドレス**：`support@example.com`
  - `index.html`（サポートセクション・フッター）
  - `privacy.html`（8. お問い合わせ・フッター）
- **App Store URL**：`index.html` ヒーローの「App Storeで見る」ボタン（現在は `#`）
  - 各箇所には `TODO:` コメントを記載済みです。

## ライセンス・権利表記

アプリおよびサイト内で言及される名称・画像・データ等の権利は、各権利者に帰属します。
