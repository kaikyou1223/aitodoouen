# システムパターン

## アーキテクチャ概要
- **静的サイト**: Jekyll + GitHub Pages
- **フロントエンド**: HTML5 + CSS3 + minimal JavaScript
- **レスポンシブデザイン**: CSS Grid + Flexbox
- **ホスティング**: GitHub Pages

## 設計パターン
- **モバイルファースト**: 小さな画面から大きな画面へのスケーリング
- **コンテンツ重視**: 情報の階層化と可読性優先
- **アクセシビリティ**: セマンティックHTML、適切なコントラスト
- **Progressive Enhancement**: 基本機能を確保してから拡張

## ディレクトリ構造
```
/
├── _config.yml          # Jekyll設定
├── index.html           # プライバシーポリシーページ
├── assets/
│   ├── css/
│   │   └── style.css    # メインスタイル
│   └── js/
│       └── main.js      # 最小限のJavaScript
└── README.md            # プロジェクト説明
```

## 技術的決定
- **Jekyll**: GitHub Pagesの標準、メンテナンスが簡単
- **Vanilla CSS**: 軽量性とパフォーマンス優先
- **セマンティックHTML**: SEOとアクセシビリティのため
- **No Framework**: 複雑性を避けシンプルに保つ

## パフォーマンス目標
- ページロード時間: 2秒以下
- モバイル対応: 100% responsive
- アクセシビリティ: WCAG 2.1 AA準拠 