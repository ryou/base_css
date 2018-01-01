# CSSの初期化調査

今まで前職のリセットCSSをそのまま使っていたので、リセット（ノーマライズ）CSSを自身で選別する。


## 使用ファイル

### Normalize.css

[Normalize.css: Make browsers render all elements more consistently.](https://necolas.github.io/normalize.css/)

デファクトスタンダードである`Normalize.css`をまず最初に適用する。

### Eric Meyer’s “Reset CSS” 2.0

[Eric Meyer’s “Reset CSS” 2.0 | CSS Reset](https://cssreset.com/scripts/eric-meyer-reset-css/)

`Normalize.css`は、そのままだとマージンが当たっている要素が多く、「見栄えはそのままでタグのみを変更したい」といった要求を満たせない。

そのため、リセットCSSをその上に当てる。
