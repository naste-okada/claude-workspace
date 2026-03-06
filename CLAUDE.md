# プロジェクト概要
- 会社: 株式会社naste
- 担当: 岡田
- 目的: AIアプリ開発・経営サポートツールの自動化環境構築

# 厳守ルール
1. 推測・憶測による実装禁止。不確かな場合は作業を止めて報告すること
2. 仕様変更を勝手に行わないこと。変更が必要な場合は旧仕様と新仕様を明示して確認を取ること
3. 実行前にやることを箇条書きで報告してから実行すること
4. 完了後は何をしたかをGitHubにコミットログとして記録すること

# 作業ディレクトリ
- ローカル: C:\Users\user\claude\claude-workspace
- GitHub: git@github.com:naste-okada/claude-workspace.git

# 開発対象
- AIOアナリティクスツール
- データベースマーケティングプラットフォーム
- BIデータ未来分析
- 出店計画支援
- 人材評価支援

# ログ記録ルール
logs/YYYYMMDD.md に記録する内容は以下の3つのみとする。

## 1. 仕様決定
- 何を作るか決まったこと
- 採用した技術・設計の理由

## 2. 仕様変更
- 変更前: [旧仕様]
- 変更後: [新仕様]
- 変更理由: [理由]

## 3. 未解決課題
- 課題内容
- 現状の選択肢
- 次回確認事項

# ログに記録しないもの
- 実行コマンドの詳細
- 成功した操作の詳細
- ファイルの中身そのまま

# 起動時の必須アクション
1. logs/ フォルダの最新ファイルを読み込むこと
2. 前回の作業内容・進行フェーズを把握してから作業を開始すること
3. 把握した内容を冒頭で報告してから作業に入ること

# このチャットとの連携方法
- リポジトリはPublicのため、claude.aiから直接参照可能
- 新スレッド開始時は以下URLをclaude.aiに貼り付けること
  - https://raw.githubusercontent.com/naste-okada/claude-workspace/main/CLAUDE.md
  - https://raw.githubusercontent.com/naste-okada/claude-workspace/main/logs/YYYYMMDD.md（最新）
- ログのURLは作業日ごとに追加すること
