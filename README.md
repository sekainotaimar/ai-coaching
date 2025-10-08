# 30日間AI伴走プログラム - ランディングページ

モバイル先行・超軽量のコンバージョン最適化されたランディングページです。

## 🚀 特徴

- **モバイルファースト設計**: 320px〜対応、レスポンシブ
- **超軽量**: Core Web Vitals最適化（LCP ≤ 2.5s目標）
- **高コンバージョン**: CRO最適化された導線設計
- **アクセシビリティ**: WCAG AA準拠
- **完全依存ゼロ**: バニラJS、外部ライブラリ不使用

## 📁 ファイル構成

```
├── index.html          # メインHTML（CSS・JavaScript内蔵）
├── netlify.toml       # Netlify設定
└── README.md          # このファイル
```

## 🎯 コンバージョン要素

### 主要CTA
- **メインボタン**: "今すぐ無料で体験してみる"
- **セカンダリ**: "当日の流れ（3分でわかる）"
- **モバイル固定CTA**: 480px以下で表示

### 心理的効果
- ✅ β版残枠カウンタ（希少性）
- ✅ 14日全額返金保証（リスク軽減）
- ✅ 7日連続達成特典（行動促進）

## 📊 計測・分析

### 実装済みトラッキング
- GA4イベント（CTA、スクロール、FAQ）
- Meta Pixelコンバージョン
- UTMパラメータ自動保存

### 設定が必要な項目
```html
<!-- index.html内で置換してください -->
GA_MEASUREMENT_ID → 実際のGA4 ID
META_PIXEL_ID → 実際のPixel ID
@example → 実際のLINE公式アカウントID
```

## 🛠 カスタマイズ方法

### 価格・期限変更
```html
<!-- data-var属性を検索して変更 -->
<span data-var="beta-price">¥980</span>
<span data-var="original-price">¥1,480</span>
<span data-var="beta-count">17</span>
```

## 🚀 公開手順

### 1. Netlify（推奨）
1. GitHubリポジトリ作成
2. ファイルをアップロード
3. Netlifyでリポジトリ連携
4. 自動デプロイ

### 2. Carrd移植
1. Carrdで新規サイト作成
2. HTMLブロック追加
3. index.htmlの内容をコピー

### 3. その他のホスティング
- index.htmlをそのまま使用可能
- netlify.tomlは他サービスでは不要

## 📱 パフォーマンス仕様

- **LCP**: 2.5s以下目標
- **INP**: 200ms以下目標  
- **CLS**: 0.1以下目標
- **Lighthouse Score**: 95+/100目標

## 🔧 技術仕様

- **HTML**: セマンティックマークアップ
- **CSS**: CSS Grid + Flexbox、CSS カスタムプロパティ
- **JavaScript**: ES6+、バニラJS
- **画像**: WebP対応、遅延読み込み
- **フォント**: Google Fonts（Inter + Noto Sans JP）

---

**作成日**: 2024年10月6日  
**バージョン**: 1.0.0