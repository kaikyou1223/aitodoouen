# 技術的コンテキスト

## 使用技術
- **静的サイトジェネレーター**: Jekyll 4.x
- **ホスティング**: GitHub Pages
- **HTML**: HTML5 (セマンティックマークアップ)
- **CSS**: CSS3 (Grid, Flexbox, Custom Properties)
- **JavaScript**: ES6+ (最小限の使用)
- **バージョン管理**: Git

## 開発環境
- **OS**: macOS 14.5+
- **Ruby**: 2.7+ (Jekyll依存)
- **Node.js**: 18+ (開発ツール用)
- **エディタ**: VS Code / Cursor

## 依存関係
- Jekyll およびその依存gems
- GitHub Pages gem
- 最小限のフロントエンド依存関係（可能な限り避ける）

## 技術的制約
- GitHub Pagesの制限に準拠
- カスタムプラグインの使用不可
- 静的ファイルのみ
- サーバーサイド処理なし

## セキュリティ要件
- HTTPS配信（GitHub Pages標準）
- XSSの予防（Content Security Policy）
- 個人情報の不適切な収集防止

## デプロイメント
- **自動デプロイ**: GitHub Actions（またはGitHub Pages自動ビルド）
- **ブランチ**: main / gh-pages
- **URL**: https://[username].github.io/[repository-name]

## 品質保証
- HTML/CSS バリデーション
- レスポンシブテスト
- パフォーマンステスト
- クロスブラウザテスト 