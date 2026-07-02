# carestock

## 作業方針

- 小規模修正ではサブエージェントを使用しない
- リポジトリ全体分析は依頼時のみ実施
- レビューは依頼時のみ実施
- 修正後は最小限の確認のみ行う

## データの取り扱い

- 個人・業務の実データ(エクスポートJSON/CSV)はこのリポジトリにコミットしない
- バックアップは非公開リポジトリ care-data-backup に置く

## バージョン管理

- HTML内の `_APP_V` は GitHub Actions(auto-version.yml)が自動更新するため手動で変更しない
- 新規アプリは management リポジトリの app-template.html を雛形にする
