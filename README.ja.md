# PoseNet2Scratch

*Read this in other languages: [English](README.md), [日本語](README.ja.md)*

PoseNet2Scratchは人の姿勢を検出し、身体の各部分のxとyの位置を取得できるScratch拡張ブロックを追加することができます。

<p>

<img src="posenet.gif" width="400" />

<img src="posenet2.gif" width="400" />

</p>

PoseNet2Scratchは、これを拡張機能として追加できる[独自バージョンのScratch 3](https://champierre.github.io/scratch/)で体験できます。

## 使用例

1. ブラウザで https://champierre.github.io/scratch/ を開きます（Chrome推奨）。

2. 「拡張機能を追加」ボタン（+が付いたフォルダのアイコン）をクリックします。
<img src="images/ja/extension.png" width="400" />

3. 「PoseNet2Scratch」拡張機能を選択します。
<img src="images/ja/posenet_extension.png" width="400" />

4. PoseNet2Scratchのブロックを使用できます。
<img src="images/ja/posenet2scratch_blocks.png" width="400" />

5. Webカメラでキャプチャした画像をステージ画面に表示するには、「Video Sensing」拡張機能を選択します。これは必須ではありません。
<img src = "images/ja/video_sensing.png" width = "400" />

6. 「Glasses」(眼鏡)スプライトを追加します。
<img src="images/en/glasses.png" width="400" />

7. 以下のようなコードを作ります。
<img src="images/en/blocks.png" width="400" />

8. 顔の中央（鼻のx位置）と目の高さ（左目のy位置）に眼鏡が表示されます。
<img src="images/en/face.png" width="400" />