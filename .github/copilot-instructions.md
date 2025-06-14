<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

このプロジェクトはPythonを使用したWebクローリングとローカルRAG（Retrieval-Augmented Generation）システムの実装です。

## プロジェクト構成

- `src/`: メインのソースコードディレクトリ
  - `main.py`: アプリケーションのエントリーポイント
  - `utils.py`: 共通ユーティリティ関数
  - `crawl4ai/`: Webクローリング関連のモジュール
    - `crawler.py`: クローラーの実装
  - `duckdb/`: DuckDB関連のモジュール
    - `duckdb_rag.py`: DuckDBを使用したRAGの実装

- `tests/`: テストコードディレクトリ
  - `test_main.py`: メインモジュールのテスト
  - `test_utils.py`: ユーティリティ関数のテスト

## コーディング規約

1. Python 3.11以上の機能を活用すること
2. すべてのコードに日本語のドキュメントコメントを付けること
3. テストコードを必ず作成すること
4. 型ヒントを適切に使用すること（pyright設定あり）

## タスク

以下のタスクが定義されています：
- `Run main.py`: メインアプリケーションの実行
- `Run tests`: ユニットテストの実行
