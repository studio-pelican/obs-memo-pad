# 配信画面メモパッド (OBS Memo Pad) タスクリスト

- [x] 計画フェーズ
  - [x] UI操作フロー図とDOM構造の設計
  - [x] ユーザー承認の取得
- [x] 実装フェーズ (`index.html`)
  - [x] プロジェクトの初期設定（ベースHTML・CSS作成）
  - [x] OBS用最適化CSS（透明背景、オーバーフロー防止、選択禁止）
  - [x] JavaScript: localStorage連携（メモの保存・復元機能）
  - [x] JavaScript: メモDOMの動的生成と個数制限（最大10個）の管理
  - [x] イベント: 新規メモ作成（画面ダブルクリック）
  - [x] イベント: テキスト編集（contenteditable と blur 検知）
  - [x] イベント: ドラッグ＆ドロップ移動（Pointer Events）
  - [x] イベント: 4隅のリサイズ（Pointer Events と ResizeObserver またはドラッグ）
  - [x] イベント: メモの削除（右クリックコンテキストメニュー）
- [x] 検証・ドキュメント作成フェーズ
  - [x] ブラウザ相当の環境での機能テスト
  - [x] `README.md` の作成（操作説明、OBS設定手順、デプロイ手順）
  - [x] `walkthrough.md` の作成
