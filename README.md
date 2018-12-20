# Spring cleaning the GitHub repository tool

## Motivation

年末なのでGitHubリポジトリを整理したい。
しかしGitHubのWeb UIはアーカイブや削除までの手数が多くて面倒である。
そのためできるだけ少ない手数でアーカイブや削除をおこなえるものが欲しい。

## Requirements

- Auth
  - OAuthによるlogin / logout
- GitHub API
  - get repository list
    - 時間がかかりそうなのでローディング表示したい
  - repository archive / delete
    - 確認画面作りたい

### 必要なページ

- ログイン後共通
  - logoutボタン
- ホーム
  - GitHub認証ボタン
- リポジトリ一覧
  - archiveボタン
  - deleteボタン
- アーカイブ / 削除確認モーダル
