# ggj2025 - スクラッチカードゲーム

ggj2025 team-F

## 概要

Webブラウザで動作するスクラッチカード風のゲームです。

## ゲーム内容

- 3×3のマスに1〜9の数字がランダムに配置されます
- 最も多く出現した数字とその出現回数からスコアを計算します
  - スコア = 数字の値 × 出現回数
- 10回カードを引いて、合計スコアを競います
- 最後にランキングが表示されます

## プレイ方法

### GitHub Pagesで確認する場合

1. リポジトリの Settings > Pages に移動
2. Source を "Deploy from a branch" に設定
3. Branch を "copilot/add-scratch-card-game" / "root" に設定
4. Save をクリック
5. 数分待つと、`https://molpheus.github.io/ggj2025/` でアクセス可能になります

### ローカルで確認する場合

1. リポジトリをクローン
2. `index.html` をブラウザで開く

```bash
git clone https://github.com/molpheus/ggj2025.git
cd ggj2025
# ブラウザでindex.htmlを開く
```

## スコアリング例

3×3のマスに以下のように数字が配置された場合:
```
5 3 7
5 2 5
1 8 5
```

5が4回出現しているため:
- スコア = 5 × 4 = 20点

## 開発

このゲームは単一のHTMLファイルで構成されており、外部依存関係はありません。
