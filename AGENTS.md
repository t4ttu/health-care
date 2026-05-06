<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.
<!-- END:nextjs-agent-rules -->

# Agent Operating Notes

このファイルは、コーディングエージェントが確実に検出できるよう、リポジトリ直下に配置したままにしてください。

詳細な運用ルールは以下を参照してください。
- docs/README.md
- docs/agent-guidelines.md

変更時の基本方針:
- 変更は小さく、目的に対して最小限にする。
- 完了前に docs/agent-guidelines.md の検証コマンドを実行する。
- 明示的な依頼がない限り、大規模リファクタは行わない。
