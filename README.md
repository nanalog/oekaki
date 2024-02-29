# Go言語最終課題成果物: お絵かきアプリ

## 内容

### できること

* お絵かき
* 一つ前の工程に戻る
* 全て削除する（Dkey または　ゴミ箱画像選択で実行）
* 文字の大きさの変更

### 構成

<pre>
.
|__ main.go
|__ game.go
|__ uiimage.go
|__ image
|__ bar.png
|__ hude.png
    |__ return.png
    |__ sq.png
    |__ trash.png
</pre>

### 使用しているパッケージ
<pre>
* fmt
* os
* image/color
* math
* slices

* github.com/hajimehoshi/ebiten/v2"
* github.com/hajimehoshi/ebiten/v2/ebitenutil
* github.com/hajimehoshi/ebiten/v2/inpututil
</pre>
### 学んだこと

* Ebitengine
* Slice の初期化、削除、追加、スライス型
* package の分割、スコープ
* Ebitengine　が主。仕組みの理解からUI部分であるキー入力、マウス入力の所作

## Copyright of images
<pre>
[illustAC](https://www.ac-illust.com/main/) has the copyright of images under the img directory.
[Icon-Icons](https://icon-icons.com/) has the copyright of images under the img directory.
[iStock](https://www.istockphoto.com/jp/) has the copyright of images under the img directory.
</pre>
