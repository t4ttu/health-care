# エージェント運用ガイド

## 目的

- このファイルは、プロジェクト固有のエージェント運用ルールを定義します。
- 入口ファイルである AGENTS.md はリポジトリ直下に維持します。

## プロジェクトコマンド

package.json の npm scripts を使用します。

- npm run dev: 開発サーバーを起動
- npm run build: 本番ビルドを作成
- npm run start: 本番サーバーを起動
- npm run lint: Biome で静的チェック
- npm run format: Biome で整形

## 変更ポリシー

- 変更は最小単位で行い、対象外ファイルは触らない。
- タスク要件がない限り、既存の命名規則と構成を維持する。
- 依存関係を追加する場合は、追加理由を明記する。

## 完了前チェック

必要に応じて以下を実行します。

1. npm run lint
2. npm run build

## Next.js に関する注意

- このプロジェクトの Next.js は破壊的変更を含む可能性があります。
- フレームワークレベルの変更前に node_modules/next/dist/docs/ を確認してください。

## docs 配下の運用

- 要件定義、設計、agent 関連の情報は docs 配下へ集約します。
- 新規ドキュメントを追加したら docs/README.md の目次を更新します。
