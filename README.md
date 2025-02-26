# 追加レビュー件数の最小化問題


## 問題

上司から, 「Googleの平均口コミ評価を上げてくれ」との指示が出た.<br>
<br>
私は, あと何件のレビューを獲得することができれば, 目標を達成することができるだろうか.


## 問題の設定
- 現在のレビュー件数 : n (n > 0)
- 現在の平均口コミ評価 : m (1 ≤ m < 5)
- 目標平均口コミ評価 : M (m < M < 5)
- 追加レビューはすべて星5と仮定
- 追加レビュー件数をxとする ← 今回求める


## モデル
追加レビュー件数最小化の式は次のようになる.
$$
\frac{mn + 5x}{n + x} \geq	M
$$

xについて解くと,

$$
x \geq	\frac{n(M - m)}{5 - M}
$$
