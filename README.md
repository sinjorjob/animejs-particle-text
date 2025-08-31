# Anime.js Particle Text Animation 🌈✨

美しい虹色のパーティクルテキストアニメーションです。Claude CodeのVibe Codingで作成されました。

## 🎨 特徴

- **虹色パーティクル**: 各文字が美しい虹色のグラデーションで表現され、約150個のパーティクルが「anime.js」の文字を形成します
- **インタラクティブ**: マウスやタッチ操作でパーティクルを自由に動かせます
- **3D背景**: Three.jsを使用した地球と月の3Dモデルが背景で回転します
- **滑らかなアニメーション**: anime.jsによる流体的で自然な動きを実現
- **レスポンシブ**: すべての画面サイズに対応

## 🚀 デモ

[Live Demo](https://sinjorjob.github.io/animejs-particle-text/)

## 💻 使用技術

- **[anime.js](https://animejs.com/)**: パーティクルアニメーションとエフェクト
- **[Three.js](https://threejs.org/)**: 3D惑星背景の実装
- **Vanilla JavaScript**: ピュアJavaScriptで実装
- **CSS3**: グラデーションとビジュアルエフェクト

## 🎮 操作方法

- **マウス移動**: パーティクルがマウスカーソルを追従します
- **タッチ操作**: モバイルデバイスでタッチ位置にパーティクルが集まります
- **自動アニメーション**: 操作しない場合は自動的に美しいパターンを描きます

## 📦 セットアップ

1. リポジトリをクローン:
```bash
git clone https://github.com/sinjorjob/animejs-particle-text.git
```

2. `index.html`をブラウザで開くだけで動作します（サーバー不要）

## 🎯 特別な機能

### パーティクルエフェクト
- 各パーティクルは個別の色相を持ち、全体で虹色のスペクトラムを形成
- 立体的なグラデーションとシャドウによる深みのある表現
- パルスアニメーションによる生命感のある動き

### 3D惑星背景
- NASAのテクスチャを使用したリアルな地球
- 月の満ち欠けと地球照の表現
- 星空と大気光のエフェクト

## 🛠️ カスタマイズ

文字パターンは`letterPatterns`オブジェクトで定義されています。新しい文字を追加したり、パーティクルの配置を変更できます：

```javascript
const letterPatterns = {
  'a': [
    [50, 35],  // 頂点
    [45, 45],  // 左の斜線
    // ...
  ],
  // 他の文字...
};
```

## 📝 ライセンス

MIT License

## 🙏 謝辞

- Claude Code (Anthropic) - Vibe Codingでの開発支援
- anime.js - 素晴らしいアニメーションライブラリ
- Three.js - 強力な3Dグラフィックスライブラリ

## 🔗 リンク

- [GitHub Repository](https://github.com/sinjorjob/animejs-particle-text)
- [Live Demo](https://sinjorjob.github.io/animejs-particle-text/)

---

Made with ❤️ using Claude Code's Vibe Coding