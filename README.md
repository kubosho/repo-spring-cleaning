# Spring cleaning tool for GitHub repository

## Motivation

年末なので GitHub リポジトリを整理したい。
しかし GitHub の Web UI はアーカイブや削除までの手数が多くて面倒である。
そのためできるだけ少ない手数でアーカイブや削除をおこなえるものが欲しい。

## Requirements

- Auth
  - OAuth による login / logout
- GitHub API
  - get repository list
    - 時間がかかりそうなのでローディング表示したい
  - repository archive / delete
    - 確認画面作りたい

### 必要なページ

- ログイン後共通
  - logout ボタン
- ホーム
  - GitHub 認証ボタン
- リポジトリ一覧
  - archive ボタン
  - delete ボタン
- アーカイブ / 削除確認モーダル
