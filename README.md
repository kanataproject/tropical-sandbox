# tropical-sandbox

Sandbox for exploring tropical algebra — from min-plus basics to applied geometry experiments.

トロピカル代数の実験場 — min-plus代数からジオメトリ生成実験まで

## デモ

https://kanataproject.github.io./tropical-sandbox/

## 現在のコンテンツ

### トロピカル代数 可視化ツール (`index.html`)

min-plus代数の動作を視覚的に確認するツール。

- **1変数　折れ線** — トロピカル多項式が区分線形関数（折れ線）になる様子を確認。係数スライダーで折れ目の位置がリアルタイムに変化する。
- **2変数　トロピカル直線** — 3つの領域の境界線としてY字型のトロピカル直線が出現する様子を確認。係数a・bが「向き」、cが「広がり」に対応。

## 理論的背景

トロピカル代数は通常の足し算・掛け算を以下のように置き換えた代数系。

```
a ⊕ b = min(a, b)   // 足し算の代わり
a ⊗ b = a + b       // 掛け算の代わり
```

この置き換えにより、滑らかな曲面がトロピカル化されると多面体フレームが得られる。「どの項が最小か」の境界部分だけが残ることで、ポリヘドラルな骨格構造が自然に生成される。

## 今後の実験予定

- 断面の積み上げによる3Dワイヤーフレーム生成
- 視界計算・FOVへのトロピカル演算の応用
- モーショントレースへの転用検証

## 参考文献

- Maclagan — [Introduction to Tropical Algebraic Geometry (2012)](https://arxiv.org/abs/1207.1925)
- Richter-Gebert, Sturmfels, Theobald — [First Steps in Tropical Geometry (2003)](https://arxiv.org/abs/math/0306366)

## ライセンス

MIT
